# Metasploit-for-reconnaissance
# Metasploit
Metasploit for reconnaissance in pentesting

# AIM:

To get introduced to Metasploit Framework and to  perform reconnaissance  in pentesting .

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:

#Step1:Identify the Attacker’s IP Address
Determine the IP address of the attacker's system.

![image](https://github.com/user-attachments/assets/6ef20a3c-7590-4d21-a7fb-b45b26779412)

#Step2:Launch the Metasploit Console
Invoke the msfconsole.
![image](https://github.com/user-attachments/assets/e22d19f1-d76b-4646-9fd6-9d3048c9a005)
To view available commands, enter "?".

![430711300-9898388a-1dd5-4eb6-9501-135fa8364205](https://github.com/user-attachments/assets/43d3d611-8f76-4b6e-b1ec-f9e0d3ba82b9)

#Step3:Generate Payload Using msfvenom
Execute the following command to generate a Windows Meterpreter reverse shell payload.

![image](https://github.com/user-attachments/assets/ccf225c8-7cd0-4d78-a730-862cfeccc2b3)

#Step4:Set Up an HTTP Server
Once the payload file is created, navigate to the home directory. Right-click and select "open terminal here".

![image](https://github.com/user-attachments/assets/70f50965-d211-4ec9-80c8-6bf49756c65f)

Run the Python command to establish an HTTP server for file distribution.

![image](https://github.com/user-attachments/assets/512d0253-f2f3-4892-999a-1331b178cc32)

#Step5:Distribute the Payload
Share the .exe file with the target system via any medium or the HTTP server.

Once the victim downloads and executes the file, the exploit is triggered.

#VICTIM DEVICE:
![image](https://github.com/user-attachments/assets/bd05b26e-5206-4c63-a6d4-00fc7d37e822)

![image](https://github.com/user-attachments/assets/92eabe0f-c056-4e4d-9989-4bd875ba0400)

#Step6:Establish a Connection
On Kali Linux, reopen the terminal and invoke "msfconsole". Follow the necessary steps to establish a connection with the victim’s device.
![image](https://github.com/user-attachments/assets/479f4c7e-d7fb-401a-bd5b-30ff506a2654)
#Step7:List commands
Use the help command to list available operations.
![Screenshot 2025-04-07 143751](https://github.com/user-attachments/assets/0a4d6988-02d5-4410-8f8f-53086b873e20)

#Step8:
For example, the "screenshot" command captures the victim’s screen and saves it in the attacker's home directory.
![image](https://github.com/user-attachments/assets/c0a758de-de2a-4d37-935b-a8dab1d04129)
![430799096-b2bd93b8-20cc-4105-8bda-09e37e51533c](https://github.com/user-attachments/assets/ba7f892a-44d2-4efd-a2bd-9d702351e904)
#Step9:Terminate the Connection
After completing the intended operations, close the session securely.

## RESULT:
The Metasploit framework for reconnaissance is  examined successfully
