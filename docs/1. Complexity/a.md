# The result of Complexity

I created this list for some academic work in 2015. Let me know if you have any good, more recent examples.

13th August 2014: Verizon make a small routing error, causing their BGP routes to desegregate. This added a few thousand new routes to the internet. However, thousands of older Cisco routers have a TCAM limit of 512k entries. These failed and a major internet outage occurred. 

19th June 2012: A software update applied to CA-7 Software brigs down RBS, NatWest, Ulster Bank etc. Ulster Bank has problems for over a month. 

2008: The crash of JK5022 with the loss of 154 should not have happened. The computer which automatically handles fault information from aircraft was infected with malware and did not flag serious problems.

September 2007: A bug is discovered in Excel 2007 which gives incorrect errors when the answer is 65,535 or 65,536.

August 24th 2006: Microsoft’s genuine advantage (!) flagged thousands of genuine licensed instances of Windows XP and Vista clients as being pirated. 

December 2004: Comair runs a 15-year old scheduling software package from SBS International (www.sbsint.com). The software has a hard limit of 32,000 schedule changes per month. With all of the bad weather last week, Comair apparently hit this limit and then was unable to assign pilots to planes.

January 2004: NASA's Spirit rover became unresponsive on January 21, 2004. Too many files had accumulated in the rover's flash memory. It was fixed (delete .)!! 

August 2003: USA Northeast Blackout, a race condition existed in General Electric Energy's Unix-based XA/21 energy management system. 

2001: A cobalt-60 radio-therapy machine in Panama over-irradiates patients for seven months due to an obscure bug. The death toll is not known. 

December 2000: An Osprey aircraft crashes due to a hydraulic failure which should have been compensated for. A software anomaly prevented the pilots from recovering and four marines were killed. 

December 3, 1999: NASA Mars Polar Lander destroyed. Flight software mistook vibrations due to atmospheric turbulence for evidence that the vehicle had landed and shut off the engines 40 meters from the planet’s surface! 

September 23 1999: Mars Climate Orbiter destroyed. Part of the project was done in SI units but data was passed to the spacecraft in American/Imperial units. The spacecraft disintegrated in Mars atmosphere. 

June 1996: Explosion of the Ariane 501 rocket 37 seconds into its maiden flight was due to a software error. Ariane-5's inertial reference system dealt with 64-bit floating-point data and converted it into 16-bit signed integer values. The result of the data conversion was too large for a 16-bit signed integer, which caused an arithmetic overflow in the hardware. 

1994: An entire series of Intel Pentium CPUs had a bug where they calculated incorrectly after the eighth decimal point. The lookup table for calculations was missing 5 out of 1,066 entries. 

Jan. 15, 1990: a bug in redundancy software causes AT&T exchanges to continuously reboot.

1985 and 1986: In at least six cases, a radio-therapy machine (the Therac-25) sent high energy x-ray beams into patients intended for low level radio-therapy. This was due to a bug which causes a race condition between two modes of operation. 

September 23rd 1983: Lt. Col. Stanislaus Petrov saved the world. The USSR early warning system was very buggy and showed a launch of 5 US ICBMs against Russia. Petrov thought the attack profile did not make sense and did not order a retaliation. Sometime later, radar confirmed there were no incoming missiles. Petrov was side-lined and given early retirement.

July 22, 1962: Mariner 1 was intended to send a probe to Venus. A single error in notes resulted in programmers not applying a smoothing function. The rocket thus overcorrected for every error. Self-destruct was triggered 4 minutes into the flight. 

At one time computer mishaps were predominantly the results of human error; now, many mishaps are due to complexity and unanticipated interactions. Consider the results of some of these failures. 

We could define _safety_ as the implications of a failure to operate correctly.