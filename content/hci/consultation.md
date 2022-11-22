---
title: "Consultation"
date: 2022-11-22T16:03:33Z
---

We consulted with our clients to try and get an idea for what would be required of the project.
We interviewed both a developer and the chief information officer in a semi-structured format.
This was recommended by a textbook [1] as it would bring up issues that we had not considered.
This turned out to be very beneficial.


## Interview with a CIO
**How do you currently assess the carbon impact of your software? Does any software exist?**


Currently, it is a manual exercise and has to be done by a software by software with each team assessing it themselves.​

**What are your priorities when assessing the carbon impact of your software stack?**


3 main factors affect the carbon impact. Firstly, the kind of electricity that data centers use, which I do not have much say in. Second, is the footprint of manufacturing the hardware used, which we call embodied carbon. Every server has an LCA number and an expected lifetime, which we know. Finally, the energy usage of the software, is where we can make the biggest impact. I’d like to get our developers to adopt better patterns and practices, but to do this, first, we need to be able to assess which applications are using a lot of energy and why.​

**What would your general process be when assessing the carbon impact?​**


We do not have a standard way to assess it. I have to ask the team that makes the application to calculate it themselves. ​

**What issues does this raise?​**


It’s difficult to deal with different teams who code in different languages and then provide the code in different formats. I want to receive it in a standardised format.


## Interview with a developer
**Have you ever considered carbon impact when developing software? Why or why not?​**


No. I don’t know what to look for so how could I consider it? I would need the appropriate tools and how to use them.​

**What would make an SDK to test carbon impact pleasant to work with or integrate?​**


The ease of implementation is crucial. For that, I need good instructions and quality documentation. In my team, I use Python, so I would want to have native libraries in Python. I need to know exactly what to expect the output to be. Also, use universal standards across the SDK and common data formats, so that I could use other libraries to process the data. I would want a dashboard so I can see whether the code I write makes an effect on the performance of the software.​

**What would you want out of the dashboard?​**


The dashboard should display detailed performance statistics. If I'm writing a program that runs multiple threads concurrently, I want to make sure that all the cores of the CPU are used evenly. If there are individual emissions for each component, I can prioritise which to conserve.​

**Are there any specific features you want in the library?​**


I want function decorators that I could implement to specifically measure the performance load of each function over time. This would make optimising easier as I would know exactly where I should start.




***
*References*


[1] Helen Sharp, Jennifer Preece, Yvonne Rogers. Interaction Design : Beyond Human-Computer Interaction [Internet]. Vol. Fifth edition. Indianapolis, IN: Wiley; 2019 [cited 2022 Nov 15].