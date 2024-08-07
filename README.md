Lobsnet IoT

Lobsnet IoT is a set of devices and funcionalities able to support remote control of some environments. It can receive data from remote sensors, send commands to remote switches, fans, displays or even remotely control other computers. It can deliver message to remote location, far from Internet Access Point or work without the Internet.

Security

All wireless communication and protocols in the system are encrypted. Pairing procedure with encryption for BLE, secure ZigBee and LoRa, MQTT with TLS/SSL and WiFi with WPA2. If you want to control remote environment beeing separated from the Internet, this solution may support your case.

Long Range and Short Range

The beauty of Lobsnet IoT is a way how LoRa – long range communication can support remote world. Even with it’s low data transmission speed, in some cases it is the best way to pass messages or even control remote single board computer with Linux installed on it. For local connections system can talk with other devices using bluetooth low energy, ZigBee and WiFi.

USB connection

Apart from IoT functionality user can exchange data between machines (laptops, smatphones or others) via USB. Lobsnet bases are ready to be connected to any UART terminal instaled on the machine.

IoT

Playing with IoT was the main reason for development of the system. Among many solutions which are available on the market, some of them are free and relatively easy to work with. As an example the Zigbee2mqtt, system which is well known in a smart home world, has been chosen and the choice appeared to be probably the bes one. Interaction with the Internet bases on MQTT protocol and in particular a mosquitto broker installed on any VPS.

Data transfer

Well, there are many factors which justify why LoRa is used in the system, but it has some disadvantage – this is low data transmission speed. If every hour you need to pass couple of bytes for a distance of 50 kilometers or couple of tousends bytes for a distance of 5 kilometers LoRa is however great solution for it.

