# Tüm Türklere Sesleniyorum!
Bazı kişilere bu github sayfasını veriyorum ama hiç bir şey anlamıyolar(İngilizce yazdığım için)
O yüzden vereceğim bir çeviri sitesi linkinden bu yazıları kopyalayıp çeviriye yapıştırın
Link: https://translate.google.com/?hl=tr&sl=auto&tl=tr&op=translate


# All the free hosting's that i know:
 # Silly Development: https://sillydevelopment.co.uk (I Prefer It!)
 ## Bot Hosting: https://bot-hosting.net (Credit system, but not getting suspended everytime if you have enough coins!)
 ### PylexNodes: https://pylexnodes.net (I Prefer It!)

# Brawl-Stars-Server-With-Hosting
In this tutorial i showed u how to create your own private brawl stars server in 7 steps, i hope that helped!

What u need for this page: MT Manager(for apk extract), zip maker(can be done by ZArchiver), Hosting(gonna give it later)
# 1. Getting the zip and apk
https://t.me/AllModsBrawlStars
Get the zip and apk from here, they have what u want

# 2. Getting the hosting
look up for the hostings that i listed up there

# 3 Creating a server
when u on the site, click to the 3 lines and click earn credits and get 10 credits(its free + this is for bot hosting site, if u selected the other 2 websites figure it out yourself)

# 3.1 Opening the server
To open the server, click on 3 lines again and click "Create Server"
on there there would be name thing do it whatever you want
and for the server languege do it python
after that click on "View on control panel"
and wait the "running imstaller" text go gone
(For bot hosting site again)

# 4 File Replacement
Now click on files
and click "Upload" Button
upload the server zip u got
extract the zip
and delete the zip after extracting

# 5 Getting the port
now go back to console
you will see something called "Address" on bottom of the output(console)
click to the "address" and it will copy something
after the ":" symbol there would be numbers
copy those numbers, we will need it later

### Example
:12342

# 5.1 Setting up the port
Now go to the files page and click on "main.py" file
scroll all the way down on the code
you will see something like '0.0.0.0', 9339
now delete that 9339 and put the port u just copied it(this will run the server on hosting)
and after that click save content(the blue button) to save the file

# 6 Setting up the run file
Go to the startup page
scroll down until you see "bot py file"
now delete that bot.py and change it to "main.py"
and bottom of that, you will see additional python packages
type on that box this:
colorama tinydb

## Or if you use sql server do this:
### colorama tinydb mongo pymongo schedule

## This installs the other packages

and leave that page

# 7 Putting the port on apk
Now, go to the mt manager
scroll to the right on the right side
and click apk extract(something like that)
and select the apk u got
and extract it
after that, go to the your brawl stars apk file
click "lib" folder
and click the folder named "armeabi-v7a"
go to the libgg.config.mod (or the file that says config) thing like click on the one who says config idk
put this ln redirectHost:
65.108.77.37 (this ip is for bot hosting, in silly development your got your own server ip
and in redirectPort, put your own port

## If you do not have redirectPort, its probably because you can only host it on pyroid 3

## If you not saw the config thing, you probably downloaded the not self hosted version

## NOTE! No, you dont gonna put "65.108.77.37" if you using silly development (pylexnodes got their own ip thing)

# 7.1.Other Node IPs
Nodes IPs & Informations
- de1: `167.235.13.16` ( Germany ) de1.bot-hosting.net
- de2: `138.201.21.189` ( Germany ) de2.bot-hosting.net
- de3: `157.90.181.183` ( Germany ) de3.bot-hosting.net
- fi1: `95.216.39.179` ( Finland ) fi1.bot-hosting.net
- fi2: `95.216.10.105` ( Finland ) fi2.bot-hosting.net
- fi3: `65.108.103.151` ( Finland ) fi3.bot-hosting.net
- fi4 `65.21.202.154` ( Finland ) fi4.bot-hosting.net
- fi5 `65.108.3.108` ( Finland ) fi5.bot-hosting.net
- fi6 `65.108.77.37` ( Finland ) fi6.bot-hosting.net
- us1: `103.60.13.254` (United States - Premium Node) us1.bot-hosting.net
- us2: `172.81.128.14` (United States - Premium Node) us2.bot-hosting.net

- (btw you get your own ip like if the number is like 3 and fi (i mean fi3) you get the fi3 ip i already showed on the list)

save the file
now go back to the hosting
Click to the start button to start the server

And enjoy your game :)

 ## have something to ask? my discord is: batus_zz

