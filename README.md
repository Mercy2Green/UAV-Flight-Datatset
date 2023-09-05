# UAV-Flight-Datatset
 
We built three quadrotor UAVs with different weights, sizes, and computing capabilities to conduct experiments and collect real-world flight data. Figures 1, 2, 3, and 4 lists the drone we assembled and the location we conducted the experiments. We conducted flight tests and collected multiple batches of flight data from all three drones. Table 1 shows the configuration information of these UAVs.

<center>

<div>TABLE 1: UAVs configuration.</div>

| **UAV type**               | Heavy            | Medium            | Light    |
|-------------------------------------|------------------------------------|-----------|----------|
| **Firmware**               | PX4              | PX4               | PX4      |
| **Airframe**               | ZD550            | F450              | GEP-CL30 |
| **FC**                     | PixHawk 2.4.8    | PixHawk 2.4.8     | PixHawk 2.4.8|
| **OC**                     | Intel NUC        | Raspberry pi 4B+  | Raspberry pi Zero |
| **OS**                     | Ubuntu 22.04     | Raspbian 64 bit   | Raspbian 32 bit |
| **CPU**                    | i5-1135G7        | BCM2711B0         | BCM2835  |
| **Frequency**              | 4.2GHz           | 1.5GHz            | 1.0GHz   |
| **Mermory**                | 8GB              | 4GB               | 512MB    |
| **Power**                  | 16.0V 6A         | 5V 2A             | 5V 2A    |
| **Battery**                | 6S 30C 5300mAh   | 4S 30C 2200mAh    | 3S 85C 850mAh|
| **GPRS**                   | GPS Wi-Fi        | GPS Wi-Fi         | Wi-Fi    |
| **Weight**                 | 3KG              | 1.7KG             | 0.6KG    |

</center>


This dataset contains 12 sets of real-world flight data. We respectively utilized QGroundControl planning and manual control to carry out flight experiments. We also utilized the communication program based on Mavlink to record the UAV sensor data in real time. 


<center>
    <img src=./Figure/light.jpg>
    <div>Fig. 1 Light model.</div>
</center>

<center>
    <img src=./Figure/medium.jpg>
    <div>Fig. 2 Medium model.</div>
</center>

<center>
    <img src=./Figure/heavy.jpg>
    <div>Fig. 3 Heavy model.</div>
</center>

<center>
    <img src=./Figure/exp_location.png>
    <div>Fig. 4 Experimental location.</div>
</center>


