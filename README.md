// How to compile the project from the command line //

1.Open Windows PowerShell
   
2.Navigate to the project folder
Type this but replace with your file path of the project -> 

```Bash
cd "C:\Users\adsol\OneDrive\Desktop\Climate Change Quiz App\Climate Change QuizApp"
```

3.Navigate to the .src folder where all .java files are stored:
Type this -> 

```Bash
cd src
```

4️.Compile all Java source files, including the SQLite JDBC driver located in the libs folder:
Type this -> 

```Bash
javac -cp ".;../libs/*" *.java
```

// How to run the program //

1.After compiling, stay in the src folder
   
2.Run the application using:
Type this -> 

```Bash
java -cp ".;../libs/*" QuizApp
```



