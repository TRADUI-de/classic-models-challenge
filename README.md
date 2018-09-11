# TRADUI classic-models-challenge programming challenge

=== Goal
The goal is, that 

=== Tasks

=== Time estimation
Between ~1 hour up to ~3.5 hours, 
depending on your previous experience & development environment.

=== Part A (testing your SQL skills)

We prepared you an database example which is based on the "Classic Models" built-in database scheme of BIRT.

Please take a look at the SQLFiddle example at: ... url
In the fiddle you will find  different tables like "CUSTOMERS", "PRODUCTS" and so on.

The goal for this task is, that you show up the top 5 customers based on their order volume for each country.
Next, extend the exisiting query to identify the ratio of each top 5 customer of the total country order volume. Calculate it or use any built-in function.

### Part B (testing your Java skills)

In this last step fork / clone this java project. We prepared a small java project with a single main class. The project contains a CSV file with the required data from the "Classic Models" database from step one.
First read the required data from the csv file. Your goal is exactly the same task as in step one, only programmed in java.

Test your results in the included test class.

=== Getting started

Fork or directly clone the repository

git clone https://github.com/TRADUI-de/classic-models-challenge

or if you’ve forked the repository then

git clone git@github.com:YOURNAME/classic-models-challenge

=== Building and running

The project scaffolds provides a Maven pom.xml as starting point. You should be able to start with any IDE or text editor you are convenient with.

After installing Maven 3.x you should be able to

Run the main class de.tradui.challenge.classicmodels.ClassicModelsApp::

    mvn clean compile exec:java
	
Build & test your project::

    mvn clean test.
	
Or use your IDE functionality::

    to run & debug you program.

=== Submitting your results

Ideally you provide your solutions as Git repository with appropriate commits and descriptions. If you have a GitHub account (or create a new one), please feel free to publish your solution there.