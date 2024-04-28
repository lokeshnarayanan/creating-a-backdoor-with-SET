# Creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:
### Step 1:
Install kali linux either in partition or virtual box or in live mode.

### Step 2:
Investigate on the various categories of tools as follows.

### Step 3:
Open terminal and try execute some kali linux commands.

### DEVELOPED BY : Lokesh N
### REGISTER NO : 212222100023

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. The command sudo setoolkit in the prompt gives menu with set prompt:

![image](https://github.com/lokeshnarayanan/creating-a-backdoor-with-SET/assets/119393019/a4b1b1f1-65a9-4a38-829b-712a1846d1d5)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
It displays the following menu and select 2 for Website Attack Vectors:

![image](https://github.com/lokeshnarayanan/creating-a-backdoor-with-SET/assets/119393019/3fc01052-16bd-4f19-9de2-777abcbe7ee0)


The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:


![image](https://github.com/lokeshnarayanan/creating-a-backdoor-with-SET/assets/119393019/c05b3b95-bf0f-4fa2-8abc-90edd4c124a7)


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected: 

![image](https://github.com/lokeshnarayanan/creating-a-backdoor-with-SET/assets/119393019/73dd518a-3b2c-44b0-8ea7-fffa6381e05f)


It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![image](https://github.com/lokeshnarayanan/creating-a-backdoor-with-SET/assets/119393019/38c5dfb4-d704-4a68-b091-9aa577e8f99a)


It shows the following screen in which the option Google can be selected: 

![image](https://github.com/lokeshnarayanan/creating-a-backdoor-with-SET/assets/119393019/21883a45-3aec-414a-9e9e-1a21322e7ad9)


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done: 
![image](https://github.com/lokeshnarayanan/creating-a-backdoor-with-SET/assets/119393019/d80c4334-ae68-4fda-a40c-df2cb7c7e3e6)



In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password 

![image](https://github.com/lokeshnarayanan/creating-a-backdoor-with-SET/assets/119393019/4f5ce701-8951-4e4a-a7af-6b811f117dbf)


SET logs the information regarding the Google credentials: 
![image](https://github.com/lokeshnarayanan/creating-a-backdoor-with-SET/assets/119393019/f10e904e-7dc4-4a16-bf1e-69b7aa521fd1)



SET logs the information in the xml file under /root/.set directory:


![image](https://github.com/lokeshnarayanan/creating-a-backdoor-with-SET/assets/119393019/aa739f13-971c-4f33-9ba6-04db33869736)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
