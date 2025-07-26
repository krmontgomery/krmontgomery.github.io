---
layout: post
title: "What is EDI from an EDI Professional"
description: Explaination on what EDI is and how it affects our lives.
date: 2025-07-23 09:08:30
categories: [EDI, Transportation]
tags:
  - EDI
  - X12
  - Transportation
  - Informative
---

![Alt text](/assets/images/EDI-Dark-Theme.png)
<br>
<br>

&nbsp;&nbsp;&nbsp;&nbsp;Back in 2018, during my internship, I couldn't have told you what EDI stood for, the need for it, or why it's crucial in so many industry sectors. An analogy was shared with me when I was first introduced to EDI; It's similar to ordering products from Amazon. You get updates confirming your order, a notification that your payment went through, and notifications for delivery updates.

&nbsp;&nbsp;&nbsp;&nbsp;EDI—Electronic Data Interchange. Words that might have you glazed over and hovering the "Skip Ad" if it were an advertisement on YouTube; honestly, I wouldn't fault you either. Behind the dull phrasing of words really is something that impacts all of us, yet most of us have never heard of it or know what it is.

&nbsp;&nbsp;&nbsp;&nbsp;Think about the last time you picked up groceries, or when you’ve waited for a package to hit your doorstep. What you probably don’t see or even know about, is the digital handshake happening in the background. More often than not, EDI is quietly keeping things moving. Companies like Walmart, Kohl's, Guitar Center, and Tractor Supply use it to track stock, share schedules, and converse back and forth with carriers to line up pickups and deliveries. This happens without anyone picking up a phone or writing anything down on paper.

![Alt text](/assets/images/Transactions.png)

&nbsp;&nbsp;&nbsp;&nbsp;In Transportation, EDI revolves around five primary transaction sets. These transaction sets would be 204, 990, 214, 210, and 997. A carrier receives a load from a customer via EDI using the 204 (EDI Load Tender) transaction set. The 204 gives pertinent information about the load, as well as dates and times of when the load should be picked up and delivered. This goes even further, where the purpose of a 204 could be to cancel the original 204 or change information about the original 204. Once a carrier has accepted a load tender, a 990 will then be sent back to the customer to notify them that the load offer was accepted. 990s are generally the more benign of the transaction sets.

&nbsp;&nbsp;&nbsp;&nbsp;Returning to the Amazon analogy. EDI 214s are the shipment tracking updates. Whether a driver is dispatched, in-transit, at the pickup/dropoff location, a 214 is sent to the customer to communicate that milestone. These updates can be supplemented or entirely replaced by third-party supply chain visibility platforms like FourKites, Macropoint, and Project 44, to name a few. I’ll dig into those in a future post.

&nbsp;&nbsp;&nbsp;&nbsp;The EDI 210 covers freight billing; aside from the 214, 210s are usually more complex. Handling 210s can involve custom requirements and intensive programming. Due to the challenges and cost of having an in-house solution for handling freight bills. Customers may turn to intermediaries like Syncada, Intelligent Audit, or Cass.

&nbsp;&nbsp;&nbsp;&nbsp;Finally, there’s the humble EDI 997, Functional Acknowledgement. It really only has 2 simple purposes: to acknowledge a received EDI transmission, and to let the sender of the transmission know if there were any errors in their transmission.

&nbsp;&nbsp;&nbsp;&nbsp;EDI may sound like background noise or corporate chatter, but it’s actually an unsung hero of modern-day transportation. It keeps the gears turning quietly, reliably, and comfortably in the background. So next time you buy your groceries or your Amazon shipment arrives on time, thank the EDI.