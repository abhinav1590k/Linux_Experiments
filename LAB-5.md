1. ps Command -> (a)Display all running processes: ps aux
   ![image](https://github.com/user-attachments/assets/2cbc1f53-3403-41ca-ae1a-a86df53825d8)
   
   (b)Show processes for the current terminal session: ps
   ![image](https://github.com/user-attachments/assets/289034b8-8abe-411f-9d48-e514293f48bb)

   (c)Display a process tree: ps -e --forest
   ![image](https://github.com/user-attachments/assets/2c55c23d-6a6a-4a72-9b51-879de05091d9)

   (d)Filter by process name: ps -C firefox
   ![image](https://github.com/user-attachments/assets/f22d6f2b-19d6-420c-9431-6fb57f64becf)

   (f)Show detailed information of a specific process: ps -p 1234 -o pid,ppid,cmd,%mem,%cpu
   ![image](https://github.com/user-attachments/assets/57b998b9-16c1-4439-aed4-a6f45bc55620)
   
2. kill Command -> (a)Find the PID: ps aux | grep firefox
   ![image](https://github.com/user-attachments/assets/5d56ecba-708b-432d-8314-adeebb9d5185)
   
   (b)Kill a process by PID: kill 1234
   (c)Force kill a process: kill -9 1234
   (d)Kill by process name: killall firefox

4. top Command -> top Sort by memory usage: Press M Sort by CPU usage: Press P Kill a process: Press k → Enter the PID Exit top: Press q
   ![image](https://github.com/user-attachments/assets/97d301bb-dd0a-4d76-b37d-0f95f09448ca)

5. apt-get Command -> (a)Update package list: sudo apt-get update
   ![image](https://github.com/user-attachments/assets/0b9ba027-2a9e-4cc3-a428-ed3278fe4a46)
   
   (b)Upgrade installed packages: sudo apt-get upgrade
   ![image](https://github.com/user-attachments/assets/c55b8b25-0222-4344-8492-3b6f03a43e5c)

   (c)Install a package: sudo apt-get install vim
   ![image](https://github.com/user-attachments/assets/99aa9ee1-8597-4869-b5b9-36112679d6a7)

   (d)Remove a package: sudo apt-get remove vim
   ![image](https://github.com/user-attachments/assets/1f278bd0-9495-4d26-8075-1f5917388df0)

   (e)Remove package along with configuration files: sudo apt-get purge vim
   ![image](https://github.com/user-attachments/assets/f35af546-011e-46b8-b1a3-c9a71dca54d7)

   (f)Clean up unused packages: sudo apt-get autoremove
   ![image](https://github.com/user-attachments/assets/3c240b1a-48ee-44a5-a42f-4e4beaab2323)

   (g)Clean package cache: sudo apt-get clean
   ![image](https://github.com/user-attachments/assets/6477fde2-2287-40a0-95e2-e17311c0719b)



   






