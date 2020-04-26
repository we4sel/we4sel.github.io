---


---

<h1 id="js8-operating-suggestions">JS8 Operating Suggestions</h1>
<h4 id="home--station-and-contact-on-the-aironline-radio-clubs--organizationsprojectsjs8call-operating-suggestions-and-informationyou-are-here">++<a href="index.md">Home </a> ++<a href="ontheair.md">Station and Contact On The Air</a>++<a href="hclubs.md">Online Radio Clubs &amp; Organizations</a>++<a href="projects.md">Projects</a>++JS8Call Operating Suggestions and Information(you are here)</h4>
<hr>
<h3 id="tldr--js8-is-a-little-weird-at-first.-there-are-a-lot-of-different-things-going-on-at-the-same-time-using-the-same-space-and-it-can-be-confusing-even-if-not-new-to-ham-radio-or-js8.-there-is-much-much-more-but-these-are-the-things-i-use-most-often-and-how."><strong>TL;DR:</strong>  JS8 is a little weird at first. There are a lot of different things going on at the same time using the same space and it can be confusing, even if not new to Ham Radio or JS8. There is much much more, but these are the things I use most often, and how.</h3>
<p><em>NOTICE: in the following is much I may have wrong, or there could certainly be better ways of doing almost everything than those I have described here. I’m open to suggestions and will give due consideration to those received, and if they seem to work better, then the following will certainly be updated to reflect best practices as I understand them.</em></p>
<p>These are subject to change as better information comes along. Like much of Ham Radio, it can seem like drinking from a firehose at first. All the following is my best attempt at understanding and condensing: very little is “official information”. Please pardon if it gets either too technical or too “crayon. I’ve been trying to figure out how to write a simple guide for folks, and this isn’t very simple but hopefully helpful at leas. Many of the things blend into other categories, which gives lots of combinations and flexibility to the mode and program.</p>
<p><strong>Ragchew</strong>: (Primary purpose of mode) Active operators at their keyboards having conversations.</p>
<ul>
<li>Often rather long, slow, patient conversations, lasting from several minutes to several hours or even days if you count multi-session “pick up in the morning where we fell asleep”, got distracted” or had to attend to real life”", etc.</li>
<li>Often Logged, at least first qso between stations</li>
</ul>
<p><strong>Auto</strong>:  Applies to several overlapping functions</p>
<ul>
<li>
<p><strong>Queries</strong>: There are a good many queries that can be sent to solicit response from a remote station without the direct intervention of the remote operator being needed, such as:</p>
<ul>
<li>station info (if they set it in config)</li>
<li>last several stations heard</li>
<li>last time they heard a particular station</li>
<li>a repeat of their last transmission (very handy)</li>
<li>Rarely Logged</li>
</ul>
</li>
<li>
<p><strong>Relay</strong>: transmissions can be relayed through intermediate stations</p>
<ul>
<li>In case of no direct path between a pair of stations in qso</li>
<li>Manual between the stations in qso</li>
<li>Auto/mesh functions for the intermediate stations.</li>
<li>It’s a little tedious to use in practice, but it’s worth tinkering with and learning to utilize.</li>
<li>Will be better when longer prop conditions return.</li>
<li>Rarely Logged</li>
</ul>
</li>
<li>
<p><strong>Mesh</strong>: When not active at the keys/in qso, many of operators leave their stations powered on, unattended, in AUTO/HB/ACK purely to participate in this part of the mode.</p>
<ul>
<li>Automated “ping - pong” system of  <strong>H</strong>eart<strong>B</strong>eat &amp; <strong>ACK</strong>nowledgement (<strong>HB</strong>,  <strong>ACK</strong>  &amp;  <strong>SNR</strong></li>
<li>Lets the rest of the “network know who’s stations are available for relay/messages</li>
<li>Helps to see propagation in both directions, especially when combined<br>
with <a>PSKReporter</a></li>
<li>Gives a backbone for message notification.</li>
<li>Comprises probably &gt;75% of JS8 traffic</li>
<li>Mostly on the low offsets of 500-1000hz.</li>
<li>Can lead to frustration when it’s the only traffic and someone wants to ragchew!</li>
<li>Rarely logged</li>
</ul>
<pre><code> &gt; E.G. HB/ACKs from my station at 15w and the 5 automatic responses.
 &gt; 	    TX 14:41:00 - (1100) - WE4SEL: HB AUTO RELAY SPOT EM54 ⣿
 &gt; 	    RX 4:41:29 - (545) - AF5AV: WE4SEL ACK +01 ⣿
 &gt; 	    RX 14:41:30 - (654) - KV4ATV: WE4SEL ACK +00 ⣿ 
 &gt; 	    RX 14:41:30 - (847) - KB8HTU: WE4SEL ACK +03 ⣿ 
 &gt; 	    RX 14:41:30 - (893) - W5DXP: WE4SEL ACK +10 ⣿
 &gt; 	    RX 14:41:57 - (1006) - W7RLF: WE4SEL ACK -06 ⣿
</code></pre>
</li>
<li>
<p><strong>Message</strong>: -   	- Direct message if received intact, the receiving station will auto-reply an acknowledgement and the message will pop up on the receiver’s screen (if enabled) and stores in a local mailbox.</p>
<ul>
<li>Messages can be stored on the senders machine, to be transmitted when the target station is on the air and requests the message to be transmitted.</li>
<li>Includes the same accuracy check that the message was delivered intact and replies with an acknowledgement to the sending station.</li>
<li>Quite handy.</li>
<li>
<pre><code>  E.G. 15:12:45 - (1100) - WE4SEL: KV4ATV ACK +12 MSG ID 6 ⣿
</code></pre>
in the traffic window. His station sent a HB, mine ACK’d, and since there’s a message in my outbox for him, told him it’s number for retrieval at his convenience.</li>
</ul>
</li>
<li>
<p><strong>Group/Net</strong>:</p>
<ul>
<li>There are groups/nets, such as @allcall @net etc</li>
<li>Highlights on every receiving station as if it were directed to their personal callsign</li>
<li>Can be used for nets, etc, with the typical ham creativity.</li>
<li>Examples @MS (for state) @skywarn, @net, @arfcom</li>
</ul>
</li>
</ul>
<p>Well, that’s far too much and not nearly enough. Maybe a little easier than reading all the documentation, but that’s also an <strong><a href="http://files.js8call.com/latest.html">VERY GOOD IDEA</a></strong>. In any case is enough rambling from me. Will be glad to try and answer any questions I can.</p>
<hr>
<p>“Talking to Aliens” v042520201900</p>

