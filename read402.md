## Read: 02 - Arrays, Loops, Imports
Packages and Import


### The first statement, other than comments, in a Java source file, must be the package declaration.
> Following the optional package declaration, you can have import statements, which allow you to specify classes from other packages that can be referenced without qualifying them with their package.
It is like a group which it used to group related classes and we use the Packages to avoid name conflicts, and to write a better maintainable code.
The first statement must be the package declaration.
Types of Packages
Built-in


User-defined
Common imports
import java.awt.\*; Common GUI elements.
import java.awt.event.\*; The most common GUI event listeners.
import javax.swing.\*; More common GUI elements. Note "javax".
import java.util.\*; Data structures (Collections), time, Scanner, etc classes.
import java.io.\*; Input-output classes.
import java.text.\*; Some formatting classes.
import java.util.regex.\*; Regular expression classes.
Loop Statements
Java provides different types of loops to fit any programming need. Each loop has its own purpose and a suitable use case to serve.
The while Statements
> while (true){
    // your code goes here
}
> The do-while Statements
do {
    statement(s)
> } while (expression);
> The for Statement
> for(int i=1; i<11; i++){
    System.out.println("Count is: " + i);
