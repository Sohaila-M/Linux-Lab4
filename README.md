# Linux-Lab4
1. List **all running processes** and save the output to `~/processes.txt`.  ![image](https://github.com/user-attachments/assets/20c281fb-651e-4b61-b2a4-9ac3db764925)

2. Find the **PID (Process ID)** of the `sshd` service.  ![image](https://github.com/user-attachments/assets/66dfb3ad-acb6-457f-b015-a2d9bc3cc7c9)  ![image](https://github.com/user-attachments/assets/46ef5102-1a79-44b8-8176-3f07fa5408ae)


3. Run a `sleep 500` command in the background, then **kill it** after 5 seconds. ![image](https://github.com/user-attachments/assets/5ddc8905-3fc0-487a-9946-45fe076ebf3d)
 

4. Install `apache2` service, edit the default HTML file (`/var/www/html/index.html`), and verify changes in a web browser. 
  
5. **Check if `sshd` (SSH service) is running**. If not, start and enable it.  ![image](https://github.com/user-attachments/assets/def60fc6-0715-4289-b419-bb6822d11b45)

6. **Restart the `cron` service** and verify its status.  ![image](https://github.com/user-attachments/assets/e15e214c-c0e5-4476-bf9f-543626cc1553)


7. Create a **compressed tarball** (`archive.tar.gz`) of `/var/log` and save it in your home directory.  ![image](https://github.com/user-attachments/assets/e3938a2c-b347-44be-992c-3f9a79b6ff2b)

8. **Extract** the tarball into `~/logs_backup/`.   ![image](https://github.com/user-attachments/assets/2f358182-81b3-43df-9947-ca1936f7a798) ![image](https://github.com/user-attachments/assets/61187d1a-3ff4-4ea3-a004-6f4fec557fcb)


9. Create a **non-compressed tarball** (`archive.tar`) of `/etc/ssh` and save it in `/tmp`.  

10. Compress `~/processes.txt` using `gzip`.  ![image](https://github.com/user-attachments/assets/2987a53b-f45c-46b6-aa7b-926b6f246faf) After Compression we can see that the file size decreased ![image](https://github.com/user-attachments/assets/940ecb47-19a0-49c1-9416-2ce22512034c)


11. **Decompress** it and compare file sizes using `ls -lh`.  We can see that after decompression the file goes back to its original size ![image](https://github.com/user-attachments/assets/e07c2432-227f-4dc4-9bac-7e3431d31d90)


12. **Install `htop`** (a process viewer) using your package manager.  
13. **Search for the package `nginx`** (or `httpd`) but do not install it.  
14. **Remove the `vim` editor** (if installed) and then reinstall it.  

15. Use `wget` to download the Linux kernel source:  
    
    ```  
16. Use `curl` to fetch **Google’s homepage** and save it as `google.html`.  

17. **Create a new VM** (e.g., VirtualBox/Cloud instance), add a user to the `sudoers` group, and run `apt update && apt upgrade`.  
18. **Generate an SSH key pair** using `ssh-keygen`.  
19. **Copy your public key** to the remote server:  
20. **SSH into the server** and verify with `hostname`.  
21. **Transfer the archived file** (e.g., `archive.tar.gz`) to the remote server using ssh copy way (don’t copy/paste >>> you have to search)


