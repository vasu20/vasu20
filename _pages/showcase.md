---
layout: minimal 
title: "Creation examples"
permalink: /showcase-vasu-9360q/    
robots: noindex              
nav_exclude: true       
---


# Mirage Geospatial (at Percipient.ai)

### Problem 
Geospatial imagery analysts working for the US and international governments are inundated with large volumes of satellite imagery data, and are unable to keep up with emerging threats and developments reflected in the data. Especially in the US, they are stuck with legacy processes and tools built by defense contractors that are barely effective. 

### Solution: 
At Percipient.ai, I have envisioned and led the technical development of Mirage Geospatial since 2018, creating an MVP within three months and continuing to evolve it with the latest in AI, product insights, and user feedback. I infused the product with learnings from my earlier experience supporting hundreds of map editors and computer vision operators at Microsoft and Uber.
**Highlights:**
- **Search by Example**: Analysts can find visually similar objects using a single image. This one-shot detection is powered by a proprietary large foundation model and computer vision pipelines that learn new object types without retraining.
- **Self-improving AI**:  The models self-improve purely with analyst interactions. 
- **Anomaly alerts**: Analysts receive early warnings about subtle or unusual activity patterns in regions of interest.
- **Fast and scalable**: The system delivers insights within 5 minutes of imagery capture, while scaling both inference and training.
- **Modern UX**: Allows analysts to understand a region over time, spot subtle trends, collaborate, create a repository for their intelligence gatherings, and feed that back to Mirage’s AI.

### Impact 
Mirage Geospatial became Percipient’s first revenue-generating product, with several million dollars in sales to date. It has received high praise from analysts for its usability, mission effectiveness, and speed. The work is covered by two patent applications nearing award: 
- [**Product level patent**](https://patents.google.com/patent/CA3164893A1/en?inventor=Vasudev+Parameswaran&oq=Vasudev+Parameswaran&sort=new) covering system design and workflow.
- [**One-Shot “Search by Example”**](https://patents.google.com/patent/US20250232560A1/en?inventor=Vasudev+Parameswaran&oq=Vasudev+Parameswaran&sort=new) patent.


# Driver ETA Improvement (at Uber)

### Problem
ETA error is one of the most critical metrics for Uber’s business. Every minute of error reduction on average results in huge savings for the company via fewer canceled rides, better driver/rider matching, increased customer satisfaction, etc. When I had joined Uber in 2015, the existing ETA prediction system relied on “road segment speed profiles”, which were statistical averages of speeds of each road segment along a route for a given time of day. 

### Solution
Soon after I joined Uber, I conceived and prototyped Uber’s first ML based ETA refinement pipeline. Exploring an intuition that incidental parameters of an Uber ride such as time of day, number of traffic lights/stop signs on the way, etc could impact the ETA, I created an ML model to learn an error term on top of the route-predicted ETA. I transitioned my prototype to the Logistics team who productized it. 


### Impact
The ETA error was provably reduced by an average of 20% across cities. The system currently in place at Uber for this ETA improvement methodology is called DeepETA, and although completely revamped, still retains my core formulation of ETA error reduction as an ML problem ten years ago. My original innovation is covered by the following granted patent:

- [**Determining adjusted trip duration using route features**](https://patents.google.com/patent/US10429200B1/en?inventor=Vasudev+Parameswaran&oq=Vasudev+Parameswaran&sort=new&page=1)

## More of My Work
The above are just two examples of my creations. You can find more in my [**patents**](https://patents.google.com/?inventor=Vasudev+Parameswaran&oq=Vasudev+Parameswaran&sort=new) and [**publications**](https://scholar.google.com/citations?hl=en&user=8unqZVkAAAAJ&view_op=list_works&sortby=pubdate).
