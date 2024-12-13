# API206-R | How event-driven architectures can go wrong and how to fix them

Event-driven architectures enable speed and agility for distributed cloud applications; however, this also means there’s the risk of shipping bad ideas fast without governance. Fortunately, the same agility allows for quick fixes. Attend this chalk talk to learn common event-driven pitfalls, including YOLO events, god events, observability soup, event loops, exposing monoliths, state corruption, and surprise bills. Explore strategies and techniques teams can implement to avoid these pitfalls and reap the full benefits of event-driven architectures.

**Matthew Meckes:Sr Serverless Specialist, AWS**

**Luca Mezzalira:Principal Serverless Specialist, AWS**

Existing architectures
![alt text](IMG_3060.png)
- Eventbridge can integrate with API in VPC (New Feature)
- ECST - Event Carry State Transfer

Steps to consider
1. Gather Requirement
2. Understand your broker
3. Understand the event
4. Model your domain (Event Stromming)
5. Use event b/w domains
6. Design your consumers
7. Document you decisions. 
Always don't be afraid to break the rules

