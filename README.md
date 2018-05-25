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
