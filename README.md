# Database

### Relational Database System

#### Tools and Techniques
I used two main tools. The first one being Draw.io which I used to create my ERD (Entity Relationship Diagram) to show how my tables within my Database's are related. Additionally, the other tool I used was Microsoft Excel, which is the tool I used to create my Data dictionary.

Similarly to my tools I used two main techniques; the first being an Entity Relationship Diagram. Within my Entity Relationship Diagram I created 5 tables, which were called: Enemies, Heores, Enemy_skills, Hero_Skills and finally Skills. The other technique I used was a Data dictionary, which was a table within Microsoft Excel that showed the information that was going to be in each table.

Here is my Data dictionary:

![](https://gyazo.com/805ba589dc7f2a0b6f02daa0deeaabba.png)


Here is my Entity Relationship Diagram:

![](https://gyazo.com/6d11585373bece5d1ef3f1edbb543899.png)

### User stories
I needed to create 10 user stories and here they are:

As a user I would like to see how much damage an enemy does

As a user I would like to see how much health an enemy has

As a user I would like to see how much damage a hero does

As a user I would like to see how much health a hero has

As a user I would like to be able to create and add new heroes using a form

As a user I would like to be able to create and add new enemies using a form

As a user I would like to see what a heores stats are

As a user I would like to see what a heroes stats are

As a user I would like to be able to view a heroes level

As a user I would like to be able to view an enemies level


### Forms
Here at two forms; one shows a form of an Enemy and the other shows a form of a Hero.

![](https://gyazo.com/dd1b3dbbd3590b36668bb27037903e23.png)

![](https://gyazo.com/475996880b81a422ea519eddbf2b5b4b.png)

### Data Validation
Here is an error message that pops up withint the Heroes table if a user wants to use a name that is already in use:

![](https://gyazo.com/0332d640292aae23cdcddcc42c6a866d.png)

This is also an error message that pops up, but this time it is because a user is trying to insert a character that has the damage of 1200, which is too high:

![](https://gyazo.com/db7472363652caeb49c116c0000ac626.png)

### Reports
These reports shows all of the data within a table in a easy to read manner. In this case the report is of the table Heroes, the data it shows is Species, Name, Level, ID and HP. The second report is off the Enemy table which shows data such as ID, Name, HP, Damage and Stats.


![](https://gyazo.com/4aeefa745239953f6605f010122cb5eb.png)

![](https://gyazo.com/6882f39f50248c041f8a5da7c3468adf.png)

### SQL Code
These sections of code are code I used to help my create my Database. While creating my Database I made code to create tables, insert, update, delete and select data.

These are a few examples of the code i used when creating new tables.

![](https://gyazo.com/1b7f4ec42584c55b6ee2975fca20848c.png)

![](https://gyazo.com/5438ed0edb1cad57e87b979b94ddd446.png)

![](https://gyazo.com/76f38c78107dc9df0d223f1a3471336a.png)

![](https://gyazo.com/fe7384a90017553cc8e2268bdb0804bb.png)

![](https://gyazo.com/19e2d500a6f2110540f25ecd4c735dea.png)

These are a few examples of code I used to insert different types of data into my tables:

![](https://gyazo.com/9f256e6fdc77c4917e0d1ac46b8b6412.png)

![](https://gyazo.com/eac60014082d73832157c6d3ed0fd80c.png)

![](https://gyazo.com/7c695b3320c12eb09364eaf27aebb769.png)

![](https://gyazo.com/4a764bafc5d80eaceb4de023c5cf8965.png)

![](https://gyazo.com/72ce94ce6085342ef5369512142eecd0.png)

When it came to updating values and data within my tables this is the code I would use:

![](https://gyazo.com/20ab24c40d70cd2cc138fb57a20ce6e3.png)

![](https://gyazo.com/d42dbe0b6937b0f9662a0c0bd49489f3.png)

![](https://gyazo.com/440544d6095b878b979c6d190c53be35.png)

![](https://gyazo.com/14722ad06884abf25f6d9d24dbed6450.png)

![](https://gyazo.com/e0f39efe17596bac3fc4ecd828444c54.png)

If I needed to delete mass amounts or even small amounts of data and values I would use this code:

![](https://gyazo.com/7fc91f11031ba6c7744558bb59fc1e39.png)

![](https://gyazo.com/47658eafc58028acfdceb61b65f7e78d.png)

![](https://gyazo.com/7daff3bff328f933e27ce34420941bcf.png)

![](https://gyazo.com/7d09ff35f134535c6379d87a44a56758.png)

![](https://gyazo.com/a750705b55ca0664d966ef4b0710c79b.png)

When it came to selecting values and data I wanted to update or delete I would use this code to select a table or piece of data:

![](https://gyazo.com/bd6d331d5ebbeff7298e3cd5be72fcca.png)

![](https://gyazo.com/e8e9d10e41b1a7a442e8afe1077b66aa.png)

![](https://gyazo.com/5aa97b786c3eaa5822bbd3a30d7161cb.png)

![](https://gyazo.com/45727a9e7f986f62238cc717b64cb725.png)

![](https://gyazo.com/1e82301da2e4711b85d9767a153af5cd.png)

### Test plan
Here is the test plan I made to test my Database

![](https://gyazo.com/92044f48401dd3c59b7798b147eeab2a.png)

Additionally here are some screenshots of me testing my database:

![](https://gyazo.com/dd1b3dbbd3590b36668bb27037903e23.png)

![](https://gyazo.com/475996880b81a422ea519eddbf2b5b4b.png)					
					
![](https://gyazo.com/0332d640292aae23cdcddcc42c6a866d.png)

![](https://gyazo.com/db7472363652caeb49c116c0000ac626.png)

### User and Technical documentation
My data 9base is was developed and designed to hold different types of data, about characters that are in my game. The data base contains several tables called, Enemies, Heroes, Enemy_Skills, Skills and Hero_Skills. Each table contains different types of data and data values. These types and values are Health, ID, Name, Damage, Range, Hero_ID, Enemy_ID and Weapon; because these values are for a game these values will be updated and changed in real time.

#### Role of a database system
The need of a database system comes in many forms. Most databases are used to store information/data in a neat and easy to ready manner. Databases are especially good tools to use because of how easy it is to access or change data. One role of a database can come in the form of a Back-end system. The general jist of a back-end system is that it can be used/accessed by more than one user through a third-party program/application. Next we have the role of a database within an E-Commerce environment. In essence a database's role within an E-commerce environment is to store customer information such as the businesses customer care, customer transactions and the inventory of the business. The last role of a database im going to mention is its role within data mining applications. Data mining is the process of looking through big data sets to try and find identity patterns and to establish relationships that help to solve problems using data analysis. Within businesses data minign allows businesses to predict future trends. During data mining one or more databases are searched for information (that is predefined by who ever is data mining) that will help in the process of finding new patterns within the data.

#### What is the system for?
I designed my system to store characters health, damage, range, ID, their names and their species. I will use this database to hold all of this information so I have a place I can go to see every character in my games stats. Additionally, this will help me compare characters, help we work on seeing if any are over powered or need improving/buffing. Lastly, I will be using this database to keep up to date with each characters stats which I will be uppdating daily to make sure I keep up to date with all my characters.

#### Risk and Contingencies within my Database
There are a few risks that come with any database:

1. When it comes to my forms, a risk would be the from not showing the correct information that is within the tables.
2. Next we have the risk that my tables will not have the correct informtaion within same as they are not updating.
3. This risk is to do with my reports, and it is the risk that my reports about my forms and tables will not update meaning I will be looking at out dated information
4. Lastly this is the risk my code will be wrong or will contain problems.
5. The computer I am using crashes or does something of this sort.

Here are the contingencies I can put in place to help prevent/reduce these risks:

1. Make sure I triple check all my code to make sure it works properly and performs how I want it to perform.
2. Have back ups of all of my documentation and code to make sure I reduce the risk of me losing important data.
3. Make sure I follow my Entity relationship diagram to help me keep on track when it comes to efficency and productivity, and to make sure im not working on something I dont need to be as I have a design of what my end goal should look like. This reduces the risk of losing time spent on useless things.
4. Lastly, to have backups of nto just work, but the database as a whole to make sure if I make a huge mistake I can just go back to a previous back up.

#### Design decisions and influences.
Firstly, I designed an entity relationship diagram to make sure I knew how I wanted each character of my game to play out for example what stats and skills it had such as damage and health. Additionally, I used the ERD to see how each table for example what type of relationship my Hero table and my Hero_skils table would have whether that be a one to many relationship, a many to many relationship and so on. I thought a ERD would be the best place to start with my database design as it would give me an idea about relationships and base ideas of skills that characters would have. Lastly, an ERD helped me meet the base requirements of the database such as why am I making a database, what am I going to use it for, who would be in my databse, what would they do, how would they fight and with what skills.

#### What influenced my design
The biggest factor that influenced my design was the fact it was going to be about a game. As I knew it was about a game I knew I had to base my designs and database around showing off the characters stats such as the heroes and the enemies health, damage, range, and ID. Additionally, knowing I was making this database for a game helped me keep on track as I knew what my goal was the whole time.

#### Functional design decisions 
I knew I was going to make a database for a game. This meant my database needed to have the functionality to support and be based off my game. Knowing this I made the database able to hold heroes and enemies stats/skills. As I had a strong idea of what I wanted from the start it helped me achieve the goal of creating a functional database that could hold character stats and skills that I could easily change, delete and update when needed.

#### Database system decisions
The tool I needed to use to create my database in had to give me a lot of posibilities when it came to managing and running the database. I chose Microsoft Access as I felt it gave me all the tools and things I needed to create a database, that would help me professionally and easily store and show off my data about my game. Additionally, the type of tools Microsoft access had that helped me make the perfect database where being able to have reports of my tables and forms, being able to create easy to read tables, being able to create forms and reports that would update in real time and finally being able to use SQL queries to better off my database. Microsoft access and its tools helped me create the database that was perfect for checking off the requirements. 

#### Security of my database
As this project was an individual one I created the game and database on my own. This means it was a private database that only I had access to. It was better I kept the database private as it reduced any risk of my database becoming compromised, deleted, changed or lost. To go with this I made sure I kept back ups of my database and the documentation within in so it the case that my database was accessed by a hacker I would not lose out on the time, effort and data I put into the database if the hacker decided to delete or change anything within it.

#### Maintenance and performance of my database
When it came to the performance of my database I was very pleased with how it panned out. As the database was small and did not contain much information it had no problem running. The maintenance of the database was very minimal too, as the performance side of the database went so well I did not need to perfrom any big maintenance changes or updates to the database. As my database contained all the information it needed to, there was no need for the database to be bigger, this helped with the maintenance and performance of the database as it was small enough I came across little to no problems.

#### Detailed database design
Within my database I knew there were certain things I needed to add to cater to the requirements. One being having 5 tables that would show skills that characters would have. The 5 tables I created were Heroes, Hero_skills, Enemies, Enemy_skills and Skills. Each table within my database were thought about before hand within my ERD. This is where I planned out what skills characters might have and what type of relationships enemies and heores might have, like I referred to earlier if this would be a one to many, many to many or many to one relationship. In this case the relationship between these tables were many to many as there are many skills that belong to many enemies and there are many enemies that have many skills. Within my database the forms main job was to store and display the tables data in a clear and easy to read manner. Additionally, the reports within my database would show a more detailed view of each table I had, this helped me look at each table as a whole and decide if I was happy with it. Lastly, the reports would update in real time, which made the database smaller and easier to maintain as I did not need to create a new report everytime I removed, added or changed data.

#### Resultant data structures and data software objects
Each form I created I made sure came with a set of buttons that would allow me to edit the data and values that is in each table instead of having to go back and edit each table which allowed me to change and update the forms with ease. Another button I made sure I implemented was a button to allow me to delete sections of the database all at once I felt were not needed. When designing and bulding my database my goal was to create one that was very easy to maintain, edit, change and add data to, with this being said within my database I made sure there was more than one place that data can be change and uploaded for example, it can be done within a table or within a form instead of just within a report. I did this because I felt it would make my database run smoother if my reports were a place that was more for showing off and displaying data instead of the place I go to delete, add, change or edit data.

### Tools used
There are four main tools I used to create my database:

* Microsoft word -  I used Microsoft word for my documentation such as the User and Technical documentation.
* Draw.io - I used Draw.io to make my ERD (Entity relationship diagram) that showed character relationships and their skills.
* Microsoft access - I used Microsoft access to create the actual database in.
* Microsoft excel - I used Microsoft excel to create my data dictionary which displayed characters skills. I also used Microsoft excel to create my test plan in which was how I went about testing my database.






























