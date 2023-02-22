# Shark on Wire
![image](https://user-images.githubusercontent.com/87900090/220533621-f2639fb3-4e8a-4648-9c82-5f3ea2a6db3e.png)

## Solution

1. Open the capture.pcap file in wireshark.
![image](https://user-images.githubusercontent.com/87900090/220534132-8c28d5b3-4b50-4fc6-8ea5-f42108d04165.png)

2. Open a random packet and started following udp streams similar to another challenge where we had to follow tcp streams.
3. As we keep on going through the streams, we can find the flag on stream 6.
 ![image](https://user-images.githubusercontent.com/87900090/220534404-81a9659b-14c2-4265-9ea8-c3b787d3feaa.png)
4. **picoCTF{StaT31355_636f6e6e}**
