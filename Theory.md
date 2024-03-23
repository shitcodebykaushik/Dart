# Dart 
 Dart file name is the runnning command for the dart file .
The dart is the a client-optimized programming language for apps on multiple platforms.
`Main`is the one of the function from where the running of aplications begins.
We use // or /**/ for the commenting of the content .
To create a multi-line string, use a triple quote with either single or double quotation marks:

# Data types 
 ## Numbers 
  In dart we have two falavour.
 - In this we have two different types of data types 
   - int and double 
   ```Dart
   void main (){
   int a = 75;
   double n = 453;
   print(a);
   print (n);
   }
     ```

 # String
  A Dart string (String object) holds a sequence of UTF-16 code units
 
Booleans 
# Records 
Records are an anonymous, immutable, aggregate type. Like other collection types, they let you bundle multiple objects into a single object. Unlike other collection types, records are fixed-sized, heterogeneous, and typed.

Records are real values; you can store them in variables, nest them, pass them to and from functions, and store them in data structures such as lists, maps, and sets.
``` Dart 
 void main (){
    int id = ('raj','kaushik ');
    print('id');
 }
```


lists 

sets 
maps 
runes 
symbols 

# Variable 
Variables store references. In this object type can be anything which you want.
# Null Safety is one of the core feature of the dart . 
It simply states that a varible must be intilized before running the code .
 In this we get two operator for the null varibale.
 ? ans ! for running the null value .
 ``` Dart
 void main (){
  int?a;
  int y = a!;
  print(a);
}
 ```

 - This is the line for the null safety.

```Dart
   void main (){
 String name ;
 print(name);
 
}
```
Dart doesn't set initial values to non-nullable types. It forces you to set an initial value. Dart doesn't allow you to observe an uninitialized variable. This prevents you from accessing properties or calling methods where the receiver's type can be null but null doesn't support the method or property used.

# Late variables 
- Declaring a non-nullable variable that's initialized after its declaration.
 - Lazily initializing a variable.
``` Dart
 late String desi;
 void main (){
 
 desi = 'KAushil';
 print(desi);
desi = 'KAushik';
 print(desi);
}
```  
# Final and const 
 Use these keywords to set the variable as a constant variable .
 Instance varibale can be final but canot be const .
 Const is the compile time constant .
 ```Dart
 void main (){
  const name = 'k';
 final name1 = 'k';
 print(name);
 print(name1);
}

 ```
 # Operator 
 This will be updated later one 
 # Metadata 
 It is use to give the additional data to the  code .
 It annoations begins with the character '@'.
 We can define our own metadata.
