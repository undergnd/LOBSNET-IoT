![image](https://github.com/user-attachments/assets/587d87a7-f1d8-4d0f-8e17-7bcaac384c6b)


**Lobsnet IoT**

Lobsnet IoT is a set of devices and funcionalities able to support remote control of some environments. It can receive data from remote sensors, send commands to remote switches, fans, displays or even remotely control other computers. It can deliver message to remote location, far from Internet Access Point or work without the Internet.

**Security**

All wireless communication and protocols in the system are encrypted. Pairing procedure with encryption for BLE, secure ZigBee and LoRa, MQTT with TLS/SSL and WiFi with WPA2. If you want to control remote environment beeing separated from the Internet, this solution may support your case.

**Long Range and Short Range**

The beauty of Lobsnet IoT is a way how LoRa – long range communication can support remote world. Even with it’s low data transmission speed, in some cases it is the best way to pass messages or even control remote single board computer with Linux installed on it. For local connections system can talk with other devices using bluetooth low energy, ZigBee and WiFi.

**USB connection**

Apart from IoT functionality user can exchange data between machines (laptops, smatphones or others) via USB. Lobsnet bases are ready to be connected to any UART terminal instaled on the machine.

**IoT**

Playing with IoT was the main reason for development of the system. Among many solutions which are available on the market, some of them are free and relatively easy to work with. As an example the Zigbee2mqtt, system which is well known in a smart home world, has been chosen and the choice appeared to be probably the bes one. Interaction with the Internet bases on MQTT protocol and in particular a mosquitto broker installed on any VPS.

**Data transfer**

Well, there are many factors which justify why LoRa is used in the system, but it has some disadvantage – this is low data transmission speed. If every hour you need to pass couple of bytes for a distance of 50 kilometers or couple of tousends bytes for a distance of 5 kilometers LoRa is however great solution for it.


![image](https://github.com/user-attachments/assets/ecca9f42-50f1-4b7e-96b2-21ea8c2d5a87)


**Devices**

Some devices are build within the project development but there are also ones from the market to support project’s development.

**Lobsnet LoRa station**

- Long range LoRa encrypted link
- Secure connection over BLE or ZigBee
- USB Virtual COM Port
- Powered with 5V USB or 3.6 – 15V DC

**Lobsnet gateway**

- Connects Lobsnet LoRa base station to server
- WiFi connection to local server or Internet
- BLE secure connection to LoRa base station
- MQTT client with SSL
- Configuration via webpage
- Powered with USB

**Lobsnet sensor**

- BLE communication
- Accelerometer, temperature and humidity sensor
- Ultra low power consumption
- Powered with 3V Li Ion battery

**Zigbee2mqtt adapter**

- Custom board for RF-BM-2652P2
- Zstack firmware
- Fits to 40 pins SBC’s connectors (i.e. Raspberry Pi, Orange Pi, Banana Pi, Radxa Zero 3W)

**Single board computer with Zigbee2mqtt and mosquitto broker**

- Hosts zigbee2mqtt and mqtt broker
- Cheap, small, efficient and available
- Ready for automation aplications

**Example possible user cases**


**Greenhouse management**

![image](https://github.com/user-attachments/assets/379e96a5-73bf-4bfa-9981-257f6417a8a9)


**Wreless e-ink tagging system for warehouse**

![image](https://github.com/user-attachments/assets/a836fbf7-0989-455a-9115-fed0d4399c50)

**Long Range Remote LED display control**

![image](https://github.com/user-attachments/assets/2e0dea77-4b23-4abb-bcd4-5de90c031a7d)

**SmartHome systems extension**

![image](https://github.com/user-attachments/assets/e5aca9d1-228d-4592-84da-a6df67762582)

