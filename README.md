# Metasploit-for-reconnaissance
## Metasploit
Metasploit for reconnaissance in pentesting

## AIM:

To get introduced to Metasploit Framework and to  perform reconnaissance  in pentesting .

## DESIGN STEPS:

## Step 1:

Install kali linux either in partition or virtual box or in live mode

## Step 2:

Investigate on the various categories of tools as follows:

## Step 3:

Open terminal and try execute kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
### Step1:
Find out the ip address of the attackers system

![image](https://github.com/user-attachments/assets/bb1c6730-c2c2-443a-8518-867238a569d8)

### Step2:
Invoke the **msfconsole**.

![image](https://github.com/user-attachments/assets/4d1d9bf4-d238-4292-8adf-1258012b7d4c)


To know more about the msfconsole commands give **"?"**.
![image](https://github.com/user-attachments/assets/27abd468-0de1-4ed6-8ac2-e892d912e35d)


### Step3:
Generate Payload Using msfvenom

Run the following command to generate a Windows Meterpreter reverse shell payload
![image](https://github.com/user-attachments/assets/dc16bb9d-a0e6-4b45-96dd-1b5a0d507115)

### Step4:
After the payload file is created go to the home directory.
In this directory right click and select the option "open terminal here".

![Screenshot 2025-03-28 210707](https://github.com/user-attachments/assets/f5f434cb-b251-4d01-8ca3-ebb6afe1bb0f)

In this terminal run the python code to establish the http server
![Screenshot 2025-03-28 140418](https://github.com/user-attachments/assets/8efd9834-3907-413d-84d9-d27e879f918c)

### Step4:
Make the victim user  to download the exe file in his/her device which was created by us using msfvenom.
By sharing exe file through any media  or using the server the exe file can be downloaded.
**VICTIM DEVICE:**
![WhatsApp Image 2025-03-28 at 14 47 45_03c71856](https://github.com/user-attachments/assets/dbb317e6-b57b-4c04-9908-778d020851b2)

After downloading make them to run.
![WhatsApp Image 2025-03-28 at 14 47 45_03c71856](https://github.com/user-attachments/assets/fe327381-891d-4f91-b3af-4ece1a8d21e2)










#### RESULT:
The Metasploit framework for reconnaissance is  examined successfully.
