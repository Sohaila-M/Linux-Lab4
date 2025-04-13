# Linux-Lab4
1. List **all running processes** and save the output to `~/processes.txt`.  ![image](https://github.com/user-attachments/assets/20c281fb-651e-4b61-b2a4-9ac3db764925)

2. Find the **PID (Process ID)** of the `sshd` service.  ![image](https://github.com/user-attachments/assets/66dfb3ad-acb6-457f-b015-a2d9bc3cc7c9)  ![image](https://github.com/user-attachments/assets/46ef5102-1a79-44b8-8176-3f07fa5408ae)


3. Run a `sleep 500` command in the background, then **kill it** after 5 seconds. ![image](https://github.com/user-attachments/assets/5ddc8905-3fc0-487a-9946-45fe076ebf3d)
 

4. Install `apache2` service, edit the default HTML file (`/var/www/html/index.html`), and verify changes in a web browser. (Couldn't install it on my computer)
  
5. **Check if `sshd` (SSH service) is running**. If not, start and enable it.  ![image](https://github.com/user-attachments/assets/def60fc6-0715-4289-b419-bb6822d11b45)

6. **Restart the `cron` service** and verify its status.  ![image](https://github.com/user-attachments/assets/e15e214c-c0e5-4476-bf9f-543626cc1553)


7. Create a **compressed tarball** (`archive.tar.gz`) of `/var/log` and save it in your home directory.  ![image](https://github.com/user-attachments/assets/e3938a2c-b347-44be-992c-3f9a79b6ff2b)

8. **Extract** the tarball into `~/logs_backup/`.   ![image](https://github.com/user-attachments/assets/2f358182-81b3-43df-9947-ca1936f7a798) ![image](https://github.com/user-attachments/assets/61187d1a-3ff4-4ea3-a004-6f4fec557fcb)


9. Create a **non-compressed tarball** (`archive.tar`) of `/etc/ssh` and save it in `/tmp`. ![image](https://github.com/user-attachments/assets/369f8ecf-d58b-4dce-a8a7-e1da2c143cad)
 

10. Compress `~/processes.txt` using `gzip`.  ![image](https://github.com/user-attachments/assets/2987a53b-f45c-46b6-aa7b-926b6f246faf) After Compression we can see that the file size decreased ![image](https://github.com/user-attachments/assets/940ecb47-19a0-49c1-9416-2ce22512034c)


11. **Decompress** it and compare file sizes using `ls -lh`.  We can see that after decompression the file goes back to its original size ![image](https://github.com/user-attachments/assets/e07c2432-227f-4dc4-9bac-7e3431d31d90)


12. **Install `htop`** (a process viewer) using your package manager.  ![image](https://github.com/user-attachments/assets/19e0d13d-8aa3-450a-81ee-191cdefca3fc)

13. **Search for the package `nginx`** (or `httpd`) but do not install it.  ![image](https://github.com/user-attachments/assets/ef0fbfef-fb1c-4640-ae02-e3ac2c7d365d)

14. **Remove the `vim` editor** (if installed) and then reinstall it.  ![image](https://github.com/user-attachments/assets/9740d9fc-305b-413b-b6df-82179875064a)                        
 ![image](https://github.com/user-attachments/assets/9441dd23-aa2c-4b5e-98ed-2066a3aba37b)


15. Use `wget` to download the Linux kernel source:  
   ![image](https://github.com/user-attachments/assets/c090190e-eaf9-4853-8c87-c0a7ce2ce40e)

16. Use `curl` to fetch **Google’s homepage** and save it as `google.html`.  ![image](https://github.com/user-attachments/assets/e80f69c8-1454-4805-9ea0-352e16fab464)


17. **Create a new VM** (e.g., VirtualBox/Cloud instance), add a user to the `sudoers` group, and run `apt update && apt upgrade`.         multipass launch --name myvm       
multipass shell myvm  
sudo adduser myuser  
sudo usermod -aG sudo myuser  
sudo apt update && sudo apt upgrade -y  

18. **Generate an SSH key pair** using `ssh-keygen`.  ![Capture](https://github.com/user-attachments/assets/2e4a6883-e175-4fa8-98d1-ecc1329c978c)

19. **Copy your public key** to the remote server:                                                                                         
  ssh-copy-id
20. **SSH into the server** and verify with `hostname`.                                                                                 
 ssh newuser@myvm        hostname
21. **Transfer the archived file** (e.g., `archive.tar.gz`) to the remote server using ssh copy way (don’t copy/paste >>> you have to search)
scp archive.tar.gz 
newuser@vm:/home/
