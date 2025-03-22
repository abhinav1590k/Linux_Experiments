			LAB  EXPERIMENT- 2
1. Open the editing_final_lab.txt file in Vim and Nano: -> VIM- vim editing_final_lab.txt NANO- nano editing_final_lab.txt
   ![image](https://github.com/user-attachments/assets/cf168718-5b0d-4fcc-b3f8-020401a5881e)
   ![image](https://github.com/user-attachments/assets/64bc5f4e-15ff-4661-ac7c-1b7f4a64affc)
   ![image](https://github.com/user-attachments/assets/b7cae13c-7a2b-4d27-8fc8-d670ac7255bd)
   ![image](https://github.com/user-attachments/assets/132604d5-061d-4aac-aa3b-dd61a8e73603)
   
2. Use the lab_file shell variable: -> lab_file="editing_final_lab.txt" vim $lab_file
   ![image](https://github.com/user-attachments/assets/a4131891-d214-4e58-beff-4a1c84fc338f)

3. Enter visual mode in Vim: -> Open Vim. Press v to enter visual mode.
   ![image](https://github.com/user-attachments/assets/74bb6143-d569-4d23-ab97-6fb89c2bb2da)
4. Remove the last seven characters from the first line: -> Press ^ (caret) to go to the beginning of the line. Press v to start selecting characters. Move to the end of the line using $. Press d7 to delete the last 7 characters.

5. Preserve only the first four characters of the first column: -> Go to the beginning of the line using 0. Press v and move to the 4th character using l (right arrow). Press d to delete everything after the 4th character.

6. Save and exit: -> :wq

 




