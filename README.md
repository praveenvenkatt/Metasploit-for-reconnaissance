# Metasploit-for-reconnaissance
## Metasploit
Metasploit for reconnaissance in pentesting
```
Register Number: 212222040121
Name: Praveen V
```
## AIM:

To get introduced to Metasploit Framework and to  perform reconnaissance  in pentesting .

## DESIGN STEPS:



1.Install kali linux either in partition or virtual box or in live mode


2.Investigate on the various categories of tools as follows:


3.Open terminal and try execute kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
### Step1:Identify the Attacker’s IP Address
Determine the IP address of the attacker's system.

![image](https://github.com/user-attachments/assets/bb1c6730-c2c2-443a-8518-867238a569d8)

### Step2:Launch the Metasploit Console
Invoke the **msfconsole**.

![image](https://github.com/user-attachments/assets/4d1d9bf4-d238-4292-8adf-1258012b7d4c)


To view available commands, enter **"?"**.
![image](https://github.com/user-attachments/assets/27abd468-0de1-4ed6-8ac2-e892d912e35d)


### Step3:Generate Payload Using msfvenom

Execute the following command to generate a Windows Meterpreter reverse shell payload.
![image](https://github.com/user-attachments/assets/dc16bb9d-a0e6-4b45-96dd-1b5a0d507115)

### Step4:Set Up an HTTP Server
Once the payload file is created, navigate to the home directory.
Right-click and select **"open terminal here"**.

![Screenshot 2025-03-28 210707](https://github.com/user-attachments/assets/f5f434cb-b251-4d01-8ca3-ebb6afe1bb0f)

Run the Python command to establish an HTTP server for file distribution.
![Screenshot 2025-03-28 140418](https://github.com/user-attachments/assets/8efd9834-3907-413d-84d9-d27e879f918c)

### Step5:Distribute the Payload
Share the .exe file with the target system via any medium or the HTTP server.

Once the victim downloads and executes the file, the exploit is triggered.

**VICTIM DEVICE:**
![WhatsApp Image 2025-03-28 at 14 47 45_03c71856](https://github.com/user-attachments/assets/dbb317e6-b57b-4c04-9908-778d020851b2)

![WhatsApp Image 2025-03-28 at 14 47 45_6a2f6d61](https://github.com/user-attachments/assets/9bc15080-9257-4b03-9a7b-a8d9a050b8e5)

### Step6:Establish a Connection
On Kali Linux, reopen the terminal and invoke **"msfconsole"**.
Follow the necessary steps to establish a connection with the victim’s device.

![Screenshot 2025-03-28 142550](https://github.com/user-attachments/assets/a0cbd2d8-92db-46a2-bc17-73e3744e43de)

Once exploited, a session is created, allowing remote access without the victim’s awareness.

### Step7:List commands
Use the help command to list available operations.

![Screenshot 2025-03-28 142611](https://github.com/user-attachments/assets/ce47f27f-d0bd-49fb-b0a8-f90351ce7896)

### Step8:
For example, the **"screenshot"** command captures the victim’s screen and saves it in the attacker's home directory.
![Screenshot 2025-03-28 142630](https://github.com/user-attachments/assets/efa1cb48-4d7a-4161-b133-269d25abb04f)

![Screenshot 2025-03-28 142704](https://github.com/user-attachments/assets/de62a1bf-6fa3-4b9f-b1ad-b2c99355b55e)

### Step9:Terminate the Connection
After completing the intended operations, close the session securely.

#### RESULT:
The Metasploit framework for reconnaissance is  examined successfully.
