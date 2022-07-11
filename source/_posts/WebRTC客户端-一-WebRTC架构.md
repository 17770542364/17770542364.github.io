---
title: WebRTC客户端(一) WebRTC架构
date: 2022-07-05 19:47:47
categories: 音视频
tags:
  - WebRTC
  - 音视频
---

## WebRTC整体架构

![image-20220616150935297](WebRTC客户端-一-WebRTC架构/image-20220616150935297.png)



## WebRTC目录结构

![image-20220616151953427](WebRTC客户端-一-WebRTC架构/image-20220616151953427.png)

![image-20220616152128809](WebRTC客户端-一-WebRTC架构/image-20220616152128809.png)



##  WebRTC Modules目录

![image-20220616152630603](WebRTC客户端-一-WebRTC架构/image-20220616152630603.png)

![image-20220616152810130](WebRTC客户端-一-WebRTC架构/image-20220616152810130.png)



## WebRTC运行机制

### 轨与流

- Track 轨 	各个轨之间保持平行
- MediaStream 流 每个流里面包括了多条轨

### WebRTC重要的类

- MediaStream
- RTCPeerConnection 
- RTCDataChannel 非音视频的数据通过这个类进行传输

### PeerConnection调用过程

![image-20220616160704314](WebRTC客户端-一-WebRTC架构/image-20220616160704314.png)

### 调用时序图

![image-20220616165550065](WebRTC客户端-一-WebRTC架构/image-20220616165550065.png)
