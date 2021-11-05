## Tracking Any Device Using  Seeker In Kali Linux

**1.Open Your Kali Linux Terminal**
<br>
Clone into Seeker
<br>

```
git clone https://github.com/thewhiteh4t/seeker
``` 

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1636105887852/pc3ceRCXD.png)
<br>
After cloning is finished we need to go in seeker's directory, to do that and to see the files we use 
```
cd
```
 command and ls command so we apply both commands together:

```
cd seeker && ls
``` 

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1636106031112/esQWT3SKR.png)

Install all the requirements required to run seeker

```
sudo bash install.sh
``` 

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1636106132547/XsjdqzDuD.png)
 Run seeker

```
python3 seeker.py
``` 

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1636106224712/HVPEujRfi.png)

Create a Listener Port
<br>
Install Ngrok
<br>
Ngrok is a cross-platform application that exposes local server ports to the Internet.
(Open A new Tab)

```
wget curl -s https://ngrok.com/download | grep -o -E 'https://bin.equinox.io/c/[A-Za-z0-9]{4,}/ngrok-stable-linux-amd64.zip
``` 
unzip ngrok-stable-linux-amd64.zip install it
```
chmod +x ./ngrok ./ngrok -h
``` 
Set Listener to port 8080 after running Ngrok

**IN SEEKER:**
From the Given Options select the google drive method to create a link:

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1636106698157/bRENtWjyA.png)
Now we can send this link to the victim. When the victim opens this link he/she can see the Google drive page and that page will prompt the victim for location information. If he/she "Allow" this we got all the location information.
<br>
**Whatsapp Group Invite Method
**
Same things we can do with the Whatsapp method for this we need to choose option 2. After this, we need to choose a group title and we need to give an image. The image should be relatable to the group's title. We can use any image file but 300x300 images will look better. We have to give our image path or we can drag and drop our image in the terminal to auto-fill the path of our image.


![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1636106906149/i4gVvPLwY.png)
**Getting the Location**
Whenever target clicks on the attacker's shared link and try to any activity this asks for location permission. If the victim clicks "Allow" we got the victim's location.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1636106968796/_wmXUU-9k.png)
Now we just copy the Whatsapp group invitation link and send it to the victim. We shouldn't worry because this will be a fake webpage exactly like the Whatsapp group invitation. The victim will try to connect and we got the location and device info. The victim always gets group full notification.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1636107023763/358FK8_2u.png)

**Extra Social Engineering**
Now we can send this link to our target but there will minimum chance that our target will click on the link. So we need to do some extra Social Engineering. Suppose we know that our target is jobless and he needs some money also target loves to make new friends. In this case we firstly shorten this long URL with bit.ly or any other URL shortener which opens the link directly.
(IN MY NEXT POST)















