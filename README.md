# 2c.SIMULATING ARP /RARP PROTOCOLS
## AIM
To write a python program for simulating ARP protocols using TCP.
## ALGORITHM:
## Client:
1. Start the program
2. Using socket connection is established between client and server.
3. Get the IP address to be converted into MAC address.
4. Send this IP address to server.
5. Server returns the MAC address to client.
## Server:
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are
stored.
4. Read the IP address which is send by the client.
5. Map the IP address with its MAC address and return the MAC address to client.
P
## PROGRAM - ARP
![Screenshot 2025-03-21 124724](https://github.com/user-attachments/assets/711f0590-294c-4b94-b9dc-fcfd2709ba46)

## OUPUT - ARP
![Screenshot 2025-03-21 124750](https://github.com/user-attachments/assets/0b5bb7a6-2285-423d-8bcd-156e08260922)

## PROGRAM - RARP
![Screenshot 2025-03-21 130606](https://github.com/user-attachments/assets/fd0d828a-ac63-4183-a903-360ffeba0657)

## OUPUT -RARP
![Screenshot 2025-03-21 135134](https://github.com/user-attachments/assets/0e880128-2311-4473-8f87-962078c55fb6)

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
