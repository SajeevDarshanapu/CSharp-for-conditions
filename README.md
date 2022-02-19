# CSharp-for-conditions

# for loop
--------When you know exactly how many times you want to loop through a block of code, use the for loop instead of a while loop:

# Syntax
for (statement 1; statement 2; statement 3) 
{
  // code block to be executed
}


# Example on for loop

for (int i = 0; i < 5; i++) 
{
  Console.WriteLine(i);                    //output: 1 2 3 4
}

# foreach loop

---------used exclusively to loop through elements in an array

# syntax
foreach (type variableName in arrayName) 
{
  // code block to be executed
}

# Example  on foreach loop

string[] cars = {"Volvo", "BMW", "Ford", "Mazda"};
foreach (string i in cars) 
{
  Console.WriteLine(i);
}



