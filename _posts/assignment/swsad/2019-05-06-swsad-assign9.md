---
layout: post
title: 简单web服务搭建-GraphQL框架-项目介绍
categories: Simplewebserver
description: 对GraphQL框架的服务端开发部分项目的介绍
keywords: GraphQL,SimpleWebServer
---

1.make reservation 领域建模  
![image1](/images/posts/UMLet/assign9/p1.png)

2.payment领域建模  
![image1](/images/posts/UMLet/assign9/p2.png)
约束：  
#Hotel (ID/PrimeryKey, LocationID/ForeignKey, Name, Address, Star)  
Room (ID/PrimeryKey, Type, Price, IsAvailable)  
Travelers (ID/PrimeryKey, Name, Email)  
Reservation (ID/PrimeryKey, TravelerID/ForeignKey, HotelID/ForeignKey
, Date, Time, CheckInDate, CheckOutDate, AdultNum, ChildNum, ChildAge)  
Payment (ID/PrimeryKey, ReservationID/ForeignKey, Date, Time, Total)  
CreditCard (ID/PrimeryKey, TravelerID/ForeignKey, PaymentID/ForeignKey, Number, SecurityCode, ExpiryDate)  
3.生命周期：  
![image1](/images/posts/UMLet/assign9/p3.png)

