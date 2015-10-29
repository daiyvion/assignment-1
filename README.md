# assignment-1
using System; 
2 
 
3 namespace Program1 
4 { 
5     class Program 
6     { 
7         static void Main(string[] args) 
8         { 
9             Console.WriteLine("What is your first name?"); 
10             string firstName = Console.ReadLine(); 
11             Console.WriteLine("What is your middle initial?"); 
12             string middleInitial = Console.ReadLine(); 
13             Console.WriteLine("What is your last name?"); 
14             string lastName = Console.ReadLine(); 
15 
 
16             string fullName = firstName + " " + middleInitial + ". " + lastName; 
17 
 
18             Console.WriteLine("What is your height in feet and inches?"); 
19             Console.WriteLine("Feet:"); 
20             int heightFeet = int.Parse(Console.ReadLine()); 
21             Console.WriteLine("Inches:"); 
22             double heightInches = double.Parse(Console.ReadLine()); 
23 
 
24             double totalHeightCM = ((heightFeet * 12) + heightInches) * 2.54; 
25 
 
26             Console.WriteLine("What is your age?"); 
27             int age = int.Parse(Console.ReadLine()); 
28             Console.WriteLine("Are you a citizen?"); 
29             bool isCitizen = bool.Parse(Console.ReadLine()); 
30 
 
31             bool canVote = age >= 18 && isCitizen; 
32 
 
33             Console.WriteLine("Height:"); 
34             Console.WriteLine(totalHeightCM); 
35             Console.WriteLine("Name:"); 
36 
 
37             Console.WriteLine(fullName); 
38             Console.WriteLine("Can you vote?"); 
39             Console.WriteLine(canVote); 
40         } 
41     } 
42 } 
 





Status
 API
 Training
 Shop
 Blog
 About
 Pricing
 
