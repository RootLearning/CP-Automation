# Competitive Programming Automation Project



[![](ss5.png)]



## About the Project:
 This project is to make the Competitive Programming Contests easier for participants by providing a context-specific boilerplate code for problems.

## Objective:

Our main goal is to reduce the time taken by the participants to do the repetitive process and help the participants to work more effectively on the logic for the code.


### What's going to happen inside our tool???

## **STEP 1**

#### Getting input and output from the contest:

 * The sample input and sample output from the contest should be copied and stored in any readable file. It can be a text file(.txt), markdown file (.md)

 * The text files should be stored in the following path:

   **_C:\\myfolder\\SampleInput.txt_**

   **_C:\\myfolder\\ExpectedOutput.txt_**

   [![](ss1.png)]

* In this tool, we will give support to various types of input and outputs.

*  Various input including integers, strings, arrays, lists, char, and so on.
  



## **STEP 2**:

### Scripting:

* The next step is to write a  **PowerShell Script** to open a new project with all the required Applications, Libraries, and test files.

* The Project  is stored in the path specified.

  **User\\Desktop\\automated**

* The User can run the script in the **PowerShell Terminal**.

* During the runtime, the name can be given to the newly created projects.

### Why Scpriting required here?

While participating in a contest, the user has time constraints. Within a given time, it is a tedious job to open a project folders and adding all your required folders in it.

_This job can be made easier by scripting!!!!_

**Powershell scripting** is the best way to automate all our process. It is 100% automated, consistent, and faster.


We can help the user by automating the solution,project,class folders creation by Powershell scripting.

[![](ss2.png)]

It will reduce Time consumption and allow users to concentrate on the logic for the problems more effectively.





## **STEP 3**

### Boiler code :

* Open the created new project.

* The Sample Input text file should be given as a input to the code by using StreamReader.

* Now, the users can write their logic code inside the boiler code.

* After the logic code, the output from the logic code should be  redirected to the new text file by using StreamWriter.

* The New text file located in the following path.

   **C:\\MySample\\OurOutput.txt.**

   [![](ss4.png)]

### Why streaming input and output required?

In this tool, we used **StreamReader** and **StreamWriter** to stream the input and output from a text file.

By using this, the user can stream the exact input and output given in the contest.

No need to give the input and output by themselves.

Time consumption and the accuracy are optimized here!


## **STEP 4**

### Compare and show the mismatch:

* If both outputs are the same, the code is ready to upload in the contest.

* else,the users have to recheck or modify the code according to the requirements.


* Our tool should clearly show the mismatch between the expected and logic code text  output file,so that it will be effective for the user to find their mistakes.

### Why automated comparison?

Without using our tool, the users manually check the logic output and the expected output and find the mismatch.

But in our tool, we can automate the comparison and show where the mismatch occurs.

### Advantages:

* By this tool,user can work in a effective manner.

* Time consumption is highly optimized by automation!!


























