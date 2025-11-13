# Experiment 4 – Create Rectangle Structure with Length and Breadth and Add Method to Calculate Area  

<H3>ENTER YOUR NAME: Santhosh G</H3>  
<H3>ENTER YOUR REGISTER NO: 212223240152</H3>  
<H3>EX.NO.4</H3>  
<H3>DATE: 16-10-2025</H3>  


## AIM:  
To create a structure with length and breadth values and calculate the area of a rectangle.  

## EQUIPMENTS REQUIRED:  
- Hardware – PCs  
- Software – Visual Studio Code (Version 1.104.0)  
- Rust Installation  

## RELATED THEORETICAL CONCEPT:  

*Structures in Rust:*  
A structure (struct) in Rust is a custom data type that lets you group related values together. Each field in a struct can have a different type.  

*Methods in Rust:*  
Methods are functions defined within the context of a struct, enum, or trait object. They are used to implement behavior associated with that data type.  

*Need for Structs with Methods:*  
- Encapsulates related data into one unit.  
- Improves code reusability and readability.  
- Allows defining behavior (like area calculation) directly associated with the struct.  

## ALGORITHM:  
STEP 1: Create a structure **Rectangle** with numeric fields `length` and `breadth`. <BR>  
STEP 2: Implement an `area` method for the `Rectangle` structure. <BR>  
STEP 3: In the `main` function, define a structure variable and assign values for length and breadth. <BR>  
STEP 4: Call the `area` method and print the calculated value of area of the rectangle. <BR>  

## PROGRAM:  
```

struct Rectangle {
    length: f64,
    breadth: f64,
}

impl Rectangle {
    fn area(&self) -> f64 {
        self.length * self.breadth
    }
}

fn main() {
    let r = Rectangle { length: 10.0, breadth: 5.0 };
    println!("Area = {}", r.area());
}

```
## OUTPUT :

<img width="1108" height="244" alt="image" src="https://github.com/user-attachments/assets/e8ef2f1e-07ff-41ce-b78c-d239349e15a2" />

## RESULT :

Thus we have successfully implemented a structure called rectangle with length and breath fields and added a method to calculate area of rectangle.
