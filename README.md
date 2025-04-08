# Linux-Lab4
1. List **all running processes** and save the output to `~/processes.txt`.  
2. Find the **PID (Process ID)** of the `sshd` service.  
3. Run a `sleep 500` command in the background, then **kill it** after 5 seconds.  

4. Install `apache2` service, edit the default HTML file (`/var/www/html/index.html`), and verify changes in a web browser.  
5. **Check if `sshd` (SSH service) is running**. If not, start and enable it.  
6. **Restart the `cron` service** and verify its status.  

7. Create a **compressed tarball** (`archive.tar.gz`) of `/var/log` and save it in your home directory.  
8. **Extract** the tarball into `~/logs_backup/`.  
9. Create a **non-compressed tarball** (`archive.tar`) of `/etc/ssh` and save it in `/tmp`.  

10. Compress `~/processes.txt` using `gzip`.  
11. **Decompress** it and compare file sizes using `ls -lh`.  

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


