Download Link: https://assignmentchef.com/product/solved-ece487-assignment-5-automatic-repeat-request-arq-protocol
<br>
<ol start="2">

 <li>Consider that a communication system uses an automatic repeat request (ARQ) protocol. The distance between the sender and receiver is 6,000,000 meters, and the propagation speed is 3×10<sup>8</sup> meters per second. We only consider propagation delay and ignore all other delay (and therefore, the transmission time of a frame can be infinitely small). The time-out value of a timer is 1 second. At the sender side, there are an infinite number of packets in Layer 3 to be sent. The size of a data frame is 2000 bits.

  <ul>

   <li>Assume stop-and-wait ARQ is used and no frame is corrupted. What is the throughput of the system? Here throughput means for a long duration (for example, a day), on average how many bits of information per second can be delivered successfully from the sender to the receiver.</li>

   <li>Assume stop-and-wait ARQ is used. The channel from the sender to the receiver is noiseless. The channel from the receiver to the sender is noisy in such a manner that, for each particular data frame, its first ACK is always corrupted, while its second ACK is always successfully received by the sender. Then what is the throughput of the system?</li>

   <li>Assume Selective Repeat ARQ with m=3 bits for the sequence number is used and no frame is corrupted. What is the throughput of the system?</li>

  </ul></li>

 <li>Fifty stations on a pure ALOHA network share a 1-Mbps (10<sup>6</sup> bit per second) channel. If frames are 1000 bits long, find the system throughput (<strong>in unit: frames/second</strong>) if each station is sending 10 frames per second. Repeat this question for slotted ALOHA.</li>

 <li>(a) In a CSMA/CD network with a data rate of 5 Mbps, the minimum frame size is found to be 512 bits for the correct operation of the collision detection process. What should be the minimum frame size if we increase the data rate to 30 Mbps? (b) In a CSMA/CD network with a data rate of 5 Mbps, the maximum distance between any station pair is found to be 500 meters for the correct operation of the collision detection process. What should be the maximum distance if we increase the data rate to 50 Mbps?</li>

 <li>Consider a standard Ethernet (which implements CSMA/CD and 1-persistent method) with only three stations in a line: the distance between Station A and Station B and between Station B and Station C are both 150 meters. The propagation speed is the speed of light (3×10<sup>8</sup> meters per second). The data rate is 10 Mbps. At time instant t<sub>1</sub>=0 microsecond, Station A has a frame with size 2,000 bits to be sent. At time instant t<sub>2</sub>=0.2 microsecond, Station B has a frame with size 3,000 bits to be sent. At time instant t<sub>3</sub>=0.3 microsecond, Station C has a frame with size 4,000 bits to be sent. Please determine the number of bits each station can send during its first</li>

</ol>

transmission attempt. Note that 1 microsecond  = 10<sup>-6</sup> second.