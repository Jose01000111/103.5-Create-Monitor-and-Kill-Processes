# 🧪 103.5 – Create, Monitor, and Kill Processes

## ✅ What I Did in This Lab
I broke down the lab into five parts based on the key knowledge areas of the LPIC-1 objective. I practiced both interactive and scripted use of commands like ps, kill, bg, fg, watch, tmux, and more. Each section helped me understand real-world process control and monitoring in Linux.

I’ve included some helpful links to guide you through the lab and for studying afterward:

[EXAM OBJECTIVE 103.5](https://www.lpi.org/our-certifications/exam-101-102-objectives/#103.5_Create.2C_monitor_and_kill_processes)

[OBJ. 103.5 NOTES](https://1drv.ms/w/c/354f1c8d534fbced/EVNQbpIqz89GnpwHXZc3uLgBo_domUfRa0YQeqmP0JfjyQ?e=zeiH2L)

[OBJ. 103.5 LAB](https://1drv.ms/w/c/354f1c8d534fbced/EbnLsV43-aNKqk6yZ9WtXIIB_YNe_CEw5iWSffDD-5HKIg?e=oicGqo)

---

## 1️⃣ Run Jobs in the Foreground and Background

🔹Create a background job

![JQWwqNb](https://github.com/user-attachments/assets/d01c6cea-cdb9-42bb-bee2-e8e5631685aa)

🔹View background jobs

🔹Bring a background job to the foreground

🔹Suspend a foreground job with Ctrl+Z and resume in background

![L76WEf1](https://github.com/user-attachments/assets/c12e6bba-8530-40e2-b241-5eee045224dd)

## 2️⃣ Signal a Program to Continue After Logout

🔹Run a command with nohup

![sAM6SwD](https://github.com/user-attachments/assets/cd2d6049-6599-4588-8892-2148f2eae712)

🔹Verify it’s still running after logout (simulate with exit and re-login)

![iE7eDCB](https://github.com/user-attachments/assets/6c8797b0-a373-41a9-a363-917cc0f0fbbc)

![HWkGsRH](https://github.com/user-attachments/assets/19b6a28a-f0b9-4e18-95ee-893202d886b5)

## 3️⃣ Monitor Active Processes

🔹Use ps to view all processes

![jNoQLU4](https://github.com/user-attachments/assets/f48aff02-1467-4c2b-aed1-3e2698b5cd48)

🔹Use top to interactively monitor

![3hx10tC](https://github.com/user-attachments/assets/fa353f6b-de66-4adf-84c0-87c293d4e11f)

🔹Use free to check RAM usage

![X74gpkP](https://github.com/user-attachments/assets/69187cad-19c6-498e-8d00-6615ddd5bbcb)

🔹Use uptime to check system load

![99G4L30](https://github.com/user-attachments/assets/f83a3729-2d96-4061-8efb-29199101fd06)

🔹Use watch to refresh a command

![SlQFTQf](https://github.com/user-attachments/assets/8df88927-760a-4e41-983f-50a8089206b6)

## 4️⃣ Select and Sort Processes for Display

🔹Use ps with --sort

![g33W3OR](https://github.com/user-attachments/assets/810ae07d-f4eb-4123-9226-68cb82eceb61)

🔹Use pgrep to search by name

![hzOw1d5](https://github.com/user-attachments/assets/bcb521a8-f609-49a2-a282-fcc07e039d15)

🔹Use top and sort by CPU or memory (P or M key inside top)


## 5️⃣ Send Signals to Processes

🔹Find process ID

![YYwsLH1](https://github.com/user-attachments/assets/a83efd54-1c9f-48b1-a857-5a2a4a52b632)

🔹Send SIGTERM to a process

🔹Send SIGKILL if necessary

🔹Kill all of a type

🔹Use pkill by name

![posLRw5](https://github.com/user-attachments/assets/810202ef-e176-456d-addb-a6e4b7b4f258)

## 🎓 What I Learned
This lab helped me understand the lifecycle of Linux processes and how to control them using the command line. I now feel confident managing foreground and background jobs, terminating stuck processes, and using monitoring tools like top and ps to keep systems healthy. These are skills I’ll regularly use in both cybersecurity and administration roles. 🧠
