# Network Fundamentals
Use `netstat -ano` to list all listening ports. Identify one service listening on a local port<br /> Firstly, I show all port listeners on the system with the netstat -ano command
![alt text](https://github.com/saabir00/networklab2sabir/blob/main/Screenshot%202025-05-13%20220159.png)
![alt text](https://github.com/saabir00/networklab2sabir/blob/main/Screenshot%202025-05-13%20220236.png)
![alt text](https://github.com/saabir00/networklab2sabir/blob/main/Screenshot%202025-05-13%20220248.png) <br /> Then, I select a line in the "LISTENING" state:
![alt text](https://github.com/saabir00/networklab2sabir/blob/main/Screenshot%202025-05-13%20220319.png) <br /> I selected the line 0.0.0.0:5040 in the 4th line, its PID is 8612. Then I find out which process this PID belongs to. <br /> Results: <br /> Port: 5040 <br /> PID: 8612 <br /> Protocol: TCP <br /> Service: svchost.exe
