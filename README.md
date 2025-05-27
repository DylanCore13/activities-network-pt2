# activities-network-pt2


![image](https://github.com/user-attachments/assets/4ed2242a-809c-45a7-9fab-4091aef6f850)    ![image](https://github.com/user-attachments/assets/8ad90810-eb97-4e8a-877a-8c34541b3594)





<h2>Observing ICMP Traffic</h2>

- Welcome to 2nd part!!!








If using Mac, install Microsoft Remote Desktop




Use Remote Desktop to connect to your Windows 10 Virtual Machine, copy ip address and log in with username and password set up on virtual machine when you were createing it

![image](https://github.com/user-attachments/assets/51b86540-027b-4bcf-8f4b-8cac82c74ebd)


![image](https://github.com/user-attachments/assets/cd79c046-0012-4767-972f-1ed925537e36)



Once you're logged in within your Windows 10 Virtual Machine, Install https://www.wireshark.org (It's going to be the Windows x64 Installer)



![image](https://github.com/user-attachments/assets/9a6f3ecc-f272-4e8e-b87a-e33e2f9f4335)




Open Wireshark and start packet capture

![image](https://github.com/user-attachments/assets/b8bffe7b-241f-45f3-a514-75611073f98c)



Within Wireshark, filter for ICMP traffic only

![image](https://github.com/user-attachments/assets/06f24044-34f9-4d9a-9486-4046e6bac987)



Retrieve the private IP address of the Ubuntu VM (linux-vm) and attempt to ping it from within the Windows 10 VM


![image](https://github.com/user-attachments/assets/5dff8edb-9da7-4458-859e-b21405a19711)


![image](https://github.com/user-attachments/assets/f8a57fc9-09ae-4a1b-9434-bfe181d45fb0)


- Observe ping requests and replies within WireShark

![image](https://github.com/user-attachments/assets/4dfebd2b-d99c-4e3e-b915-33320e6bd1f3)

  
From The Windows 10 VM, open command line or PowerShell and attempt to ping a public website (such as www.google.com) and observe the traffic in WireShark


![image](https://github.com/user-attachments/assets/cd2d770e-f651-4eb1-8486-2e9d18cb0e5c)


