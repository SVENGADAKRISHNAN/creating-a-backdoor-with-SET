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
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to 
the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
![image](https://github.com/vishnudorigundla/creating-a-backdoor-with-SET/assets/94175324/06baec76-9600-4492-96ab-96da09722b0f)
It displays the following menu and select 2 for Website Attack Vectors:
![image](https://github.com/vishnudorigundla/creating-a-backdoor-with-SET/assets/94175324/85305ad3-927a-4b8c-9d3c-96846958a8bc)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![image](https://github.com/vishnudorigundla/creating-a-backdoor-with-SET/assets/94175324/911f4a04-ee4b-4fe8-a82c-087360f41241)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
![image](https://github.com/vishnudorigundla/creating-a-backdoor-with-SET/assets/94175324/2e686e9b-660b-4519-9d7f-9988e863bf1c)
It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![image](https://github.com/vishnudorigundla/creating-a-backdoor-with-SET/assets/94175324/2ff1c2df-1917-4a35-99cc-324ae8fa3c5c)

It shows the following screen in which the option Google can be selected:

![image](https://github.com/vishnudorigundla/creating-a-backdoor-with-SET/assets/94175324/32c2796f-dcb3-43ff-b4b2-e30af7df3aaf)
SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
![image](https://github.com/vishnudorigundla/creating-a-backdoor-with-SET/assets/94175324/66af187f-5b81-4936-aa39-3ef43cd4b2a4)


In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![image](https://github.com/AasrithSairam/creating-a-backdoor-with-SET/assets/139331438/48684515-2f0f-4bf6-b446-d21d0e1b799f)


SET logs the information regarding the Google credentials:

![l](https://github.com/praveenst13/creating-a-backdoor-with-SET/assets/118787793/569bac5b-8b6b-4f99-b679-bdf6e3878475)
SET logs the information in the xml file under /root/.set directory:
![image](https://github.com/vishnudorigundla/creating-a-backdoor-with-SET/assets/94175324/bd3d89c1-6d9b-46e1-baf8-219a7cf61f09)







## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
