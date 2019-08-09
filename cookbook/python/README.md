# Hands-on with Python

[Installing Python3 on Ubuntu 18.04]()<br>
[Writing Your first Hello World Program]()<br>
[Python Indentations]()<br>





## Installing Python3 on Ubuntu 18.04

```
apt install python3
```

Quick Way:

```
docker pull python:3.6
```


## Writing Hello World Example in Python

Create a file called "helloworld.py" and add the below contents:

```
root@ubuntu1804-1:~/cookbook# cat helloworld.py
#!/usr/bin/python3
print ("Hello,World")
```

Save the file and run the python script:

```
root@ubuntu1804-1:~/cookbook# python3 helloworld.py
Hello,World
```

## Python Indentations

Where in other programming languages the indentation in code is for readability only, in Python the indentation is very important.
Python uses indentation to indicate a block of code.

```
root@ubuntu1804-1:~/cookbook# cat tryindentation.py
if 5 > 2:
  print ("Five is greater than two!")
```

```
root@ubuntu1804-1:~/cookbook# python3 tryindentation.py
Five is greater than two!
```

Que: What will be output of the below code:

```
if 5 > 2:
print("Five is greater than two!")
```

It will generate error. Think why?
