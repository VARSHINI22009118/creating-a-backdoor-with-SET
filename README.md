# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:

![Screenshot 2024-04-30 170809](https://github.com/VARSHINI22009118/creating-a-backdoor-with-SET/assets/119401150/d8cd8cf7-a682-4a57-a087-fe527b00b854)



The command sudo setoolkit in the prompt gives menu with set prompt. Select menu 1 for Social Engineering Attacks:

![Screenshot 2024-04-30 170120](https://github.com/VARSHINI22009118/creating-a-backdoor-with-SET/assets/119401150/f4edb330-9312-4f25-aca6-a67b833f75b6)


It displays the following menu and select 2 for Website Attack Vectors:

![Screenshot 2024-04-30 170215](https://github.com/VARSHINI22009118/creating-a-backdoor-with-SET/assets/119401150/0b274cef-a871-47bc-b083-c6aeab259015)


The website Attack Vectors displays the following menu. In this menu 3 for Credential Harvester Attack Method is selected:

![Screenshot 2024-04-30 170249](https://github.com/VARSHINI22009118/creating-a-backdoor-with-SET/assets/119401150/83e7a966-ab97-430f-8615-1a43b2e1bf6b)


The Credential Harvester Attack Method displays the following menu. In this menu 1 for Web Templates is selected,
It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![Screenshot 2024-04-30 170322](https://github.com/VARSHINI22009118/creating-a-backdoor-with-SET/assets/119401150/179b47d7-1cfc-4ca1-98de-768a45b05b23)

It shows the following screen in which the option Google can be selected:

![Screenshot 2024-04-30 170351](https://github.com/VARSHINI22009118/creating-a-backdoor-with-SET/assets/119401150/e3ee7c51-603b-49e3-a1a0-e9ac58bd2a68)


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![Screenshot 2024-04-30 170641](https://github.com/VARSHINI22009118/creating-a-backdoor-with-SET/assets/119401150/1fb845ff-49e8-4f28-9dcf-3ef767527846)


In windows IE, on giving the url http://192.168.1.8, the fake Google page is displayed. The victim can enter the username and password

![Screenshot 2024-04-30 170610](https://github.com/VARSHINI22009118/creating-a-backdoor-with-SET/assets/119401150/ba55fb7f-3f73-45f6-aee3-08b37bfa36fc)


SET logs the information regarding the Google credentials:

![Screenshot 2024-04-30 170703](https://github.com/VARSHINI22009118/creating-a-backdoor-with-SET/assets/119401150/4bfa9493-0862-4e14-a1fb-2df7e62594ba)


SET logs the information in the xml file under /root/.set directory
## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
