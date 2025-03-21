1. Create the operator1 user: -> sudo useradd -m oper1
   ![image](https://github.com/user-attachments/assets/b7f076b4-3ad5-4e17-9a46-23ec6ce19fa1)

2. Confirm that operator1 exists: -> cat /etc/passwd | grep oper1
   ![image](https://github.com/user-attachments/assets/9d7c81fd-3048-4c77-ae8a-f7252b0c2212)

3. Set the password for operator1: -> sudo passwd oper1
   ![image](https://github.com/user-attachments/assets/99b14cc3-e2cc-49f6-a5c9-687fcffb06d7)

4. Create operator2 and operator3 users: -> sudo useradd -m operator2 sudo passwd operator2 sudo useradd -m oper3 sudo passwd oper3
   ![image](https://github.com/user-attachments/assets/f4863c80-c6a8-4c07-a688-ec3532f8b8c5)

5. Update the comment for operator1 using usermod -c: -> sudo usermod -c "System Operator 1" oper1
   ![image](https://github.com/user-attachments/assets/6ebb019e-22f4-4178-8f6f-6e2e1d39f55f)

6. Remove the operator3 user: -> (a)To delete operator3 without removing the home directory: sudo userdel oper3
   ![image](https://github.com/user-attachments/assets/f699e224-6b07-4a44-b629-fb8cac98bfae)

   (b)To delete operator3 and its home directory: sudo userdel -r oper3
   ![image](https://github.com/user-attachments/assets/50e00097-d3e0-432c-b63e-12283ad1f8e5)



