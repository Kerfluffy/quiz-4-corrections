# quiz-4-corrections

#Question 1 

##Consider the following code snippet.

##String str = "Hello, there. My name is Joseph. What's yours?";
##char c = str.charAt(7);

##What is the value of c after running this code?

The correct answer is 't'. The reason it is ‘t’ is because char c = str.charAt(7); is a character data type. A character data type will be store with ‘’ and since the 7th index in String str = "Hello, there. My name is Joseph. What's yours?" is t, that is what you get.

#Question 9 

##Methods that return a value allow us to use them to perform some computation, and store (and later use!) the result of that computation.

The Correct Answer is True because the uses of a method can potentially be the usage of recalling statements for later use. Thus, false in incorrect because it does not follow the definition of a method.

#Question 11

##Match the access modifier with its visibility.

The correct answer is public being visible in all packages, private being visible only in the class in which its defined, default being visible within the class in which it's defined, as well as by classes within the same package, and protected being visible within the class in which it's defined, by classes within the same package, and by subclasses of the class in which it's defined. 
This is the correct answer because if you search up the definition of each class, it describes what the purposes are for the access modifiers . Default and protected classes are both “package-level access” classes, meaning that only classes in the same package can access it.

#Question 12

##Consider the following method definition.

##public double randomNumber(int seed) {
    ##if (seed > 1000) {
    ##    return Math.random() * seed;
    ##} else if (seed > 500) { 
    ##    return Math.random() * seed * -1;
    ##}
##}

##I keep getting an error message telling me that my method must return a value of type double. What's wrong with my code?

The correct answer for this question is "For seed values less than or equal to 500, the method does not return a value". 
This is because the if statements both have conditions where seed is more than 500, but there is no condition if that is not true. The other statements are not right about the code


