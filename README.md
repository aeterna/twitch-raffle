Twitch Raffle
-------------
Twitch Raffle is a tool that was designed to help streamers manage raffles or giveaways within their
own Twitch chat without the hassle of dealing with the laggy chat environment that comes along with it.

Website: http://ieztech.net/~aeterna/twitch-raffle/


Developers Notice
-----------------
Twitch Raffle will always be free to download and ad-free - donations are greatly appreciated and can be
sent to rbodnar93@gmail.com on PayPal if you choose to do so. Thank you :)

Twitch Raffle is relatively new and was tested on multiple chats during different traffic levels,
meaning that it was extensively tested during both low and high volumes of chat messages. No
issues were found, but if you are to come across something not working properly, please submit
a bug report via the Help menu within the program.


Requirements
------------
As this program was built using Java, JRE 7 (Java Runtime Enviornment) or later is required.

	You can download Java here: https://www.java.com/en/download/


Running Twitch Raffle
---------------------
You should be able to double click on the Twitch Raffle jar file. If you are prompted to select
a program to open the jar with, choose your Java JRE. If nothing happens, please create a shortcut.

You can create a shortcut to run the program by adding the following to a batch or shell script.

(Windows) http://www.wikihow.com/Write-a-Batch-File
(Mac & Linux) http://www.linfo.org/create_shell_1.html

The commands:
(replace home_directory with the path to your user directory - usually C:\Users\user_name\)
		
	Windows:
		javaw -classpath home_directory/lib/*;home_directory/raffle-bot.jar org.aeternaly.raffle.Main
			
	Linux/Mac:
		javaw -classpath home_directory/lib/*:home_directory/raffle-bot.jar org.aeternaly.raffle.Main


Help
----
If you are having issues please check the FAQ (http://ieztech.net/~aeterna/twitch-raffle-faq/) for an answer.
You can also contact us via email (support@aeterna.com) or the Contact Form provided in the program under the Help menu
if the FAQ was unable to solve your issue. Please be as descriptive as possible whichever way you decide to contact me.


License
-------
Twitch Raffle is released under the GNU General Public License, with the exception of the files listed below.


External Dependencies
---------------------
* PircBot [lib/pircbot.jar] - http://www.jibble.org/pircbot.php

* JavaMail API [lib/mail.jar] - http://www.oracle.com/technetwork/java/javamail/index.html