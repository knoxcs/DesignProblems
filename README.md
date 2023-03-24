# Homework 1

Your task for homework 1 will be to implement a design problem from CS 142. Below are design problems from a few years back. your task is to discuss and implement one of them. You will 

## CS 142: Program design and methodology 
## Design Problems
The following are the design problems students wrote in 2015. For each of them, identify the ADT(s) and/or implementations needed to solve these computational problems. 

1. The Justice League has had another run in with the Legion of Doom, led this time by Vandal Savage. The Legion’s newest scheme involves pelting the earth with a series of giant meteors. The plan is to cause widespread earthquakes and therefore destruction, ushering in a new age of civilization, with Vandal Savage in charge. Luckily, Batman has a contingency plan for every situation. He is going to have Superman fly up into the atmosphere and use his heat vision to destroy the meteors (or at least blow them up into smaller pieces) in the order that they are going to reach the ground. Batman needs a program into which he can enter meteors as they are discovered and which will output the meteors in the correct order so that he can tell Superman which one to destroy next. 

2. You work in a grocery store as a stock person. One day, as you’re stocking the apples, you overhear a customer complaining about how she can never remember the different apples that she wants, and how she always forgets the names or appearances of different apple varieties. You then start to think of a way that would help customers to find the apples that they want. So, you create amazing computer software that lets you go between variety names and images. Specifically, you can enter the name of a variety and the program will show you a picture of an apple of that variety. Alternately, you can upload a picture of an apple and it will print the variety name. (The second part would actually be really hard; assume that these pictures can be processed into a canonical representation in which all apples of a given variety have the same image.) 

3. You are working for the Guinness Book of World Records on the record for most books published in a single year. You are tasked with entering the titles of books written by an author during some year, and your boss will ask for the size of the list. Because records must be double and triple checked for accuracy, others will be entering titles for that author and year as well. Before the titles are counted, duplicate titles must be removed. The size will be checked against the current record holder (initially Barbara Cartland with 23 novels published in 1976), so neither the author nor year needs to be kept since the list will be scrapped if its length does not exceed the current record. 

4. You are a Barista at a Starbuck coffee shop. The company recently implemented a membership program, for which customers swipe a membership card each time they come to the register. Based on the membership number on their card, the system brings up information on that customer. It includes what type of coffee they prefer so that Barista can provide better service and how many cups of coffee the customer has purchased. Every time a customer buys 3 cups of coffee, the system will automatically generate a coupon (“get one free”) in their account. (Note that the number of cups of coffee purchased will never exceed 3 because it is reset to 0 every time a coupon is generated.) 

5. It is the year 2020, and the zombie apocalypse has been terrorizing the world for 2 years now. You are the computer scientist in team of scientists trying to identify the different types of zombiea and their weaknesses. You want to be able to search for a type of zombie, and have the program return that zombie’s weakness. You also want to be able to do the search query as quickly as possible, as there are a constantly-growing number of zombie types. 

6. An online phone book company has hired you to implement their automated address book to store name and telephone number information on every household in town. The address book should be able to search by either name or telephone number, returning the other. Note that a telephone number may correspond to multiple people (everyone in the same household) and that a name may correspond to multiple phone numbers (common names or people with multiple phone numbers). Your system must also be able to print out a list of all the names in alphabetical order or all the phone numbers in numeric order.

7. A retail store manager wants to efficiently let customers check out in the quickest way possible during busier times. Their solution is a system on which customers ready to check out enter their name and the number of items they have. They are then directed to an appropriate line (line 1 for 1–10 items, line 2 for 11–20 items, etc). The system should keep track of the people in each of the lines so that it can provide each cashier with the name of the first person in their line, allowing each customer to be greeted by name. 

8. Two students, each in different sections of the same course, were fighting over which one has the more challenging professor. Knowing that you have learned a great deal about cataloging information in your computer science courses, they come to you and ask you to help settle the debate. They request that you make a program that will take assignment descriptions, each paired with the perceived difficulty of the assignment on a scale of 0–10. The program should then display the lists for each student in a two-column format organized by difficulty as follows: 
* 10 HW 6 Midterm 1 
* Final 
* 9 Midterm Final 
* HW 2 Midterm 2 
* HW 3 Quiz 1 
* HW 1 
* HW 6 
* ...

Each course’s assignments are listed in one of the columns. All the assignments at a given difficulty level are presented before any at a lower difficulty.

9. You want to create a personal record keeping system for first-person shooter games. Specifically, for each game it should record your KDA (kills, deaths, and assists) values; the number of times you’ve killed a character in the game, the number of times you’ve died, and the number of assists that you’ve made. You want to be able to look up this information for each game and also to update it as your stats change. 

10. It’s the year 3015 and the Earth is being evacuated due to ”environmental collapse”. You work for the government which is in the process of deciding who is worthy to be saved. You must keep track the people applying for transit visas. The process consists of two parts: 
(a) An initial filter in which people who applied earlier are given preference. Therefore it is very important to know the order in which applications are received. Once an application is reviewed, the person’s name will need to be removed. 
(b) An alphabetical file of those chosen for evacuation and their current home address. A worker must be able to search for a person based on their first name and find their home address. This is so that notifications can be sent out. 

11. Knox College wants to create a system which will allow faculty, staff, and students to reserve study spaces, classrooms, gym spaces, meeting rooms, etc. This system needs to be easy to use so that information can be found by using building names and room numbers. There already exists an interactive map of the campus so you are assigned the task of creating the ”inner workings”. Specifically, the system must be able to accept requests specified by room number. These requests are processed each morning, in an order determined by the submitter’s rank (president, dean, manager, professor, student, etc) and the time they were submitted (first-come first-served among submitters with the same rank).
