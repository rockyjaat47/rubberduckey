hello guy's Today i will show you what is USB Rubber duckey you know ,But it is definitely something more than that in fact its actually a keyboard that can also store some data I mean not too much data but enough of it so that it can do its job it's called a USB rubber ducky and it is produced and sold by hack 5 it has become quite populations the time it was featured on the TV show Mr robot it's an awesome series by the way and yes as you can obviously see it's not a usual keyboard there are no keys because this is a programmable device which means you can actually instruct it what keys to send when it is connected to a computer and it will automatically send the keys that are pre programmed inside it as soon as its connected to any device now what is its use case well it's actually designed for red teamers to do tasks like security auditing so basically when you plug this into a computer it gets recognised as a keyboard and the general nature of computers is that they trust keyboards because keyboards are the peripheral devices that humans generally used to communicate with the computer so it's a natural trait or a natural feature for any computer to trust a keyboard to support and trust a keyboard and USB rubber ducky exploits this since the keys that are to be sent are already programmed in this device it's going to automatically inject these keys as soon as it's connected to the computer and this can be used for a ton of things I mean there are countless things to exploit with this and you can even use it as an automation tool before going any further I would like to just make it very clear to you that this video is only for educational purpose all the experiments and demonstrations shown in this video are performed in a controlled lab environment if you want to get some hands on with the store you can try it on yourself but do not use it to get into other computers at least not without their consent it is an illegal activity it's a crime and you will be in trouble if you do so so be careful and be responsible for the way this works is you basically write a ducky script which is very easy to learn and understand so basically tell it what keys to press for example I'm reading a simple script that will hold control our to bring up the run menu and then type in notepad dot exe open notepad and then write the string hello world now I need to encode this taki script into a binary file and this can be done by making use of the ducky encoder web app hosted by hack file or you can even do it locally by using the key and core are using web app is easier because you don't have to download anything to your computer and I prefer that a binary file is named as inject dot pain so you place this binary file on the memory card of the rubber ducky and you can basically right to this memory card by just inserting it into a card reader now that I've copied the inject dot been into the memory card I will insert back the memory card into the rubber ducky now when you insert the duckie into a computer it does it's job and as you can see it opens up notepad and type hello world awesome now you get the idea of it the next experiment I'm going to do is I'm going to try to get a reverse shell from my target machine which is my laptop running Windows 10 to my computer which is also running Windows 10 so in this case my laptop is the target machine and my computer is the attacker machine or the hacker machine by getting a reverse shell to the target a hacker can basically do anything you can read files you can write files you can run new processes and all that so let's try it so there's this public GitHub repository of famous lucky scripts and payloads and there is a remote access script called reverse dekhe to I'm gonna use this script instead of writing one of my own so I just have to change the attackers IP and port so for the IP I'm gonna put in my Ng rock host name because its practical to be able to access the reverse shell from the Internet but if the target machine is on the same network I can just put in my local IP but just for demonstration I'm going to put in my Ng rock host name India which is actually tunnelled to my netcat listener perfect that's all I will need to change in the script now I'll just encode the script and then download the inject pin and now I'll simply move this into my lucky memory card alright let me now go ahead and plug in the USB rubber ducky into my laptop and let's see if it works so as you can see it did something it actually opened a hidden PowerShell window so that you can't see what it's typing but anyway it seems like it's done its job now let's check the listener on the attacker machine and there we go we now have a reverse shell so now I can access my laptop remotely from the attack of machine so I can read files write files run other programs download files remotely into my machine and basically do anything as the logged in user on my laptop it's like I'm having a remote connection to my laptop and I am able to do anything now sometimes the Windows Defender comes in the way and blocks whatever it is that you are trying to do for example if you're trying to spawn up a reverse shell the Windows Defender might actually block it because it's obviously malicious and it can be used by attackers to exploit your system so that's a good thing for the user but there is a way you can actually disable or turn off the Windows Defender by using the rubber duckie so there is this dagger script on the same public GitHub repo and using this you can actually disable or turn off the Windows Defender I'm going to try this script to turn off the Windows Defender on my laptop now I encoded the script and placed the binary in the duckie and I'm going to now and set it into my laptop and let's see what happens so as you can see it is making some changes to my registry and it swiftly disable the Windows Defender permanently which is really scary I mean the whole process only took about 25 to thirty seconds so all the hacker please to do is to get your attention to distract you for 30 seconds and boom your defender is turned off leaving your computer unprotected now the hacker can run any other malicious script using the same rubber duckie so obviously you can do a ton of things using the rubber duckie and it's just not practical to demonstrate all the use cases in this video is there are just countless exploits that you can build using the robber taki for example you can even download something from the Internet using the ducky script and then run the downloaded file for example lets say a metasploit payload and this adds more functionality and more creativity to your exploits for sure and one more thing is that you can even flash the firmware of USB rubber ducky and you can install you know other community provided firm its like for example there's this firmware called twin dock where in the rubber ducky connect both as a keyboard and as a storage device so I can basically save files like exploits on the rubber ducky itself so that they can be readily deployed by the taki script so the next time you are inserting a USB or any external device Inside computer think twice do you really trusted and definitely do not take any chances because you just saw how easy and how quick it is for hackers to take over your computers and steal your files another critical assets be safe so thanks for checking this repository I hope you like it if you did like do start it.

<img src="duckey.jpg">

### Dwonload Payload Files From This Link 🦖
<a href="https://drive.google.com/drive/folders/1Vmws-_yfzymV8ziBMM4rBs8z94u0uWER?usp=sharing"> Payloads Drive </a>

### Buy Form this link 
<a href="https://www.amazon.in/Hak5-Rubber-Ducky-Deluxe-Field/dp/B073VRKJ7P"> USB rubber ducky </a>

### this post only for educational purposes so use it be your own risk and responsibility
<h4> © copyright by Team Rocky and Git-Tool's community .. </h4>
