# Portfolio - Evan Baber

<br/>

## Portfolio Introduction & Professional Self-Assessment

<details>
	<summary> ⬇️ Text - Introduction & Self-Assessment </summary>

<br/>	
	
#####	When I began studying computer science at SNHU, I was the consummate image of an unsure beginner programmer.  Having spent nearly a decade working in another field, I had approached programming out of curiosity, found it interesting, and attempted to self-teach for a year or so.  I consider my time spent studying on my own to be valuable, although I was mired with the same uncertainties that are common to all programmers who have not yet started to program.  The consideration over which coding languages to study was a persistent worry.  I knew I should be attempting to build a portfolio of work, but had no idea what those projects should look like and where they should come from.  I was excited about certain areas in the field, but was discouraged that my work thus far all felt like the result of carefully followed tutorials.  
#####	I knew that if I truly wanted to make progress, that a more structured study environment would be the answer.  Thankfully, I found that my coursework in computer science alleviated my previous concerns and helped me concentrate on developing fundamental programming skills without fretting over specifics until before I was prepared to.  Additionally, my classes introduced me to topics that I hadn’t previously considered as part of a well-rounded computer science education as well as areas of interest that I’ve continued to pursue outside of class.
#####	Much of the unexpected value of my coursework has come from the more non-technical parts of the curriculum that I hadn’t previously considered when studying on my own.  My Collaboration and Team Projects class, in particular, gave me a perspective on how large projects can be accomplished by teams of developers that I hadn’t previously experienced when working on my own.  Considering how intricate large development projects can be, I now realize how crucial a working knowledge of version control is to any programmer.  Operating as part of a team when creating software is far more common than the alternative, and I’m much more prepared to work in that environment thanks to that course.
#####	Another standout non-technical course in my curriculum was my Software Development Life-Cycle class.  While I also took classes about the larger role of computer science within industry, this was the class that most closely laid out a workflow that development teams might follow in a real production environment.  After having seen the term “Agile” mentioned so often, I was able to experience how an Agile development team works in practice and had the opportunity to see how developers and their managers maintain open lines of communication with clients throughout a project.  As important as I consider the programming skills I learned in my technical classes, this class was the one that gave me the clearest impression of what software production looks like in person.
#####	While I was fortunate enough to take specific classes in data structures and algorithms, the class that I found gave me the closest understanding of these concepts was my Operating Systems course.  Much like I had been engrossed by learning how computers function at a hardware level by my early IT classes, I found the way an operating system functions to be truly eye opening.  It’s extremely helpful to have a base-level understanding of how data is stored, retrieved, and manipulated outside of the user’s view.  Understanding the sheer variety of methods a system can use to search for a piece of data gives me a great deal of respect for the process of making that decision, and the desire to learn even more about algorithms.
#####	In terms of pure programming coursework, I found my classes in Client/Server Development and Emerging Systems & Technologies to be the most edifying.  In the latter, I was able to build applications using a Raspberry Pi and a connected sensor hub to create tangible projects that interacted in real-time with the outside world.  Creating these projects gave me a new perspective and enthusiasm for building Internet of Things devices and how they might be employed.  In the former class, I had the opportunity to build custom methods to navigate a massive database, and learned how to translate the queries I wrote into useful visualizations.  With data fluency more important than ever, I was excited for each opportunity to practice data manipulation in my courses.
#####	Finally, and in what I consider to be a real gift on the part of the CS curriculum, I discovered a real interest in information security as part of my Secure Coding, Reverse Engineering, and Quality Assurance courses.  I found that combing code for vulnerabilities, learning how attacks were carried out, and writing tests to foil them was deeply engaging in ways I didn’t expect.  After my Secure Coding class, I even installed a security-based Linux distribution onto my old Raspberry Pi and turned it into a mini testing lab that I use in my free time.  This exemplifies my favorite part of my structured coursework at SNHU.  It helped me both develop foundational skills to solve programming problems and introduced me to areas of interest that I still pursue on my own.
	
<br/> -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -
	
