# Time

In any production environment, we need to be able to consider the reliability of systems and thus be able to estimate with what likelihood they will be available for usage. This is more complex than it sounds and failure to estimate correctly can lead to financial loss, safety implications, or outright disaster. We also need to be able to define what failure means. 

Suppose I contract a bank to provide ATM services on campus. 

The bank tenders for a service that will be available 99% of the time; sounds good? 

The implications is that it could be out of operation for 3.65 days per year, or 8 hours per month or 1:40 per week…..which is it? 

So the bank installs the ATM, but there is never any money in it until lunchtime on Monday. The ATM was working all this time, so the bank says they had 100% availability. So, what constitutes failure and how would we define it? One of the challenges especially in contracts and SLAs is to define failure. The IEC have some useful general definitions. Failure is:

The termination of the ability of the product to perform its required function.

The termination of the ability of any individual component to perform its required function but not the termination of the ability of the product to perform. 

Before we start any exercise, we need to define what the word failure means in the context we are working in.

If we look at a large enough number of systems, we can predict how reliable systems are likely to be over the long term. We need to consider many systems to be statistically significant and the size of the sample determines how confident we can be in the accuracy of our estimates. Small samples are meaningless.

We usually express these values in hours. 

Over very large sample sizes we can determine the mean time for a first failure to occur and we call this the _mean time to failure_ or MTTF. The bigger the MTTF, the better. 

We can determine on average, how long it takes to identify the problem, fix it and reintegrate the systems. This is the _mean time to repair_ or MTTR. The lower the MTTR, the better. 

Failures will reoccur. The _mean time between failures_ or MTBF is the time a system runs without failure (normally MTTF) plus the mean time to repair, MTTR. We call this figure the MTBF and the bigger it is, the better.

How important all these things are depends on the circumstances. A brief outage in a process might cause total loss: for example, in chip fabrication. Alternatively, we might have a retail operation where we can calculate a loss per hour which is constant and predictable.

How about a computer shop, a brief outage may have no implications and a customer might come back tomorrow? However, if you cannot service the customer tomorrow, you lose the customer. 

We may have critical periods when downtime is unacceptable and has a high cost (like a University during registration or examinations) but where an outage at other times has no major implications. 

We calculate each case uniquely. There is specific terminology used and, in these notes, I will define these terms, their interpretation and any underlying maths.