# Android App Making Process
***

### 1. Plan your app
In order to make the app making part a bit easier, 
plan out your app _before_ you start coding/designing.
Planning will make things flow easier and faster, as well as eliminate 
future headaches.

### 2. Get your tools
[Android Studio](https://developer.android.com/studio/index.html?gclid=Cj0KEQiA2uDEBRDxurOO77Cp-7kBEiQAOUgKV04Cp7VZzXEpj0LuC62iQ3dySuBOrDt2VJg0K7bKHd4aAoNP8P8HAQ) is the main tool for creating Android apps.
It is based off of the IntelliJ Java IDE. It also comes with a preinstalled Android Emulator;
therefore, you do _not_ need a physical Android phone to run your apps. As well as Android Studio, you will need
the Android SDK (Software Development Kit). The SDK usually comes with Android Studio, but there is other SDKs and APIs, 
like the Google Maps API, that you can utilize in your app.

### 3. Learn the language
Android apps are made in Java (and sometimes C++ and C#). Java is a _compiled_ language
(Python was an _interpreted_ language). Java is also more verbose, or "Strongly typed"
language than Java. For example, a "Hello world" program in python would be like this:
```Python
  print("Hello world")
```

Where as a "Hello world" program in Java would be like so:

```java
public class HelloWorldExample{
  public static void main(String[] args){
    System.out.println("Hello world");
  }
}
```

As you can see, Java has more words and lines to do the same thing, but this
brings a certain amount of customizability to Java that Python doesn't have. 
To start jearning Java, go to [codecademy.com](https://www.codecademy.com/learn) 
and go to the 'Java' section. I have also made a bit of a Java cheat sheet you can use for syntax referenct [here](https://github.com/thecarterb/Programming-Cheat-Sheets/tree/master/Java). 
See reference 1 for more details.
Reference 3 has a list of Java keywords that will be useful to you during development.

### 4. Learn the software

Android Studio comes with a build in designer for designing the UI (User interface)
of your app. If you want your app to look good, practice with the designer and figure out its quirks.
Again, doing this will take out some future headaches in the development process. See reference 2 for more details.

### 5. Read the documentation

This one is apparent with any new language/software. The Java documentation is available [here](http://docs.oracle.com/javase/8/docs/api/index.html), and the Android documentation is available [here](https://developer.android.com/reference/packages.html). The [Android Developer site](https://developer.android.com/guide/index.html) has some useful tutorials on how to do certain tasks like animation, data storage, and others. 

***
# References

### 1. Code vs. Output
Here is the pre-generated Java code from android studio when making a _Basic Activity_ application:
![alt text](http://i.imgur.com/7ScM22G.png)

Here is what it looks like on a phone (Nexus 6P):

![alt text](http://i.imgur.com/eeT7X9j.png)

This is ___NOT___ meant to scare you, try and analyze some lines to see if you can figure out what they do. (Based on pripr programming knowledge)

### 2. The UI Designer

This is a shot of the built in UI designer with a few _elements_ drag and dropped on to the phone:

![alt text](http://i.imgur.com/VRG6uI5.png)

This all gets translated into a language called _XML_, which is like a modular version of HTML.

Android has a set of design standards called _Material Design_. https://material.io/ can tell you all about material design and how it works and looks.

### 3. Java keywords and syntax

Below are some of Java's most common keywords:

| Word          | Meaning       |
| ------------- |:-------------:|
| `abstract`      | Used to implement _abstraction_. A method which doesn’t have method definition must be declared as abstract and the class containing it must be declared as abstract |
| `boolean`      | A `true` or `false` value      |
| `break`        | Used to end loop execution. |
| `char` | Defines a character      |
| `class` | A type that defines the implementation of a particular kind of object|
| `continue`| Used to resume program execution at the end of the current loop body|
| `double`  | Used to declare a variable that can hold a 64-bit floating point number|
| `extends` | This is how Java implements [_inheritance_] (https://www.tutorialspoint.com/java/java_inheritance.htm)|
| `import`  | Used at the beginning of a source file to specify classes or entire Java packages to be referred to later without including their package names in the reference|
| `int` |  Used to declare a variable that can hold a 32-bit numerical value |
| `new` | Used to create an instance of a class or array object|
| `public` | Used in the declaration of a class, method, or field; public classes, methods, and fields can be accessed by the members of any class |
| `static` | Used to declare a field, method, or inner class as a class field|
| `null` | `None` in Python, used to express the absence of a value|

Just to name a few 😄.

The syntax for declaring a function is like so:

```java
public/private/abstract static/(OR NOTHING) return type(void if no return type) functionNameInCamelCase(parameter1, parameter2){
  // This is a single line comment
  /* 
    This is a 
    multiline
    comment
  */
}
```


***
#### Other
[Here](https://github.com/JStumpp/awesome-android) is a curated list of cool APIs and other things that you can utilize in your app.
