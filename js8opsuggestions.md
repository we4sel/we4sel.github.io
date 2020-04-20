---


---

<h2 id="js8-operating-suggestions">JS8 Operating Suggestions</h2>
<h3 id="tldr--js8-is-a-little-weird-at-first.-there-are-a-lot-of-different-things-going-on-at-the-same-time-using-the-same-space-and-its-confusing-even-if-not-new."><strong>TL;DR:</strong>  JS8 is a little weird at first. There are a lot of different things going on at the same time using the same space and it’s confusing even if not new.</h3>
<p>These are subject to change as better information comes along. Like much of Ham Radio, it can seem like drinking from a firehose at first.  All the following is my best attempt at understanding and condensing: very little is “official information”. Please pardon if it gets either too technical or too “crayon. I’ve been trying to figure out how to write a simple  guide for folks, and this isn’t very simple but hopefully helpful at leas. Many of the things kinda blend into other categories, which gives lots of combinations and flexibility to the mode and program.</p>
<ul>
<li>
<p><strong>Ragchew</strong>: (Primary purpose of mode) Active operators at their keyboards having conversations.</p>
<ul>
<li>Often rather long, slow, patient conversations, lasting from several minutes to several hours or even days if you count multi-session “pick up in the morning where we fell asleep”, got distracted” or had to attend to real life”", etc.</li Often there may be dropped frames that have to be repeated or guessed at, whole lost messages, major shifts in prop, the usual things that happen to radio.</li>
</ul>
</li>
<li>
<p><strong>Mesh</strong>: When not active at the keys/in qso, many of operators leave their stations powered on, unattended, in auto HB/ACK, purely to participate in this part of the mode.</p>
<ul>
<li>
<p>an automated “ping - pong” system of <strong>H</strong>eart<strong>B</strong>eat  &amp; <strong>ACK</strong>nowledgement</p>
</li>
<li>
<p>(<strong>HB</strong>, <strong>ACK</strong> &amp; <strong>SNR</strong>)</p>
</li>
<li Lets the rest of the “network know who’s stations are available for relay/message</p>
</li>
<li>
<p>Helps to see propagation in both directions (esp if combined with pskreporter).</p>
</li>
<li>
<p>Gives a backbone for message notification. (this was condition of my station when you messaged me). This comprises probably &gt;75% of JS8 traffic, most of which will on the low offsets of 500-1000hz.</p>
</li>
<li>
<p>Can lead to frustration when it’s the only traffic and someone wants to ragchew!<br>
-  	 <strong>Examples</strong>: HB from my station at 15w and the 5 automatic responses.</p>
<blockquote>
<pre><code>  -	TX 14:41:00 - (1100) - WE4SEL: HB AUTO RELAY SPOT EM54 ⣿
  - RX 4:41:29 - (545) - AF5AV: WE4SEL ACK +01 ⣿
  -  RX14:41:30 - (654) - KV4ATV: WE4SEL ACK +00 ⣿
  -  RX14:41:30 - (847) - KB8HTU: WE4SEL ACK +03 ⣿
  -  RX14:41:30 - (893) - W5DXP: WE4SEL ACK +10 ⣿
  -  RX14:41:57 - (1006) - W7RLF: WE4SEL ACK -06 ⣿
</code></pre>
</blockquote>
</li>
</ul>
</li>
<li>
<p>Auto's: [Probably not the best term. If you happen to have used FSQ, i think this is an adaptation and advancement of ideas from that mode] There are a good many queries that can be sent to solicit response from a remote station without the direct intervention of the remote operator being needed. for instance, asking a station for their station info (if they set it in config), asking a station what other stations they copy, last time they heard a particular station, asking for a repeat of their last transmission (very handy), and so on.</p>
</li>
<li>
<p>Relay. transmissions can be relayed through intermediate stations in the case of no direct path between a pair of stations in qso, which is accomplished actively between the stations in qso but is part of the mesh functions for the intermediate stations. it’s a little tedious to use in practice, but it’s worth tinkering with and occasionally gets used. will be better when longer prop conditions return.</p>
</li>
<li>
<p>Message:</p>
</li>
<li>
<p>Direct message if received intact, the receiving station will auto-reply an acknowledgement and pop up on the receiver’s screen (if enabled) and stores in a local mailbox. quite handy.</p>
</li>
<li>
<p>Messages can be stored on the senders machine, to be transmitted when the target station is on the air and requests the message to be transmitted. it includes the same accuracy check that the message was delivered intact and replies with an acknowledgement to the sending station.</p>
</li>
<li>
<p>EG “<strong>15:12:45 - (1100) - WE4SEL: KV4ATV ACK +12 MSG ID 6 ⣿</strong>” in the traffic window. His station sent a HB, mine ACK’d, and since there’s a message in my outbox for him, told him it’s number for retrieval at his convenience.</p>
</li>
<li>
<p>Group/Net: there are groups/nets, such as @allcall which will highlight on every receiving station as if it were directed to their personal callsign, as will other groups added with a @ in front, and can be used for nets, etc, with the typical ham creativity. i use @MS (for state) @skywarn and @net but there are lots of others. have seen @arfcom getting some traffic lately if you’re into that.</p>
</li>
</ul>
<p>Well, that’s far too much and not nearly enough. maybe a little easier than reading all the documentation, but that’s also an option. In any case is enough rambling from me. Will be glad to try and answer any questions I can.</p>
<blockquote>
<p>Written with <a href="https://stackedit.io/">StackEdit</a>.</p>
</blockquote>
).
<!--stackedit_data:
eyJoaXN0b3J5IjpbMjMyNzY2OTU0XX0=
-->