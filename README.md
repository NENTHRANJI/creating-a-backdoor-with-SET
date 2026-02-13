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
## OUTPUT

<img width="1918" height="760" alt="image" src="https://github.com/user-attachments/assets/12010459-f4bd-45c9-bc70-b4ceb8b56e34" />


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

<img width="1918" height="291" alt="image" src="https://github.com/user-attachments/assets/8113d515-42db-44ad-8597-f5615f19670e" />


It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

<img width="1920" height="225" alt="image" src="https://github.com/user-attachments/assets/e3052d2f-95f2-4dec-91a9-17fe6f36b44a" />


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT
<img width="1913" height="245" alt="image" src="https://github.com/user-attachments/assets/c4e43a98-53b0-45ab-af68-0806888162c6" />



It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT


<img width="1920" height="383" alt="image" src="https://github.com/user-attachments/assets/bfae0e12-54ff-4247-930c-5667bc5bac29" />


It shows the following screen in which the option Google can be selected:
## OUTPUT
<img width="1920" height="409" alt="image" src="https://github.com/user-attachments/assets/7e0dc83b-3672-429e-b0d3-aef06b3e9ffc" />





SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/79a96b6d-0e43-4199-a981-2d2905f7c89a" />



In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT

<img width="1920" height="165" alt="image" src="https://github.com/user-attachments/assets/bf979c8b-67c8-404e-b217-4e2bc4fe9998" />

SET logs the information regarding the Google credentials:
## OUTPUT


<img width="1920" height="216" alt="image" src="https://github.com/user-attachments/assets/773f5187-a8f2-46ca-a903-b9a9e362cd92" />

SET logs the information in the xml file under /root/.set directory:
## OUTPUT


<img width="1920" height="527" alt="image" src="https://github.com/user-attachments/assets/bd342b87-0b59-4bcf-b152-e1b76f69eff6" />










## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
