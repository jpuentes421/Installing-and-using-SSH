# Installing-and-using-SSH

## Objective

 Connect and use SSH to securely transmit data. We will be installing and starting the SSH server in Kali and installing the PUTTY executable in the Windows VM. Kali will be used as the server and PUTTY in the windows box will be used as a client to connect to the Kali. 


### Skills Learned

- Install and start SSH service on Kali using the CMD prompt.
- PUTTY executable to SSH to the Kali box.

### Tools Used

- Kali
- Windows 10
- PUTTY 


## Steps
1. Start Kali and open a terminal. Type in sudo apt install openssh-server.
2. Once it is installed, we want to start the service, type in sudo service ssh start.
3. The SSH service should be ready to go.
4. Create a folder on the Kali desktop and label it "SSH Test"
5. In the folder make another folder called "Test 1"
6. We are creating folders on the Kali box to confirm we are connected.
7. Be sure to collect the IP address of the kali box, we will need this when we use the PUTTY client.
8. Navigate to the Windows box.
9. Google PUTTY to download the client which will allow us to connect o the SSH server.
10. Select putty.exe (the SSH and Telnet client itself) download for 64-bit x86.
11. Once the PUTTY executable opens, type in the IP address for the Kali box in the Host Name (or IP address). Click Open.
12. Login as Kali, and input the password for your Kali box.
13. Now we are connected and fully administering the Kali box using SSH.
14. To verify, input the command: ls
15. You can now see the Kali Desktop and folders. Input the command ls Desktop to see the folder you created earlier.
16. You will now see this folder (I named my folder elsa), and can verify you are fully administering the Kali box!

Connecting to Kali server via PUTTY connect in the Windows box:

![image](https://github.com/user-attachments/assets/570b5cd0-aef2-4ea8-8e24-d73e932cace8)

