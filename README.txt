step 1, 2, 4 is for raspberry pi
1.
clone git repo
2.
sudo apt-get update && sudo apt-get upgrade

sudo apt-get install python-pip python-flask

sudo pip install -r requirements.txt

3.** in arduino IDE **
install esp8266
install pubsub client
connect LEDs from the diagram
upload "mqtt-esp8266.ino" to the board

4. 
sudo python app.py

5.open 192.168.1.x:8181

6.control the led from web-server

ref:
https://randomnerdtutorials.com/raspberry-pi-publishing-mqtt-messages-to-esp8266/