# hello_world
Task list and resources to setup SQL and Python environments
Hey Aidan!  Welcome back from your big trip.

You've been asked to jump in and help your friends from BizSmart to build a secure back-end.  That's bad ass.  You only have to 
turn yourself into a coding wiz overnight.  Use your time during Spring Break wisely and we'll make ALoT of progress.

I've been working on learning to code, do you want to explore this together?

You may remember that Github is a code repository, this allows you to collaborate with other developers on the same codebase.  
You can share code, ask for help, follow people.  Its basically a social network for developers.  Like a community of mad scientists, all building stuff.
What is SQL? It stands for 'Structured Query Language' and it's the standard language for manipulating data in tables.  .
Its a database programming tool. Your team needs to you create a system where they can send and retrieve data.  The app is 'dumb', once someone has added an account, that data needs to be stored.  As they add things to their account, that data needs to be stored too.
You can check out the SQL wiki for more info.  They will also need you to manage the schema of the database.  more on that later..
As a Back-End engineer, as one of your first priorities you will need to learn SQL (pronounced 'seequill').  

FIRST  SET UP ENVIRONMENTS

Ok, so here's what I've done so far....

1) installed Pycharm (Python IDE) and Datagrip (SQL IDE) from Jetbrains

2. installed SQLite: download can be found here.  Get the Mac OSX binaries.  This is a light weight SQL shell I'm using to learn SQL.

3. Download a sample SQLite database (for learning & testing): link
Scroll down and download this file: ChinookDatabase1.4_Sqlite.zip

4. In the finder on your machine, move this .zip file out of the downloads folder into a new 'Coding' project folder titled 'Sample Database' make sure this file is nested under 'Aidan' (keep all your files together).  Unzip the file.

5. Open Datagrip.  We need to connect the data source 'Chinook' to Datagrip.  Open 'Data Sources and Drivers' in Datagrip (here's a quick tutorial link)  The Chinook data base is a local file scroll down in the tutorial until you see local files and SQLite.  You need to specify the pathname which is easy, just follow the steps in the tutorial link.  Make sure to click 'download missing drivers' in Datagrip.

6. Now that you've connected your database to your IDE, Datagrip will open project for you and you have a familiar coding shell.  

7.  Now what?  Learn SQL!  Here's a link to the list of commands and a tutorial:  link.  Khan Academy has a SQL course too.  We talk about this and work through exercises.  Here's a link  to the schema for the Chinook Database (a schema is like a map)


This is all preparation for the next big step.  
CREATING the SERVER ENVIRONMENT

Read this guide for an overview and lets meet up to story board the process.
Lots of stuff to learn here.  We are going to be working on setting up a virtual server on our local machine, which we'll call localhost.  Once we feel comfortable that we can set up and install all the necessary components.  We'll take the next step and set up an AWS instance.  We'll create a free test account and install the software on a cloud server.

We'll practice establishing a secure connection and then working with an SSL certificate.

If the developers on the front end team work with Django  you will have a complete stack written entirely in Python!!

As promised, here's the link for the Jetbrains tools to connect Pycharm with Github!!

