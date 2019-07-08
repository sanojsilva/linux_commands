1. ##### Shebang Line
```bash
#!/bin/bash 
``` 
***
2. ##### Shebang Line with debugging
```bash
#!/bin/bash -x 
``` 
***
3. ##### To print something
```bash
echo "hello world" 
```
***
4. ##### Create variables
```bash
NAME="manju"
NUMBER=5
```
***
5. ##### To print a variable with some text
```bash
echo "my name is $NAME"
echo "my name is ${NAME}"
```
***
6. ##### Prints the number of command line args
```bash
echo $#
```
***
7. ##### Prints the name of the script
```bash
echo $0
```
***
8. ##### Defining a function
```bash
funcName() {

}
```
***
9. ##### Calling a function
```bash
funcName
```
***
10. ##### Calling a function with arguments
```bash
funcName arg1 arg2
```
***
11. ##### While loop
```bash
while [ condition ]
do 
  command1
  command2
done
```
***
12. ##### To create an Infinite loop using while loops
```bash
while :
while [ 1 ]
while true
```
***
13. ##### Until loop
```bash
until [ condition ]
do
  command1
  command2
  command3
done
```
***
14. ##### Iterate over a list using a For Loop
```bash
for VAR in 1 2 3 4 5
do
  echo $VAR
done
```
***
15. ##### Iterate through 1 to 25 using a For Loop
```bash
for i in {1..25}
do
  echo $i
done
```
***
