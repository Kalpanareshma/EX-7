# EX-7 IMPLEMENTATION OF TRACEROUTE COMMAND

## DATE : 20-04-2023

## AIM :
To write the python program for simulating Traceroute command

## ALGORITHM :
### STEP 1: Start the program.
### STEP 2: Get the frame size from the user.
### STEP 3: To create the frame based on the user request.
### STEP 4: To send frames to server from the client side.
### STEP 5: If your frames reach the server, it will send ACK signal to client otherwise it will sendNACK signal to client.
### STEP 6: Stop the program


## PROGRAM :
### Developed : Kalpana S
### Reg no : 212222040069
```
from scapy.all import*
target = ["www.google.com"]
result, unans = traceroute(target,maxttl=32)
print(result,unans)
```


## OUTPUT :
![EX-07](https://github.com/Kalpanareshma/EX-7/assets/122040453/d70d2e1c-f626-4f71-be44-05d3af68f1b2)



## RESULT :
Thus, the python program for simulating Traceroute command was successfully executed.
