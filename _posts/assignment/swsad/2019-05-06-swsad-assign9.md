---
layout: post
title: 系统分析与设计第9周作业
categories: assignment
description: 系统分析与设计第9周作业
keywords: design,assignment,analyse
---

# 1.make reservation 领域建模  
![image1](/images/posts/UMLet/assign9/p1.png)

# 2.payment领域建模  
![image1](/images/posts/UMLet/assign9/p2.png)
### 约束：  
+ Hotel (ID/PrimeryKey, LocationID/ForeignKey, Name, Address, Star)  
+ Room (ID/PrimeryKey, Type, Price, IsAvailable)  
+ Travelers (ID/PrimeryKey, Name, Email)  
+ Reservation (ID/PrimeryKey, TravelerID/ForeignKey, HotelID/ForeignKey
, Date, Time, CheckInDate, CheckOutDate, AdultNum, ChildNum, ChildAge)  
+ Payment (ID/PrimeryKey, ReservationID/ForeignKey, Date, Time, Total)  
+ CreditCard (ID/PrimeryKey, TravelerID/ForeignKey, PaymentID/ForeignKey, Number, SecurityCode, ExpiryDate)  

# 3.生命周期：  
![image1](/images/posts/UMLet/assign9/p3.png)

