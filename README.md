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

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

### EXECUTION STEPS AND ITS OUTPUT:
### Step 1: Identify the Attacker’s IP Address
Determine the IP address of the attacker's system.

### Step 2: Launch the Metasploit Console
Invoke the msfconsole.
To view available commands, enter ?.

### Step 3: Generate Payload Using msfvenom
Execute the following command to generate a Windows Meterpreter reverse shell payload.

### Step 4: Set Up an HTTP Server
Once the payload file is created, navigate to the home directory. Right-click and select "Open Terminal Here."
Run the Python command to establish an HTTP server for file distribution.

### Step 5: Distribute the Payload
Share the .exe file with the target system via any medium or the HTTP server.
Once the victim downloads and executes the file, the exploit is triggered.

### Step 6: Establish a Connection
On Kali Linux, reopen the terminal and invoke msfconsole.
Follow the necessary steps to establish a connection with the victim’s device.
Once exploited, a session is created, allowing remote access without the victim’s awareness.

### Step 7: Execute Commands on the Victim’s Device
Use the help command to list available operations.
For example, the screenshot command captures the victim’s screen and saves it in the attacker's home directory.

### Step 8: Terminate the Connection
After completing the intended operations, close the session securely.

#### RESULT:
The Metasploit framework for reconnaissance is  examined successfully.
