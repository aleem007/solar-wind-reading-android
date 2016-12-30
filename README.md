# solar-wind-reading-android
This project displays the values read from the solar/wind mill.
The values are read from a micro controller and passed through APIs.
The values are sent to the application in the following format.
{
  "voltage": "2",
  "current": "3",
  "power": "4",
  "energy": "5"
}

Since these are communicated over a local network we can consider and harcode the communication IP as "192.168.4.1"
The app recieves the json in the above format and we just need to use those values to display in the android app.
