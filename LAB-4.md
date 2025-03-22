			                                                         LAB  EXPERIMENT- 4

1. Create the /home/consultants directory: -> sudo mkdir /home/consultants
   ![image](https://github.com/user-attachments/assets/ed9b6c56-aab7-4ffc-b523-2c37d200f924)
   
2. Add write permission to the consultants group (symbolic method): -> sudo chmod g+w /home/consultants
   ![image](https://github.com/user-attachments/assets/2aa28903-b17e-49ff-bd5d-ecffae628cec)
   
3. Forbid others from accessing the /home/consultants directory (octal method): -> sudo chmod 750 /home/consultants
   ![image](https://github.com/user-attachments/assets/642c96d0-5a8b-446e-b3aa-41465baa0657)
   ![image](https://github.com/user-attachments/assets/5a382bf5-815d-42f5-a938-e4e838283dbe)

4. Change the default umask for the operator1 user: ->(a)Open the user’s .bashrc or .profile file: sudo nano /home/abhinav/.bashrc
   (b)Add the following line to set the umask: umask 0074

   ![image](https://github.com/user-attachments/assets/7f3a0433-b360-4511-a2b2-da5e85991bdc)
   ![image](https://github.com/user-attachments/assets/15017e59-9ee8-4cda-bd9a-e72c5c5d71ae)
   ![image](https://github.com/user-attachments/assets/94f08aa6-8c08-479c-b461-32750454cf42)

5. Confirm the umask: -> su - abhinav umask
   ![image](https://github.com/user-attachments/assets/a24da587-5b2d-4f44-8843-cd7f3766bef3)




