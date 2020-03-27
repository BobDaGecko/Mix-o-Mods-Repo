## How to start a Mix o' Mods 2.0 Server
Go to the files section on the Curse page to find the server files. Make sure the file version is the same. If there are no server files available do not download older files and create an issue on the github repository and I will get new server files up as soon as I can.  

The ATM Team has made special server scripts to make running a modded server very easy and light on performance. To edit server settings go to the settings.cfg file. The ScriptsInfo.md file will tell you about the different settings.

## Note on World Generation
A server that generates the world for the first time will be very slow. To alleviate this use Speiger's Chunk Pregenerator mod which is already installed. To use this open the client version of the modpack and create a new world. Name the world "world" so the server will recognize it. Once all of your settings are set select preview. Then enter your seed. Select how many chunks you want to generate (I suggest @ least 100 chunks). Click the button that says "Terrain" so it should say "Terrain & Post" then click "Generate." Once you have the world move the world to your server folder and run the server.

## How to Share the Server with Friends
Most people use a method called port-fowarding but this is tedious and gives out your ip address. I have found a much easier and secure method to providing access to the server using an application called ngrok. Here is an simple tutorial:  
[How to make a Minecraft Server! NO PORT FORWARDING NO HAMACHI](https://www.youtube.com/watch?v=jLPdmTnZ_nM&list=PLUwylfNEVQCwmb1hnLCwFUx8nIj4AIQ1E&index=13)
