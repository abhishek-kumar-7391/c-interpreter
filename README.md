# C-interpreter
A rudimentry interpreter for C language.
It allows the user to enter code in C syntax strictly. If there are any
print statements then only output is shown, otherwise , only compilation
errors are reported (if any).
As of now there is no support for escape sequences.            
                                        
Currently provides/not provides/supports/not supports the following:                                    
1. the header files included by default are stdio.h, stdlib.h, string.h. Uptil now there is no way to include another header,
but it will be coming very soon.          
2. Readline feature for editing lines. You dont have to delete the entire line in case you want to change something at the beginnig or at any in place in the middle.            
3. Error reports per line. Lets say you enter something, thats not in accordance with C syntax or semantics, then error is reported immidiately.                       
4. Output is only displayed in case a "printf" or any other standard library routine is invoked.          
5. There is no support for writing functions, as of now its like everything is inside "main" method.        
6. It does not provide any tab completion features (look for a mathching a command on pressing tab), thus one has to write a complete command.


Additional Info:
It does not save a context, thus everything is temporary and is lost as soon as you close the interpreter.
