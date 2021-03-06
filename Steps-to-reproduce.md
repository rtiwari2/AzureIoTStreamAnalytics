#### Steps to reproduce

- Setup **``IoT Hub``**

![](images/1.png)

![](images/2.png)

![](images/3.png)

![](images/4.png)

![](images/5.png)

![](images/6.png)

![](images/7.png)

- Setup **``local developer``** environment

```sh
sudo apt-get install nodejs npm
node -v
npm -v
```

![](images/8.png)

![](images/9.png)

![](images/10.png)

![](images/11.png)

![](images/12.png)

- **``Creating device``**

![](images/13.png)

```sh
npm init
npm install azure-iothub --save
node CreateDeviceIdentity.js
```

![](images/14.png)

![](images/15.png)

![](images/16.png)

![](images/17.png)

![](images/18.png)

- **``Read IoT device logs``**

![](images/19.png)

```sh
npm init
npm install azure-event-hubs --save
```

![](images/20.png)

![](images/21.png)

![](images/22.png)

- **``Simulate IoT device``**

![](images/23.png)

```sh
npm init
npm install azure-iot-device azure-iot-device-mqtt
```

![](images/24.png)

![](images/25.png)

![](images/26.png)

- **``Project stricture``**

```sh
tree -L 2
```

![](images/27.png)

```sh
node SimulatedDevice.js
node ReadDeviceToCloudMessages.js
```

- **``Test Run``**

![](images/28.png)

- **``Stream Analytics``**

![](images/29.png)

![](images/30.png)

![](images/31.png)

![](images/32.png)

![](images/33.png)

![](images/34.png)

- **``Storage Creation``**

![](images/35.png)

![](images/36.png)

![](images/37.png)

![](images/38.png)

![](images/39.png)

![](images/40.png)

![](images/41.png)

![](images/42.png)

![](images/43.png)

![](images/44.png)

![](images/45.png)

![](images/46.png)

![](images/47.png)

![](images/48.png)

```sql
SELECT
    *
INTO
    rawiotout
FROM
    iotrawin
```

![](images/49.png)

- ``Demo``

![](images/50.png)

![](images/51.png)

![](images/52.png)

![](images/53.png)

![](images/54.png)

![](images/55.png)

![](images/56.png)

![](images/57.png)

![](images/58.png)

![](images/59.png)

![](images/60.png)

![](images/61.png)