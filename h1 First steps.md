# ["Intelligence-Driven Computer Network Defense Informed by Analysis of Adversary Campaigns and Intrusion Kill Chains"](https://www.lockheedmartin.com/content/dam/lockheed-martin/rms/documents/cyber/LM-White-Paper-Intel-Driven-Defense.pdf) white paper from Lockheed Martin Corporation by Eric M. Hutchins, Michael J. Cloppert, Rohan M. Amin, Ph.D.

## Summary
The article discusses how traditional network defense tools such as intrusion detection systems and anti-virus are no longer sufficient to protect against advanced persistent threats (APTs). APTs are well-resourced and trained adversaries who conduct long-term intrusion campaigns targeting sensitive information. The article suggests that an intelligence-based model of network defense, which uses a kill chain model and maps adversary indicators to defender courses of action, is necessary to mitigate the threat component of risk in addition to vulnerability.
## Intrusion Kill Chain
A kill chain is a systematic process used to target and engage an adversary in order to achieve a desired outcome. The U.S. military defines the steps of this process as find, fix, track, target, engage, and assess (F2T2EA). This model is integrated and end-to-end, with any deficiency interrupting the entire process. The paper presents a new kill chain model specifically for intrusions, which includes the stages of reconnaissance, weaponization, delivery, exploitation, installation, command and control, and actions on objectives.

The intrusion kill chain model can be used for intelligence-driven computer network defense (CND) by aligning enterprise defensive capabilities to the specific processes an adversary undertakes to target the enterprise. By measuring performance and effectiveness of these actions, defensive capabilities can be improved by identifying and rectifying any capability gaps. This approach is based on a keen understanding of the adversary and includes a course of action matrix using the actions of detect, deny, disrupt, degrade, deceive and destroy to illustrate the spectrum of capabilities defenders can employ.

Intelligence-driven computer network defense is necessary to address advanced persistent threats as traditional, vulnerability-focused processes are insufficient. The intrusion kill chain model provides a structure to analyze intrusions, extract indicators, drive defensive courses of action, prioritize investment for capability gaps, and measure the effectiveness of the defenders’ actions. 
By considering the threat component of risk and modeling the cost-benefit ratio for the aggressor, it is possible to establish information superiority and decrease the adversary’s likelihood of success with each intrusion attempt.


# [Command Line Basics Revisited](https://terokarvinen.com/2020/command-line-basics-revisited)
```
1. ls - List the files in the current directory
2. cd - Change the current working directory
3. pwd - Print the current working directory
4. mkdir - Create a new directory
5. touch - Create a new file
6. cp - Copy a file or directory
7. mv - Move or rename a file or directory
8. rm - Remove a file or directory
9. cat - Display the contents of a file
10. echo - Print a message to the terminal
11. man - Display the manual for a command
12. chmod - Change the permissions of a file or directory
13. grep - Search for a string in a file or output
14. find - Search for files in a directory hierarchy
15. sort - Sort the lines of a file
16. head - Display the first lines of a file
17. tail - Display the last lines of a file
18. diff - Compare the contents of two files
19. tar - Create or extract a tar archive
20. ssh username@server.com secure remote connect
```
# h1 First steps
## Become a hacker, step 0

## a) Bandit oh-five: levels 0-4
First challenge starts with solving the [Over The Wire: Bandit](https://overthewire.org/wargames/bandit/) 
> The Bandit wargame is aimed at absolute beginners. It will teach the basics needed to be able to play other wargames.

## Level 0
> The goal of this level is for you to log into the game using SSH. The host to which you need to connect is bandit.labs.overthewire.org, on port 2220. The username is bandit0 and the password is bandit0. Once logged in, go to the Level 1 page to find out how to beat Level 1.

I am familiar with Linux command line interface and server login (I use to manage multiple servers way back) this task was simple. But first I need to run the step (b) to run Linux commands (I am using Windows 10)

## b) Install Debian 11-Bullsye [VM in VirtuaBox](https://terokarvinen.com/2021/install-debian-on-virtualbox/)

![debian instal](https://user-images.githubusercontent.com/45172166/215195058-d9f4b577-b8f5-4f40-b384-bc99ef43f83e.png)

![start installation](https://user-images.githubusercontent.com/45172166/215200016-f939cd82-2d5e-41aa-902a-0f3b0862af57.png)

![start installation](https://user-images.githubusercontent.com/45172166/215207156-2f4527fb-dc7a-4e0c-970d-4c3bd4c40b98.png)







