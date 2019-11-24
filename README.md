Monon is an order pair that represent the coeffcient and the power in the phrase ax^b
this class can also build Monom from a given string such as ax^b without spaces when "a" is a double and "b" is a positive int
this class have a regular constructor(given a and b), a string constructor and a copy constructor. it can get and set the power and the coeffcient.
in addition it can do:
add and multiply the monon with another Monom
derivative the Monom
get the value in the given x
check if this is the Zero Monom
return a string that represent the Monom
check equality with another Monom
and get a new zero Monom

 

Polynom is an ArrayList of Monom (every _cell_ represent a diffrent power)
this class can also build Polynom from a given string such as ax^b+ax^b+... without spaces when every Monom should be in accordence with the rules of the Monom.
this class have an empty constructor(create an empty Polynom) and a string constructor..
in addition it can do:
add and multiply the Polynom with Monom
add, substract and multiply the Polynom with another Polynom
derivative the Polynom
get the value in the given x
check if this is the Zero Polynom
return a string that represent the Polynom
check equality with another Polynom
check if the Polynom contains a given power
get the root and the area of the Polynom between a given two numbers
return a copy
make an iterator


