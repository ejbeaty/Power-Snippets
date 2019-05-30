# Power-Snippets
Handy Visual Studio Code Snippets

## Getting Started
1. Clone this repository
2. In Visual Studio go to *Tools* --> *Code Snippets Manager* --> *Import*
3. Navigate to the snippet you want to install and select it (or can select multiple)
4. Start using your new snippet by typing the shortcut (see below) and hitting tab twice.

## Argument Snippets
### argNullCheck.snippet
**Description:** Check an argument for a null value and throw an exception if neccessary  
**Shortcut:** arg  
**Throws:** ArgumentNullException  

### stringNullCheck.snippet
**Description:** Check if a string argument is null or empty and throw an exception if it is  
**Shortcut:** sarg  
**Throws:** ArgumentNullException  

### guidNullCheck.snippet
**Description:** Check if a guid argument is Guid.Empty and throw an exception if it is  
**Shortcut:** garg  
**Throws:** ArgumentNullException  

### setOrThrowArgNull.snippet
**Description:** Check if an argument is null and throw an exception if it is otherwise set the value of a property  
**Shortcut:** set  
**Throws:** ArgumentNullException  

## Constructor Snippets
### 1arg.snippet
**Description:** Create a method constructor with one argument  
**Shortcut:** ctor1   

### 2arg.snippet
**Description:** Create a method constructor with two arguments  
**Shortcut:** ctor2 

### 3arg.snippet
**Description:** Create a method constructor with three arguments  
**Shortcut:** ctor3

### 4arg.snippet
**Description:** Create a method constructor with four arguments  
**Shortcut:** ctor4

### base1.snippet
**Description:** Create a method constructor with 1 argument that is then passed to the base class
**Shortcut:** base