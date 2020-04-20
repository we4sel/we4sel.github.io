
## JS8 Operating Suggestions

### **TL;DR:**  JS8 is a little weird at first. There are a lot of different things going on at the same time using the same space and it’s confusing even if not new.

These are subject to change as better information comes along. Like much of Ham Radio, it can seem like drinking from a firehose at first. All the following is my best attempt at understanding and condensing: very little is “official information”. Please pardon if it gets either too technical or too “crayon. I’ve been trying to figure out how to write a simple guide for folks, and this isn’t very simple but hopefully helpful at leas. Many of the things blend into other categories, which gives lots of combinations and flexibility to the mode and program.

**Ragchew**: (Primary purpose of mode) Active operators at their keyboards having conversations.

 -   Often rather long, slow, patient conversations, lasting from several minutes to several hours or even days if you count multi-session “pick up in the morning where we fell asleep”, got distracted” or had to attend to real life”", etc.
 - Often Logged, at least first qso between stations

**Auto**:  Applies to several overlapping functions

 - **Queries**: There are a good many queries that can be sent to solicit response from a remote station without the direct intervention of the remote operator being needed, such as: 
	 - station info (if they set it in config) 
	 - last several stations heard
	 - last time they heard a particular station
	 - a repeat of their last transmission (very handy)
	 - Rarely Logged

-   **Relay**: transmissions can be relayed through intermediate stations 
	- In case of no direct path between a pair of stations in qso,
	- Manual between the stations in qso 
	- Auto/mesh functions for the intermediate stations. 
	- It’s a little tedious to use in practice, but it’s worth tinkering with and learning to utilize. -
	-  Will be better when longer prop conditions return.
	- Rarely Logged

- **Mesh**: When not active at the keys/in qso, many of operators leave their stations powered on, unattended, in AUTO/HB/ACK purely to participate in this part of the mode.

	 -   Automated “ping - pong” system of  **H**eart**B**eat &  **ACK**nowledgement (**HB**,  **ACK**  &  **SNR**)
	 - Lets the rest of the “network know who’s stations are available for relay/message
	-   Helps to see propagation in both directions, especially when combined with [PSKReporter](hhttps://bit.ly/2KmSOM5) 
	   -   Gives a backbone for message notification. (this was condition of my station when you messaged me). 
	   - This comprises probably >75% of JS8 traffic
	   - Mostly on the low offsets of 500-1000hz.
	   - Can lead to frustration when it’s the only traffic and someone wants to ragchew!  
	   - Rarely logged
       
	    -  **Example**: HB/ACKs from my station at 15w and the 5 automatic responses.
	        >  - TX 14:41:00 - (1100) - WE4SEL: HB AUTO RELAY SPOT EM54 ⣿
    >  -  RX 4:41:29 - (545) - AF5AV: WE4SEL ACK +01 ⣿
    >  -  RX14:41:30 - (654) - KV4ATV: WE4SEL ACK +00 ⣿
    >  -  RX14:41:30 - (847) - KB8HTU: WE4SEL ACK +03 ⣿
    >  -  RX14:41:30 - (893) - W5DXP: WE4SEL ACK +10 ⣿
    >  -  RX14:41:57 - (1006) - W7RLF: WE4SEL ACK -06 ⣿




    
-   **Message**:
    
-   Direct message if received intact, the receiving station will auto-reply an acknowledgement and pop up on the receiver’s screen (if enabled) and stores in a local mailbox. quite handy.
    
-   Messages can be stored on the senders machine, to be transmitted when the target station is on the air and requests the message to be transmitted. it includes the same accuracy check that the message was delivered intact and replies with an acknowledgement to the sending station.
    
-   EG “**15:12:45 - (1100) - WE4SEL: KV4ATV ACK +12 MSG ID 6 ⣿**” in the traffic window. His station sent a HB, mine ACK’d, and since there’s a message in my outbox for him, told him it’s number for retrieval at his convenience.
    
-   Group/Net: there are groups/nets, such as @allcall which will highlight on every receiving station as if it were directed to their personal callsign, as will other groups added with a @ in front, and can be used for nets, etc, with the typical ham creativity. i use @MS (for state) @skywarn and @net but there are lots of others. have seen @arfcom getting some traffic lately if you’re into that.
    

Well, that’s far too much and not nearly enough. maybe a little easier than reading all the documentation, but that’s also an option. In any case is enough rambling from me. Will be glad to try and answer any questions I can.

> Written with  [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTY1MDI5NTM2MV19
-->