#####	When choosing the artifacts for my portfolio, I decided that instead of exhibiting the most complex applications I had worked on, that I would rather present three pieces of code that showcased personal interests that I’ve developed during my time in the computer science program.  I knew from first creating them that I found their subject matter engaging, and that my enthusiasm for them would come through in their narratives.  While neither the longest nor the most algorithmically complex projects I’ve worked on during my coursework, I can say without a doubt that these programs represent my strengths as a programmer and areas I would be interested in developing a deeper understanding of.
#####	My first artifact is an Internet of Things temperature and humidity sensor built with a Raspberry Pi.  I had been excited to develop for the Pi long before I bought one, but finally getting to do so for my Emerging Systems and Technologies class validated my expectations.  I hadn’t personally considered IoT an area of interest prior to developing this project, but building and enhancing the sensor hub was eye-opening.   The nearly infinite variety of ways the sensors and outputs could interact to change the user experience helped me realize the possible implications well-considered IoT products might have.  I’m still proud of this project and my enhancements to it and hope I’m able to develop similar small form-factor applications in the future.
#####	My second artifact is a small SQL injection detector that parses input strings. As I mentioned in the portfolio’s introduction, information security came out of left field as an interest to me.  I knew I wanted to learn more about quality assurance and testing, but when detecting security vulnerabilities came up as part of automated testing, I felt as if I understood the appeal of cyber security.  Although my SQL injection parser is far from complex, it marks the first time I built a small module capable of being tacked on to a program to foil a potential attack.  I’ve since used it in several assignments to validate input, and realize the value of creating a toolkit of modules such as this to either use or reference when creating new programs.  Security is an increasingly crucial facet of any application, public-facing or not, and I’m very eager to see how I can explore the topic in the future.
#####	My third and final artifact is a CRUD module I wrote to interface with MongoDB databases with Python.  Architecturally, the program is simply a list of functions allowing the user to create, read, update, and delete database objects (plus some additional functionality added during enhancements).  Although simple in build, I treasure the experience of having had to build this module because it showcases solving a common problem with ingenuity.  Barely any business operates today without the need for database manipulation, but the ability to do so simply with built-in tools is often taken for granted.  With this artifact, I could create a data analysis environment from scratch where none existed before.  Although structurally simple, I like the convergence of data analysis and problem solving this artifact represents and opted to use it to round out the final spot in my portfolio.
	
</details>
<br/>

## Code Review

<details>
	<summary> ⬇️ Video - Code Review </summary>
	
<br/>
	
