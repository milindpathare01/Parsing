# Parsing

# Parsing Bank Statemnt : Problem Statment 
Parsing the bank statement pdf included in the repository

Under src/code.java we extract all the "Text" from the uploaded PDF files.

You need to indentify and Assign the all imporatant field from the text and create object of AccountDetails and populate it. Than using object.ToString() metod print all the relavent information on console.

You can submit your solution by creating a fork from this repository.

public class AccountDetails
{

    public string Nickname {get; set;}
  
    public string AccountNumber {get; set;}
  
    ..... other property as required
  
    //This is just a sample example, u will need sothing more sophisticated method
    
    public string override ToString(){
  
      return Nickname +" "+ AccountNumber+ " ";

    }
  
}

# How to run the Project: (For Eclipse IDE)

1.Clone the project into to your system from this "milind" branch.

2.Downlaod the eclipse version "2021-09" or latest version.

3.Import the project On the "Eclipse IDE JAVA"

4.(If the JDK is not set up into your system then first set the JDK.) to set path of JDK use "jdk latest version".

5.Then Run the "code.java" file.

# How to run project : (For Visual Studio Code) 

1. Clone the project folder from this "milind" branch.
2. Open Project folder with Visual studio code.
3. Run the main file name as "code.java".


@Milind Task
readdata should use filepath as argument
Task 1:
Test cases for getBankStatementDetail 
input: given the input path="himanshi dec 21.pdf" from readdata function
output(BankStatementDetail): should not be null, property Name should not be empty, property Name should not be null, property Name should be "himanshi" (assert.equal("himanshi,BSD.Name), assert.isnotnull(BSD))
Create a test which verify if the Name is not null, Hitalent.Test.Api


