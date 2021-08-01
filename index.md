# This is Evan Baber's GitHub Pages ePortfolio - Still in Progress




## Code Review

[![Code Review - Baber](https://img.youtube.com/vi/kq2h2wBWpD4/0.jpg)](https://www.youtube.com/watch?v=kq2h2wBWpD4)

Description in progress

## Artifact #1 - IoT Temperature & Humidity Sensor Hub

``` python
######################################################################################
#   This program conducts temperature & humidity readings w/                        ##
#       the GrovePi's DHT sensor at a set interval (30 sec default)                 ##
#                                                                                   ##
#   A light sensor detects if ambient light is sufficient &                         ##
#       puts the device into sleep mode if not                                      ##
#                                                                                   ##
#   After readings are taken, the values are pushed to a .json document             ##
#       which is viewable via an associated html dashboard                          ##
#                                                                                   ##
#   *** Alter sleep value to change frequency of readings ***                       ##
#   *** Alter threshold value to change sensitivity of sleep mode trigger ***       ##
######################################################################################

import json
import grovepi
from grove_rgb_lcd import *
from time import sleep
from math import isnan

# Establish port numbers for each input & output
light_sensor = 0        # A0

# Establish port numbers for temp & humidity sensor
dht_sensor_port = 7     # D7
dht_sensor_type = 0     

# Establish port for red led (power light)
led_red = 3             # D3

# Set LCD color
setRGB(0,100,100)

# Establish a threshold value for light sensor
threshold = 30.00

# Allocates sensors to input & output functions (LCD established separately)
grovepi.pinMode(light_sensor,"INPUT")
grovepi.pinMode(led_red,"OUTPUT")

# Empty array to hold temp & humidity values - dumped to json later
dht_readings = []

# initial sleep to prevent crashes
sleep(1.0)

# While light threshold is met: take DHT readings
while True:
    try:
        # power LED stays lit unless an error occurs or the program is manually interrupted
        grovepi.digitalWrite(led_red,1)
        
        # Get light sensor value
        sensor_value = grovepi.analogRead(light_sensor)
        
        if sensor_value <= 0:
            resistance = 0
            
        else:
            # Calculate resistance of light sensor
            resistance = (float)(1023 - sensor_value) * 10 / sensor_value

        # if bright enough (low resistance), begin taking temp & humidity readings
        if resistance < threshold:
            
                print("working...") # confirms program is running for debugging
                
                # get the temperature and Humidity from the DHT sensor
                [temp,hum] = grovepi.dht(dht_sensor_port,dht_sensor_type)
                
                # takes celsius reading and converts it into Farenheit
                far_temp = round((temp * 1.8 + 32), 2)
                
                # print to terminal if available for debugging purposes
                print("temp =", far_temp, "F\thumidity =", hum,"%")

                # check if we have nans
                # if so, then raise a type error exception
                if isnan(temp) is True or isnan(hum) is True:
                    raise TypeError('nan error')

                # leaves json dashboard functionality in place so users can check readings remotely
                t = (far_temp)
                h = (hum)
                new_entry = [t,h]
                
                # Print temp & humidity readout to LCD screen
                # No blank screen between readings ---> only numbers change
                setText_norefresh("Temp:" + t + "F\n" + "Humidity :" + h + "%")
                
                # stored temp and humidity readings as nested lists for readability
                dht_readings.append(new_entry)

                # Outputs the contents of 'dht_readings' list to 'OutputFile.json' when program is interrupted
                with open('data.json', 'w') as outfile:
                    json.dump(dht_readings, outfile, indent=1)
                
                # Closes json file once readings are dumped each loop
                # Ensures file is closed even in the event of an interruption
                outfile.close()
                    
                # sleep set at 30 seconds between attempted readings
                sleep(30.00)

    
        else:
            # Switch off LEDs if too dark to take DHT readings
            print("Device currently in sleep mode")
            grovepi.digitalWrite(led_red,0)
                    
            sleep(1.0)

    except IOError:
        SetText("Error")
        sleep(5.0)
        SetText("")
        grovepi.digitalWrite(led_red,0)
    
    except keyboardInterrupt:
        SetText("Program manually interrupted")
        sleep(5.0)
        SetText("")
        grovepi.digitalWrite(led_red,0) 
```

######      The artifact I’ve chosen to submit for milestone two is a temperature and humidity reading application that I originally created in CS-350 in late 2020.  It is designed to be run from a RaspberryPi and formerly used a series of LEDs and an html dashboard to output its results.  Using a light sensor and a temperature and humidity reader plugged into a GrovePi HAT device on the Pi, the application only takes readings when the ambient light is above a certain threshold limit, and will take readings at timed intervals specified by the user.  I felt the original output system was lacking, so I modified it as part of my enhancements by adding an LCD display that I feel suits the spirit of the project much better.  I think the original design was suited more toward a remote weather station device, while my updates have pushed it closer to the beginnings of a smart thermostat.
######	This milestone is meant to showcase an artifact that exemplifies software design and engineering. While the nature of the application itself is very simple, I think it constitutes a microcosm of different software development tasks that I could expect to encounter daily as a working programmer.  There are simple examples of time handling, looping, file I/O, peripheral devices, and a slight bit of UI integration in readying the json document for use by an html dashboard.  I’m also glad to be including this project in my ePortfolio because it shows an interest in Internet of Things development, which I learned more about and developed an interest in during the course of building this project originally.  Most programmers won’t really get the opportunity to concentrate on IoT devices, but I think the inclusion of a project in a developing field, and one that I can demonstrate interest in is more likely to stand out.
######	I consider this artifact a success in demonstrating course outcomes.  In particular, the outcome “Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices…”  While the tools used in achieving this application’s goals aren’t complex, I consider the program’s brevity to be one of its merits, and the fact that it runs on a satellite device with the ability to broadcast data to a dashboard to be a somewhat unique use case.  I foresee each subsequent artifact as exemplifying a different course outcome, with algorithmic principles addressed in one, and security addressed in the next.  For now, I’d like my ePortfolio to give the impression of a well-rounded programmer rather than one seeking to specialize.
######	Luckily, this milestone’s artifact was the same one that I just conducted my code review on last week.  Given that, all of my planned enhancements had already been documented in detail and were still fresh in my mind.  While some of my planned enhancements were more in the vein of maintaining coding standards, the ones I enjoyed implementing the most were those where I was choosing to alter the focus of the application or shore up its security.  While standards are valuable and in place for a reason, I found shifting the way the program worked to still meet its base requirements in a more creative way was much more fulfilling.  I think developing for a satellite system like the Pi puts me in a more creative mindset than a normal desktop development might.  Likewise, working with peripheral devices can present its own benefits and challenges.  While setting up the LCD output was easier than expected due to the simplicity of the included GrovePi functions, working out the times the program needed to briefly wait before taking readings was as much of a guessing game as ever.


## Artifact #2

``` Still in Progress ```


## Artifact #3

``` Still in Progress ```



For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
You can use the [editor on GitHub](https://github.com/Walker1889/CS-499/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.
