# Penetration Testing.
##### This is bootcamp day01 in 1337 about penetration testing. You will find resources and a brief summary about what we did in the session.

## What is pentesting ?
Pentesting is the art of hacking machines(boxes). In general the action of getting access to a user in a machine is called penetration testing.
The reason of pentesting is trying to find vulnerabilities that could affect the system. Then you patch them to protect it.
### Steps of pentesting
We can divide pentesting into 3 magors part.
#### Basic Enumeration.
Enumeration is the most improtant part in pentesting. And you don't use just as a 1st step but you will need at every moment. But for the sake of dividing this domaine we put it here as a step.
Enumeration is simply knowing where to look and what to look for so that you get improtant informations about the system, maybe files... There are a lot of scripts that help you through this. The first one you use everytime when you try to pentest is NMAP. A simple powerful tool that gives you information about port opened on the server, what services are running on those ports, what versions, the operating system... And lot more.

#### User Access.
After the enumeration you might find valuable informations that can get you access to a user on the system.

#### Privilege Escalation.
After getting the user access you're only next step is to try and get the root access. Becoming root on the system is and will always be your ultimate goal.
In this as well there are many tools that will help you do it. We'll check them out later on.

## Resources.
Here are some links that can help you learn and practice pentesting.
Platforms:

```
https://www.hackthebox.com      - Platform filled with challenges and boxes to hack and learn from. A bit hard for beginners.
https://tryhackme.com           - Perfect platform to start your journey and hack your first box.
https://online.pwntilldawn.com  - Similar to hackthebox so I wouldn't recommend it for new comers.
```

Youtube Videos:

```
IppSec : Creator of many boxes in hackthebox. Does writeups for retired machines in details. Best hackthebox channel out there.
          https://www.youtube.com/channel/UCa6eh7gCkpPo5XXUDfygQQA
          
NetworkChuck : I think you've already crossed this guy, He is super famous for his tutorial videos. Not just pentesting but all kind of cyber security content.
          https://www.youtube.com/user/NetworkChuck
```

This is the basics of pentesting. And these resources are enough to launch your journey towrads hacking your very first machine.
I invite you to go ahead and start discovering these platforms.
