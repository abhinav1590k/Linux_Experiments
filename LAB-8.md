1. Shell Script to Print System Information -> (a)Create a file named system_info.sh:
   ![image](https://github.com/user-attachments/assets/af50ff54-5af1-4e56-824e-cdcc660733a7)

   (b)Make the script executable: chmod +x system_info.sh

   (c)Run the script: ./system_info.sh
   ![image](https://github.com/user-attachments/assets/c1dde80b-9cca-459f-ac86-e2fee998754a)

2. Shell Script to Perform Basic Mathematical Calculation -> (a)Create a file named calc.sh:
   ![image](https://github.com/user-attachments/assets/73ec9453-5473-4815-9e7d-f98cf1215afd)

   (b)Make the script executable: chmod +x calc.sh

   (c)Run the script: ./calc.sh 
   ![image](https://github.com/user-attachments/assets/3706d899-63b2-4fa1-a968-9942eb83ce7e)

3. Use Redirection Operators to Store Output of Commands -> (a)Redirect stdout to a file: ls > 
   output.txt
   ![image](https://github.com/user-attachments/assets/e6d9b63d-fccb-49f2-ab33-dff3d494d1a0)

   (b)Append output to an existing file: date >> output.txt
    ![image](https://github.com/user-attachments/assets/b684bc5a-213f-4836-9bd2-65400296d60b)
    ![image](https://github.com/user-attachments/assets/103fe163-2faa-4c7f-8c13-636cbc9c05ac)

   (c)Redirect stderr to a file: ls nonexistentfile 2> error.txt
    ![image](https://github.com/user-attachments/assets/7893f991-d579-4161-ad40-fccf8fd31840)

   (d)Redirect both stdout and stderr to a file: ls . nonexistentfile &> all_output.txt
    ![image](https://github.com/user-attachments/assets/f25f1de0-eca6-4ffe-aa7f-1b1c1629a08a)
    ![image](https://github.com/user-attachments/assets/12c7f251-1cb1-4da1-89e7-1a6c9e6abc54)

   (e)Pipe output to another command: cat file.txt | grep "keyword"
    ![image](https://github.com/user-attachments/assets/b153f8b2-388a-4baf-b421-9d5617c16500)
