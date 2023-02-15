# Homemade-Helium-Miner-Node
Homemade Kind of LoRaWAN Router &amp; Helium Node Miner

DIY Alpha Program Early Adoption
The ability to mine HNT with a 3rd party gateway is currently under development following the conclusion of the DIY Alpha program. Please join the Helium Discord Server and the #hotspot-diy-hardware channel for the latest updates on the roadmap here.


![1](https://raw.githubusercontent.com/antennaitalia/Homemade-Helium-Miner-Node/main/ss1.jpg?raw=true)
![1](https://raw.githubusercontent.com/antennaitalia/Homemade-Helium-Miner-Node/main/helium-builds.jpg?raw=true)
![1](https://raw.githubusercontent.com/antennaitalia/Homemade-Helium-Miner-Node/main/lora1.png?raw=true)
![1](https://raw.githubusercontent.com/antennaitalia/Homemade-Helium-Miner-Node/main/lora2.png?raw=true)
![1](https://raw.githubusercontent.com/antennaitalia/Homemade-Helium-Miner-Node/main/lora3.png?raw=true)


The Helium Hotspot is the combination LoRaWAN router and Helium blockchain miner. If you don’t have one, you can buy one here. And if you want to build your own, you absolutely should.

The figure below summarizes the basic building blocks of the RAK Hotspot Miner. The RAK2287 is an essential part of it as it provides all LoRaWAN connectivity. It receives and transmits LoRa Frames and takes care of modulating/demodulating the signals among others. The processing of the LoRa Frames as well as higher-level protocol related tasks are done by the embedded host system (Raspberry Pi). Received and processed LoRa Frames are being sent to a LoRaWAN Server.
