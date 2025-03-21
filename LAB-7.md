1. chown Command -> (a)Change the owner of a file: sudo chown user1 file.txt
   ![image](https://github.com/user-attachments/assets/c80e7cad-f7da-4f3c-911f-8d89fdaf7d0a)

  (b)Change the owner and group of a file: sudo chown user1:usergroup file.txt
  ![image](https://github.com/user-attachments/assets/f11ed9eb-a678-4b3c-a073-d43d20589a54)

  (c)Change only the group: sudo chown :usergroup file.txt
  ![image](https://github.com/user-attachments/assets/fdca9e4d-3ba6-4f6c-ae4c-7eb10a5087aa)

  (d)Change ownership recursively (for directories): sudo chown -R user1:usergroup /path/to/directory
  ![image](https://github.com/user-attachments/assets/94a6f179-4c48-46cd-bd77-0c587d208ca2)

  (e)Transfer ownership to root: sudo chown root file.txt
  ![image](https://github.com/user-attachments/assets/ba5f154f-3fe4-47dc-b9fe-0c663d476826)

  (f)Use --from to change from a specific owner: sudo chown --from=current_owner new_owner file.txt 
  ![image](https://github.com/user-attachments/assets/49b3ff52-137b-4b82-a7d7-ee9cb5c8a557)


2. chmod Command -> (a)Give execute permission to the user: chmod u+x file.txt
   ![image](https://github.com/user-attachments/assets/8dbab1cb-3097-442d-b06f-8ab835905c54)

  (b)Remove write permission for others: chmod o-w file.txt
  ![image](https://github.com/user-attachments/assets/8c23a8b8-f843-46b4-a3cc-4e09b2510ae3)

  (c)Give read and execute permission to the group: chmod g+rx file.txt
  ![image](https://github.com/user-attachments/assets/7c727b65-6f61-418c-ab0e-ab93c70ec20a)

  (d)Set specific permissions: chmod u=rwx,g=rx,o=r file.txt
  ![image](https://github.com/user-attachments/assets/5e7e32bf-4d92-4cb9-bdb8-b256833c7c1a)

  (e)Set permissions to rwxr-xr-- using octal mode: chmod 754 file.txt
  ![image](https://github.com/user-attachments/assets/a4d029b7-3e96-4afd-8a9c-45f4c59c7f10)

  (f)Recursive Change of Permissions: chmod -R 755 /path/to/directory
  ![image](https://github.com/user-attachments/assets/8cd07af6-3eec-4b03-ad90-d6a5bfb24483)

  (g)Change permissions based on existing files: chmod --reference=ref_file.txt target_file.txt
  ![image](https://github.com/user-attachments/assets/47817e02-8407-4ad7-995d-0fd177d88d0f)




