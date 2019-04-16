---
layout: post
title:      "What’s in a Class"
date:       2019-04-16 23:56:46 +0000
permalink:  what_s_in_a_class
---


This week we covered more of Object Oriented Programming.  
I struggled this week with the more advanced methods of OOP and the information that I was learning in the labs, group sessions, and study groups wasn’t sticking. Since everything in Ruby is an object, *whatever that means*, I was determined to use my handy dandy Google search to find additional learning sources. I’ve found wonderful resources and decided to gift wrap this information for you. The sources I used to gather this information will be located at the end of this blog. 

### Quick Definitions

* *Class:* Tells Ruby to make a new type of thing
* *Object:* Any instance of something
* *Instance: *What you get when you tell Ruby to create a class
* *Def:* A function inside a class
* *@: *Located within the class function; A variable for the instance (or object) being accessed
* *Attribute: *A property class that are from composition and usually a variable

### Using the Definitions in a Sentence

* class X	...	def initialized (j)		  -->                                                  Class X has an initiate that takes in j parameter
	
	
* class X    ...    def initialized m (j)               -->                                            Class X has a function named m that takes in j parameter
	
	 
* word= X.new                  -->                                    Sets word to an instance of Class X

* word.m(j)                -->                                             From word, get m function and class it with j parameter

* word.k=q                 -->                                            From word, get the k attribute and set it to q

I have been drilling  the Quick Definitions and Using the Definitions in a Sentence sections into my head. Okay, now lets jump into some of the main things that you need to know. FYI, this blog does not cover self but I intend to cover it later. 

1. Everything in Ruby is an Object. Objects have methods and attributes
2. The class keyword has the ability to create new Ruby objects of the class. Class names also start with a captial letter. 
      2a. A class is a constructor that groups functions of data and pulls them inside a 'container' so you can access it with the . (dot) operator
3. Initialize is a function that "boots up" each object the class creates
4. A scope of a variable is the context in which it is visble to the program. Global variables can be defined outside of a class or within a class by using $. Class variables belong to the entire instance of a class. In other words, they belong to the class and start with a @@. Instance variables have a more limited scope and belong to a particular object. 

Now lets pull in some sample coding. Don't forget to use the Using the Definitions in a Sentence section to help explain what is going on. 

```
class Car
@@car_dealership_count=0
def initialize (make, model)
@make= make
@model=model
@@car_dearship_count +=1
end
def self.number_of_cars
@@car_dealership_count
end
end

CarA=Car.new("Toyota", "Corolla")
CarB=Car.new("Camry","Accord")
```


Here are the links that I used which you might find useful:

[https://www.geeksforgeeks.org/ruby-constructors/](http://)
[https://makandracards.com/sandheep/16245-difference-between-attr_accessor-and-initialize](http://)
[https://launchschool.com/books/oo_ruby/read/classes_and_objects_part1#initializinganewobject](http://)



