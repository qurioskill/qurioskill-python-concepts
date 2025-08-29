# **Python Cheat Sheet**

## **Who is this for?**
This sheet is for budding Python programmers to look up different concepts.

## **How to use this sheet?**
Each concept has a simple-to-understand definition, what they are used for, and links for when you need to know how to use them.

---

## **Concepts**

### **Data Types and Variables**
- Data types describe the kind of information a variable/program can use.
- Depending on the type of data, different operations can be performed on it.
- Variables point to data. They give names to the data.

#### **Why?**  
The real world has a lot of different kinds of simple and complex data. 
Python programming language tries to provide ways of representing and manipulating that data.

#### **Resources**  
- [Simple Data Types](https://realpython.com/python-data-types/)  
- [Complex Data Types](https://realpython.com/python-data-structures/)  
- [Official Tutorial](https://docs.python.org/3/tutorial/introduction.html)  
- [Official Documentation](https://docs.python.org/3/library/datatypes.html)

---

### **Flow of Control**
- Flow of control is about the order in which instructions in a program are executed.
- By default, Python runs code line by line, top to bottom.
- Following are key elements of Python flow of control:
      - **Conditionals (if)** – run code only if something is true.
      - **Loops (for, while)** – repeat code multiple times.  
      - **while** – repeating instructions until a condition is true.  
      - **for** – going over a list of data repeatedly.
      - **Break / Continue** – exit or skip part of a loop.
      - **Function Calls** – jump to reusable code blocks. (Covered separately as well)

#### **Why?**  
Programs have multiple instructions and the sequence they are executed in ensures that the program does its job.  
The real world is full of situations where decisions and repetition matter. For example:

- If it’s raining → take an umbrella.  
- Check each student in a class and print their grade.

#### **Resources**  
- [Conditionals](https://realpython.com/python-conditional-statements/)  
- [Conditionals (Official Tutorial)](https://docs.python.org/3/tutorial/controlflow.html)  
- [While loops](https://realpython.com/python-while-loop/)  
- [While loops (Official Tutorial)](https://docs.python.org/3/tutorial/controlflow.html)  
- [Break/Continue (Official Tutorial)](https://docs.python.org/3/tutorial/controlflow.html)  
- [Functions (Official Tutorial)](https://docs.python.org/3/tutorial/controlflow.html#defining-functions)

---

### **Functions**
- A function is a reusable block of code that performs a specific task.
- Instead of repeating the same code many times, you can define it once and call it whenever needed.

#### **Why?**  
- To have pieces of code that can be used multiple times.  
- Forms the foundation of open source, where people can write functions for other developers to use.  
- This allows reusing already written code while hiding the complexity of complicated functionalities like making graphics, analysing data etc.

#### **Resources:**  
- [Functions](https://realpython.com/defining-your-own-python-function/)  
- [Functions (Official Tutorial)](https://docs.python.org/3/tutorial/controlflow.html#defining-functions)  
- [All Python Built-in Functions](https://docs.python.org/3/library/functions.html)

---

### **Methods**
- A method is a function that belongs to a data type.
- It looks like a function call but is always tied to a particular data type.

#### **Why?**  
Data Types in Python often need their own tools.

For example:

- Strings often need case conversion (`.upper()`, `.lower()`)
- Lists often need adding or removing items (`.append()`, `.remove()`)

#### **Resources**  
- [String Methods](https://realpython.com/python-strings/#exploring-str-class-methods)  
- [Numeric Methods](https://realpython.com/python-numbers/)  
- [List Methods](https://realpython.com/python-list/)

---

### **Modules**
- A module is a file that contains Python code (functions, variables, etc.) that you can use in other programs.
- Modules help you organize code and reuse functionality without rewriting it.

#### **Why?**  
In the real world, knowledge is grouped into books and tools in a toolbox. Modules are like those toolboxes — they let you keep related code together and share it across projects.  
They also help build an open source network of reusable code.

#### **Resources**  
- [Modules](https://realpython.com/python-modules-packages/)  
- [Modules (Official Documentation)](https://docs.python.org/3/tutorial/modules.html)

---

### **Packages**
- A package is a collection of modules, organized together in a folder.
- Packages make it easier to structure and share large amounts of code across many modules.

#### **Why?**  
In the real world, we often group related tools into kits. A module is like a single tool. A package is like a complete toolkit with many related tools inside.

#### **Resources**  
- [Packages (Official Documentation)](https://packaging.python.org/en/latest/)  
- [Packages](https://realpython.com/python-modules-packages/)

---

## **Is this all?**
No, there are a lot more concepts and tools that you can use. But all of them follow the above basic patterns.

---

## **Breaking Down Programming Tasks**

Programming can feel overwhelming at first. Breaking a problem into clear, simple steps makes it much easier to solve.

### **Why?**  
Programming is like solving a puzzle or cooking a recipe.  

- Gather the ingredients (inputs).  
- Know what dish you want (output).  
- Follow a step-by-step plan (logic).  
- Taste and adjust (test and improve).

### **Key Steps**
1. **Understand the Problem**  
      - What does the program need to do?  
      - Example: “Ask the user for their age and tell them if they can vote.”

2. **Identify the Inputs**  
      - What information will the program need?  
      - Example: user’s age.

3. **Identify the Output**  
      - What should the program give back?  
      - Example: message “You can vote” or “You cannot vote.”

4. **Plan the Logic**  
      - Think about how the input will turn into the output.  
      - Identify packages and modules whose code you can reuse.  
      - This often involves operators, conditionals, or loops.  
      - Example: If age >= 18 → say yes, otherwise → say no.

5. **Write the Code (Start Small)**  
      - Begin with the simplest version.  
      - Test it. Add features step by step.

6. **Test and Improve**  
      - Try different inputs.  
      - Fix mistakes.  
      - Clean up your code so it’s easier to read.
