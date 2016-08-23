import UIKit

var str = "Hello, playground"
//AC3.2 - Week 1 - Homework

//I. Variables

//Question 1.
//Provide the following constants/variable names with the most appropriate type annotations.

//let firstName: Constant String
//let middleInitial:  Constant Character
//var age: Int Variable
//var latitude: Double Variable
//var longitude: Double Variable
//var isRainingCurrently: Bool Variable
//let completeAddress: String Constant
//let π: Constant

//Question 2.
//Convert the following decimal numbers to Binary:

// 55 = 32 + 16 + 4 + 2 + 1 = 00110111
// 122 = 64 + 32 + 16 + 8 + 2 = 01111010
// -1 = -8 + 4 + 2 + 1 = 10001111
// 15 = 8 + 4 + 2 + 1 = 00001111


//Question 3.
//Using nested loops, print the numbers from 0 to 100, then back to 0.

/*    for i in 0...100 {
        print(i)
        if i == 100 {
            for j in (0...99).reverse() {
          print(j)
            }
   }
}
 */


//Question 5.
//
// a)Using any kind of loop, print the sum of all numbers between 0 to 50.
// b)Using a while loop, print all the odd numbers from 0 to 100.
// c)Using a for case loop, print all the multiples of 10 from 50 to 500.


/*
for i in 0...50 {
print(i)
}
*/


/*var i = 0
 while i < 100 {
 i+=1
 if i%2==1 {
 print(i)
    }
 }
*/


/* for i in 50...500 {
 if i%10 == 0 {
 print(i)
    }
 }
*/


/*Question 6.
 
 Consider the code below. Loop through the professionals array and using a switch statement:
 
 Print out the professionals with lastName "Smith".
 Print out all the developers.
 Print out all the non-developers.
 Print out the professionals in their 20s.
 Print out the professionals in their 30s.
 */
/*
 let sarah = (firstName: "Sarah", lastName: "Palardo", job: "teacher", age: 32)
 let beth = (firstName: "Beth", lastName: "Newell", job: "developer", age: 29)
 let jana = (firstName: "Jana", lastName: "Smith", job: "developer", age: 33)
 let lauren = (firstName: "Lauren", lastName: "Olson", job: "doctor", age: 27)
 let charles = (firstName: "Charles", lastName: "Wong", job: "developer" , age: 24)
 let steve = (firstName: "Steve", lastName: "Smith", job: "writer", age: 28)
 let jamal = (firstName: "Jamal", lastName: "Smith", job: "developer", age: 25)
 let navindra = (firstName: "Navindra", lastName: "Chowdhurry", job: "actuary", age: 29)
 
 let professionals = [sarah, beth, jana, lauren, charles, steve, jamal, navindra]
 
 for professional in professionals {
 switch professional {
 case (_, "Smith", _, _):
 print(professional)
 case (_, _, "developer", _):
 print(professional)
 case (_, _, _, 20..<30):
 print(professional)
 case (_, _, _, 30..<40):
 print(professional)
 case _ where professional.job != "developer":
 print(professional)
 default:
 break
  }
 }
*/



//Question 7.

//Given the arrays below, use nested loops to print out every possible card in the deck.

/*let denominations = ["A", "2", "3", "4", "5", "6", "7", "8", "9", "10", "J", "Q", "K"]
let suits = ["♠️", "♣️", "♥️", "♦️"]

 for denomination in denominations {
 for suit in suits {
 print(denomination, suit, separator: "")
   }
 }
*/


//Question 8.

//Print out the lyrics to the song "99 Bottles of Beer"

//Hint 1: Use a for-loop and a switch statement
//Hint 2: Below is an example of reversing a range in Swift
//for i in (1...5).reverse() {
//    print(i)
//}


/* var i = 0
 for i in (0...99).reverse() {
 switch i {
 case 3...99:
 print("\(i) bottles of beer on the wall, \(i) bottles of beer.")
 print ("Take one down and pass it around, \(i-1) bottles of beer on the wall.")
 case 2:
 print("\(i) bottles of beer on the wall, \(i) bottles of beer.")
 print ("Take one down and pass it around, \(i-1) bottle of beer on the wall.")
 case 1:
 print("\(i) bottle of beer on the wall, \(i) bottle of beer.")
 print("Take one down and pass it around, no more bottles of beer on the wall.")
 default:
 print("No more bottles of beer on the wall, no more bottles of beer.")
 print("Go to the store and buy some more, 99 bottles of beer on the wall.")
   }
 }
*/



//Question 9.
//"FizzBuzz"

/*Create a loop that prints all integers from 0 to 100.
For all multiples of 3, print out "Fizz" instead of the number.
For all multiples of 5, print out "Buzz" instead of the number.
For all multiples of 3 and 5, print out "FizzBuzz" instead of the number
*/

/*var i = 0
 for i in 1...100 {
 switch i {
 case _ where i % 3 == 0 && i % 5 == 0:
 print("FizzBuzz")
 case _ where i % 3 == 0:
 print("Fizz")
 case _ where i % 5 == 0:
 print("Buzz")
 default:
 print(i)
  }
 }
*/



//Question 10.

//Write code that will print out the first 10 Fibonacci numbers:

//0, 1, 1, 2, 3, 5, 8, 13, 21, 34


/* var fibElement = 0
 var secondMostRecent = 0
 var mostRecent = 1
 print(secondMostRecent)
 print(mostRecent)
 
 for i in 0...7 {
 let newTerm = secondMostRecent + mostRecent
 print(newTerm)
 secondMostRecent = mostRecent
 mostRecent = newTerm
 }
*/





