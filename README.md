# PieL
A programming language for Spanish speakers

### Java
For this project you will need to have the JDK installed and in your path. You can find the JDK [here](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html )

To verify if java is installed and in your system path open a terminal and type
```bash
$ java -version
```
You should receive the version in the next line.


### JavaCC
You will also need to install JavaCC. To download  visit the [JavaCC Homepage](https://javacc.java.net/ "JavaCC Home").

### Building PieL

1. Open Terminal on the folder where the .jj file is along with the javacc.jar file is.
2. Run these commands
```bash
java -cp "path to javacc.jar" javacc "path to PieL.jj"
```
```bash
javac *.java
```


### Instructions to run the language:
1. Run a terminal inside the folder where the parser,lexer and intermidiate code reside.
```bash
java PieL
```
3. This will allow you to start writing code in the PieL Language.

Example code to write (the words inside the quotations are to be replaced for information of your choice ex. ID would be the name of a variable you have created):

a) Crea un "TYPE" llamado "ID" con valor ("STRING" OR "NUMBER" OR "ID").

b) Crea un "STRUCT" de "TYPE" llamado "ID" y valores [ "MULTITERM" ].

c) Si ("STRING" OR "NUMBER" OR "ID") es igual a ("STRING" OR "NUMBER" OR "ID") {"insert instructions here"}.

d) Imprime "ID".

e) Imprime arreglo o lista "ID".
