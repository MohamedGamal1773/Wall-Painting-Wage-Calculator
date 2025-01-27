# Wall-Painting-Wage-Calculator
This Python script calculates the total wage for laborers painting a wall. It computes the total area of the wall and the payment required based on the price per square meter.
 --- ## How It Works
1. The user inputs: - The *length* of the wall. - The *width* of the wall. - The *price* per square meter for painting.
2. The program calculates: - The total area of the wall. - The total payment for the labor.
3. --- ## Example ### Input: ```plaintext Please Type Length: 5
4. Please Type Width: 3
5. How much For 1 Meter? 10 
Output:
The Total Area is: 15.0
Give The guy: $150.0 
Code:
str_length = input("Please Type Length: \n")
str_Width = input("Please Type Width: \n")
str_Price = input("How much For 1 Meter? \n")
length = float(str_length)
Width = float(str_Width)
Price = float(str_Price)
Total_area = length * Width
print("The Total Area is: " + str(Total_area)) 
print("Give The guy: $" + str(Total_area * Price)) 
