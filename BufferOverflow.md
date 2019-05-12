What's a buffer?<br/>
-Memory locations in a program, used for storing data that is being used by the program. 

What is buffer overflow?<br/>
-A process in which a program writes data outside of its temp storage, into other areas of 
program memory not designated to store secure data.

What happens when a buffer overflow occurs?<br/>
-Program may crash / slow down<br/>
-May return bad data<br/>
-Runs other programs or commands (command execution)<br/>

![bufferoverflo](https://www.hackingtutorials.org/wp-content/uploads/2016/12/buffer-overflow-example.jpg)

### BufferOverflow Prevention
-Store user input in a small buffer, large enough for the string required: <br/>
var userInput = String[10];<br/>
-Languages like Java, Python and .NET are immune to buffer overflows due to not allowing
direct access to memory / object typing. 