[![Code Review - Baber](https://img.youtube.com/vi/kq2h2wBWpD4/0.jpg)](https://www.youtube.com/watch?v=kq2h2wBWpD4)

</details>
<br/>

## Artifact 1 - IoT Temperature & Humidity Sensor Hub
	
<details>
	<summary> ⬇️ Code - Artifact 1 </summary>
	
<br/>
	
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
</details>	

<br/>

<details>
	<summary> ⬇️ Narrative - Artifact 1 </summary>
	
<br/>	

#####  The artifact I’ve chosen to submit for milestone two is a temperature and humidity reading application that I originally created in CS-350 in late 2020.  It is designed to be run from a RaspberryPi and formerly used a series of LEDs and an html dashboard to output its results.  Using a light sensor and a temperature and humidity reader plugged into a GrovePi HAT device on the Pi, the application only takes readings when the ambient light is above a certain threshold limit, and will take readings at timed intervals specified by the user.  I felt the original output system was lacking, so I modified it as part of my enhancements by adding an LCD display that I feel suits the spirit of the project much better.  I think the original design was suited more toward a remote weather station device, while my updates have pushed it closer to the beginnings of a smart thermostat.
#####	This milestone is meant to showcase an artifact that exemplifies software design and engineering. While the nature of the application itself is very simple, I think it constitutes a microcosm of different software development tasks that I could expect to encounter daily as a working programmer.  There are simple examples of time handling, looping, file I/O, peripheral devices, and a slight bit of UI integration in readying the json document for use by an html dashboard.  I’m also glad to be including this project in my ePortfolio because it shows an interest in Internet of Things development, which I learned more about and developed an interest in during the course of building this project originally.  Most programmers won’t really get the opportunity to concentrate on IoT devices, but I think the inclusion of a project in a developing field, and one that I can demonstrate interest in is more likely to stand out.
#####	I consider this artifact a success in demonstrating course outcomes.  In particular, the outcome “Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices…”  While the tools used in achieving this application’s goals aren’t complex, I consider the program’s brevity to be one of its merits, and the fact that it runs on a satellite device with the ability to broadcast data to a dashboard to be a somewhat unique use case.  I foresee each subsequent artifact as exemplifying a different course outcome, with algorithmic principles addressed in one, and security addressed in the next.  For now, I’d like my ePortfolio to give the impression of a well-rounded programmer rather than one seeking to specialize.
#####	Luckily, this milestone’s artifact was the same one that I just conducted my code review on last week.  Given that, all of my planned enhancements had already been documented in detail and were still fresh in my mind.  While some of my planned enhancements were more in the vein of maintaining coding standards, the ones I enjoyed implementing the most were those where I was choosing to alter the focus of the application or shore up its security.  While standards are valuable and in place for a reason, I found shifting the way the program worked to still meet its base requirements in a more creative way was much more fulfilling.  I think developing for a satellite system like the Pi puts me in a more creative mindset than a normal desktop development might.  Likewise, working with peripheral devices can present its own benefits and challenges.  While setting up the LCD output was easier than expected due to the simplicity of the included GrovePi functions, working out the times the program needed to briefly wait before taking readings was as much of a guessing game as ever.

</details>
<br/>

## Artifact 2 - SQL Injection Detector

<details>
	<summary> Code - Artifact 2 </summary>
	
<br/>	

``` c++
/*  This program creates a simple database and runs several attempts at SQL injection attacks against it
*   A database is initialized with four user accounts & passwords
*   A text-filter is used to detect potential injection attacks & could easily be used in a live environment as well
* 
*   For this method to be fully effective, the hypothetical user account creation tool would need - 
*       to implement rules forbidding spaces & uncommon characters (most do this anyway) to prevent false positives
* 
*   Failed injection attempts will return an error message
*   Successful injection attempts will return a readable copy of the database's contents
*/

#include <algorithm>
#include <iostream>
#include <locale>
#include <tuple>
#include <vector>
#include <sqlite3.h>

// Initializing needed variables for database & queries
typedef std::tuple<std::string, std::string, std::string> user_record;
const std::string str_where = " where ";

static int callback(void* possible_vector, int argc, char** argv, char** azColName)
{
    if (possible_vector == NULL)
    {   // no vector passed in, so we just display the results
        for (int i = 0; i < argc; i++)
        {
            std::cout << azColName[i] << " = " << (argv[i] ? argv[i] : "NULL") << std::endl;
        }
        std::cout << std::endl;
    }
    else
    {   // else the vector is passed into database and an entry is created
        std::vector< user_record >* rows =
            static_cast<std::vector< user_record > *>(possible_vector);

        rows->push_back(std::make_tuple(argv[0], argv[1], argv[2]));
    }
    return 0;
}

// Initialized database, defines structure
bool initialize_database(sqlite3* db)
{
    // Creates a simple three-column database to be probed: ID, Name, and Password columns
    char* error_message = NULL;
    std::string sql = "CREATE TABLE USERS(" \
        "ID INT PRIMARY KEY     NOT NULL," \
        "NAME           TEXT    NOT NULL," \
        "PASSWORD       TEXT    NOT NULL);";

    int result = sqlite3_exec(db, sql.c_str(), callback, NULL, &error_message);
    if (result != SQLITE_OK)
    {
        // error handler for failure to create database
        std::cout << "Failed to create USERS table. ERROR = " << error_message << std::endl;
        sqlite3_free(error_message);
        return false;
    }
    std::cout << "USERS table created." << std::endl;

    // Inserts four dummy accounts into the database
    sql = "INSERT INTO USERS (ID, NAME, PASSWORD)" \
        "VALUES (1, 'John', 'Pass1');" \
        "INSERT INTO USERS (ID, NAME, PASSWORD)" \
        "VALUES (2, 'Jane', 'Pass2');" \
        "INSERT INTO USERS (ID, NAME, PASSWORD)" \
        "VALUES (3, 'Jules', 'Pass3');" \
        "INSERT INTO USERS (ID, NAME, PASSWORD)" \
        "VALUES (4, 'Jim', 'Pass4');";

    result = sqlite3_exec(db, sql.c_str(), callback, NULL, &error_message);
    if (result != SQLITE_OK)
    {
        // Error handler for failure to properly insert data
        std::cout << "Data failed to insert to USERS table. ERROR = " << error_message << std::endl;
        sqlite3_free(error_message);
        return false;
    }

    return true;
}

bool run_query(sqlite3* db, const std::string& sql, std::vector< user_record >& records)
{
    
    // Simple search criteria for possible injections
    // All injection attempts will reqire an "or" statement
    // Stringent username & password criteria in a live system will prevent this from producing false positives
    std::string threatStr = " or ";

    // clears any prior results
    records.clear();

    // checks for threat string within a given command, positive yeilds an int
    try {
        // if found, throws an error
        if (sql.find(threatStr) != std::string::npos) {       
            throw 99;                                         
        }
    }
    catch (...) {
        // Will not execute command, thus no results to dump
        std::cout << "Error: Possible SQL injection detected ... Query failed" << std::endl;
        return false;     
    }

    // Exception handler in the event of SQLite error
    char* error_message;
    if (sqlite3_exec(db, sql.c_str(), callback, &records, &error_message) != SQLITE_OK)
    {
        std::cout << "Data failed to be queried from USERS table. ERROR = " << error_message << std::endl;
        sqlite3_free(error_message);
        return false;
    }

    return true;
}

// Chooses a randomly selected SQL injection tactic to append to a normal query attempt
// This method is run five times during Main()
bool run_query_injection(sqlite3* db, const std::string& sql, std::vector< user_record >& records)
{
    std::string injectedSQL(sql);
    std::string localCopy(sql);

    // we work on the local copy because of the const
    std::transform(localCopy.begin(), localCopy.end(), localCopy.begin(), ::tolower);
    if (localCopy.find_last_of(str_where) >= 0)
    { // this sql has a where clause
        if (localCopy.back() == ';')
        { // removes semicolon to allow injection to be appended, semicolon is reappended during attack text
            injectedSQL.pop_back();
        }

        switch (rand() % 4)
        {
        // Four flavors of the same " or " SQL injection attack
        // Weeding out the "or" keyword is essential in stopping injections
        case 1:
            injectedSQL.append(" or 2=2;");
            break;
        case 2:
            injectedSQL.append(" or 'string'='string';");
            break;
        case 3:
            injectedSQL.append(" or 'keyword'='keyword';");
            break;
        case 0:
        default:
            injectedSQL.append(" or 1=1;");
            break;
        }
    }

    return run_query(db, injectedSQL, records);
}


// Prints a copy of the SQL queries and the associated results to the console
void dump_results(const std::string& sql, const std::vector< user_record >& records)
{
    std::cout << std::endl << "SQL: " << sql << " ==> " << records.size() << " records found." << std::endl;

    // If injection is successful, this loop prints out the database's contents in a more readable form
    for (auto record : records)
    {
        std::cout << "User: " << std::get<1>(record) << " [UID=" << std::get<0>(record) << " PWD=" << std::get<2>(record) << "]" << std::endl;
    }
}

// Runs 6 SQL queries: 2 normal and 5 injection attempts
// Injection attempts will produce exceptions if handled well, readable DB resutls if not
void run_queries(sqlite3* db)
{
    char* error_message = NULL;

    std::vector< user_record > records;

    //  Query all
    std::string sql = "SELECT * from USERS";
    if (!run_query(db, sql, records)) return;
    dump_results(sql, records);

    //  Legitimate query
    sql = "SELECT ID, NAME, PASSWORD FROM USERS WHERE NAME='John'";
    if (!run_query(db, sql, records)) return;
    dump_results(sql, records);

    //  Run query with injection 5 times
    for (auto i = 0; i < 5; ++i)
    {
        if (!run_query_injection(db, sql, records)) continue;
        dump_results(sql, records);
    }

}

int main()
{
    // Initialize random seed:
    srand(time(nullptr));

    int return_code = 0;
    std::cout << "SQL Injection Example" << std::endl;

    // The database handler
    sqlite3* db = NULL;
    char* error_message = NULL;

    // Open the database connection
    int result = sqlite3_open(":memory:", &db);

    // Handles SQLite errors
    if (result != SQLITE_OK)
    {
        std::cout << "Failed to connect to the database and terminating. ERROR=" << sqlite3_errmsg(db) << std::endl;
        return -1;
    }

    std::cout << "Connected to the database." << std::endl;

    // Exception handler for bad database creation
    if (!initialize_database(db))
    {
        std::cout << "Database Initialization Failed. Terminating." << std::endl;
        return_code = -1;
    }
    else
    {
        // Runs our Queries, which in turn runs our injection attempts
        run_queries(db);
    }

    // Closes the SQLite connection, if open
    if (db != NULL)
    {
        sqlite3_close(db);
    }

    return return_code;
```
										
</details>	

<details>
	<summary> Narrative - Artifact 2 </summary>
	
<br/>	

#####	The artifact I’ve chosen to submit for milestone three is a SQL injection detector built in C++ that I originally created for CS-405 in early 2021.  While the program itself is mainly concerned with the building of the sample SQLite database, the detection portion shows off a simple text filtration method for testing user input for potential SQL injection attacks.  I began to develop an interest in information security almost from day one in my secure coding class, and really wanted to include an artifact from it in my ePortfolio to cover another area of interest that I discovered in my time at SNHU.  
#####	Admittedly, the more I peruse this program, the simpler it seems to me.  Upon further inspection, the actual security measure portion of my code occupies only a few lines.  However, I still believe it fits the bill of demonstrating the use of data structures and algorithms.  Algorithmically, it is very light, and aside from methods parsing text and slicing a final character form a string (and pre-built methods at that), I can’t say the artifact employs anything approaching a complex sorting algorithm.  The requirements of the program are light, and the tools used to accomplish them are similarly light.  
#####	When it comes to data structures, however, I’ve made use of tuples, vectors, and arrays for different uses throughout the program, especially as they pertain to setting up the architecture of my sample database.  While they may fall slightly short of the handmade linked-lists from my data structures & algorithms class, I wanted this artifact to balance structures I could easily explain with an information security task I was enthusiastic about.  To improve this artifact, I originally sought to strengthen the injection protection, improve a cluttered design, and make the program more understandable through in-line and header documentation
#####	I consider this artifact to demonstrate the following outcomes in particular: “Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution, while managing the trade-offs involved in design choices” and “Develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources”.  I believe the software engineering and design outcome to be represented here as well, although I think my previous artifact demonstrates it more purely than this one does.  
#####	When initially considering how to improve this artifact, I took for granted that I had left some sort of backdoor method open to circumvent the SQL injection protection I built into the program.  During some assignments, I felt as though a single type of attack was being circumvented while leaving the program open to others.  I even wrote my initial enhancement proposal on the understanding that my injection protection was second-rate and could be easily improved.  I was pleasantly surprised to find that a simple solution could truly be effective in this case.  Preventing injection is all about stopping the user from tacking on an equivalence statement such as 1=1 to their commands, and a text filter accomplishes just that.  In a wider hypothetical login environment, users would need to be forbidden from adding spaces to their usernames or passwords, which is already a ubiquitous standard as it is.  Aside from changing a bit of the aesthetic organization of the program, I brought all of the variable names under a simple standard, added more and better in-line comments, and provided a short block of header documentation.
#####	I found this artifact initially more challenging to enhance than the first.  Not due the complexity of the program, but due to its smaller scope.  At its base, this program is a demo showing how text entry fields can be guarded from a specific type of attack.  I consider the final product to be extremely successful in that regard and am pleased not to have tacked any unnecessary functionality that might muddy its purpose.  Like my first artifact did with IoT devices, I was eager to include this one in my ePortfolio to show enthusiasm for part of the CS field that I found an interest in through my coursework.  If I’m successful in my aims, I’ll have a portfolio that contains brief programs with clear purposes that demonstrate a diversity of interests rather than simply the most complex problems I’ve worked on.

</details>
<br/>

## Artifact 3 - PyMongo CRUD Module

<details>
	<summary> Code - Artifact 3 </summary>
	
<br/>	

``` python
######################################################################################
#   This a CRUD module written to interact with MongoDB databases                   ##
#       via Pymongo                                                                 ##
#                                                                                   ##
#      Functions exist for:                                                         ##
#          - Create / Create Multiple                                               ##
#          - Read / Find                                                            ##
#          - Update / Update Multiple                                               ##
#          - Delete / Delete Multiple                                               ##
#                                                                                   ##
#   Instantiating the class (in this case "Store") starts a MongoClient             ##
#       and allows access the the CRUD functions belonging to the class             ##
######################################################################################

from pymongo import MongoClient
from bson.objectid import ObjectId
from bson.json_util import dumps

class Store(object):

	# Class instantiation requires username and password of user capable of altering "MDB" class
	def __init__(self, username, password):
		self.client = MongoClient('mongodb://%s:%s@localhost:28697/?authMechanism=DEFAULT&authSource=MDB' % (username, password))
		self.database = self.client['MDB']


	# Method for Creating entries in a database
	def create(self, data): # data argument should be in dictionary form
		if data is not None:
			insert_receipt = self.database.payroll.insert_one(data)
	
			# Checks for confirmation of insertion & returns True
			if insert_receipt.inserted_id: 
				print("Insert successful")
				return True

			else:
				print("Insert failed")
				return False

		else:
			# Raises exception if data is passed in empty
			raise Exception("Nothing to create. Data parameter is empty")
			return False
            
            
    # Method to insert multiple entries, argument should be provided as an array
    def createMany(self, data):
        if data is not None:
			insert_receipt = self.database.payroll.insertMany(data)
	
			# Checks for confirmation of insertion & returns True
			if insert_receipt.inserted_id: 
				print("Multiple insert successful")
				return True

			else:
				print("Multiple Insert failed")
				return False

		else:
			# Raises exception if data is passed in empty
			raise Exception("Nothing to create. Data parameter is empty")
			return False


	# Method for searching for an entry in a database
	def read(self, query): # Query argument should be in dictionary form
		if query is not None:
			search_receipt = self.database.payroll.find(query,{"_id":False})

			# Print confirmation message & give cursor location of corresponding entry
			return search_receipt

		else:
			# Raise exception for empty 'query' field
			raise Exception("Read Failed. Search query is empty")


	# Method for updating a specified entry in a database
	def update(self, filter, updates):
		if filter is not None:
			update_receipt = self.database.payroll.find_one_and_update(filter, updates)

			# Print confirmation message & give cursor location or corresponding entry
			print("Update successful: ", dumps(update_receipt))

		else:
			#Raise exception for empty 'filter' field
			raise Exception("Update Failed. Update field not specified")
            
            
    # Method for updating multiple entries in a database
	def updateMany(self, filter, updates):
		if filter is not None:
			update_receipt = self.database.payroll.updateMany(filter, updates)

			# Print confirmation message & give cursor location or corresponding entry
			print("Multiple update successful: ", dumps(update_receipt))

		else:
			#Raise exception for empty 'filter' field
			raise Exception("Multiple Update Failed. Update field not specified")


	# Method for deleting a specified entry in a database
	def delete(self, delQuery):
		if delQuery is not None:
			delete_receipt = self.database.payroll.find_one_and_delete(delQuery)

			# Print confirmation message & give cursor location or corresponding entry
			print("Delete successful: ", dumps(delete_receipt))

		else:
			# Raise exception for empty 'delQuery' field
			raise Exception("Delete Failed.  Delete field not specified")
            
            
	# Method for deleting multiple entries in a database
	def deleteMany(self, delQuery):
		if delQuery is not None:
			delete_receipt = self.database.payroll.deleteMany(delQuery)

			# Print confirmation message & give cursor location or corresponding entry
			print("Multiple Delete successful: ", dumps(delete_receipt))

		else:
			# Raise exception for empty 'delQuery' field
			raise Exception("Multiple Delete Failed.  Delete field not specified")
```
	
</details>
	
<details>
	<summary> Narrative - Artifact 3 </summary>
	
<br/>	

#####	This artifact is a MongoDB crud module written in Python for my CS-340 Client Server Development class in early 2021.  The initial incarnation of the program was intended to interact with an html dashboard that displayed information about animals housed in rescue shelters.  For the sake of displaying a more common use-case, I changed the focus of the database to be employees on a store’s payroll.  Likewise, the content of the dashboard was so closely related to the animal shelter data that I opted to only include the crud module itself as part of my portfolio.
#####	When looking back over the database applications I worked on during my coursework, I found that nearly all of them focused on using ready-made environments to simply query databases.  Likewise, I found my experience in data mining to be very interesting and engaging, but difficult to replicate in code form because so much of it had taken place in virtual environments with very large datasets.  I was drawn to include this custom built crud module because it represented a situation in which I wasn’t presented with a console ready to accept queries, but rather needed to find a way to mesh Python code with an extant database.  I particularly enjoyed the process of writing functions for each database process and how they would be handled by the program calling them.  In the end, I felt having to write each process individually gave me a better understanding of each crud process and a greater appreciation of what it takes to set up a data analysis environment.
#####	In its first version, the crud module contained only the first four methods necessary for adequate database manipulation.  Beyond creation, reading, updating, and destruction, however, I felt like functions should be included to allow the user to manipulate multiple entries at once.  With this in mind, I included functions to create, update, and delete multiple entries at once using a few ready-made MongoDB methods.  Reading already returns multiple entries depending on the query, so it was able to stay as is.  I know that frequently database analysis requires users to make broad manipulations of data at once, and that limiting changes to a single entry at a time would pose a huge bottleneck to larger tasks.  Along with this addition, I improved the crowded spacing of the initial version, added more adequate in-line comments, and provided a block of header documentation to let users know the purpose of the module.
#####	In this artifact, I accomplish the outcome “demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals”.  Particularly, I found solving the problem of using PyMongo to allow Python code to manipulate a database to be a problem that I could very easily imagine a company facing if they weren’t adequately prepared when first approaching a database system.  Likewise, I’ve begun to consider the thorough commenting and documentation process as being a major part of “building collaborative environments” and “designing professional-quality oral, written, and visual communications” as outlined in outcomes one and two.  As a holder of a prior degree in a communications field, I have always appreciated when I am able to understand a program via its documentation without having to parse through the code first.  I think this type of communication is generally underappreciated among programmers until it is noticeably absent.  
#####	Unlike my previous artifact which I had initially intended to overcomplicate the scope of, the enhancements to this module fit precisely as I imagined they would.  From a birds-eye view, I knew that if this crud module were being used in a database manipulation environment, that the single-entry limit would pose a major obstacle as soon as more complex tasks became necessary.  Pleasantly, but unsurprisingly, MongoDB implemented standard methods for these tasks nearly six years ago, so tacking on the additional functions was a painless improvement that improved the effectiveness of the module greatly.  More than anything, I attempted to put myself in the shoes of a data analyst using my module after coming upon it for the first time.  I wanted my function names to hew to a simple standard, and for each function to be as well documented as possible to allow them to know the proper data types to input without time-wasting trial and error.  As mentioned previously, this was easily the database assignment that I was most thankful to have worked on during my courses.  Despite not having to write a single query, it helped me understand what an analysis environment looks like and that one can be created from scratch if need be.

</details>
<br/>

	
