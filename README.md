# 2a_Stop_and_Wait_Protocol
## AIM 
To write a python program to perform stop and wait protocol
## ALGORITHM
1. Start the program.
2. Get the frame size from the user
3. To create the frame based on the user request.
4. To send frames to server from the client side.
5. If your frames reach the server it will send ACK signal to client
6. Stop the Program
## PROGRAM
```python
n = int(input("Enter number of frames: "))

for i in range(1, n + 1):
    print("Sending Frame", i)
    print("Frame", i, "received")
    print("ACK", i, "received")

print("All frames transmitted successfully")
```
## OUTPUT

<img width="387" height="402" alt="image" src="https://github.com/user-attachments/assets/38a254b2-92df-48c5-89ab-7bd8fa2d67b0" />

## RESULT
Thus, python program to perform stop and wait protocol was successfully executed.
