---
layout: "post"
title: "What I learned this month - January 2021"
date: "2021-01-01 20:21"
---
# What I learned in January 2021


### Etymology

**Destiny vs Fate vs Weird**

Someone asked what is the difference between fate and destiny. As I have mentioned before, similar words in English often came into the language and different times from different languages as I will explain:

**Destiny**

This is the easiest word to trace it's from the Latin word destinare "make firm, establish" (like destination). i.e. "that which has been firmly established," as by fate and is usually a positive meaning.

**Fate**

The word “fate” and also the word “weird” is related to the idea of "The Fates" being, usually three, female beings who rule the destiny of gods and men. They appear in many European mythologies. Also know as Norns in Norse mythology, in Greek Moirai and the Roman Parcae. They were often depicted as weavers of a tapestry on a loom, with the thread dictating the destiny each person. Once the cloth of your life is woven then there is no way to change it. It is your fate.
Fate is from the Latin word "fatum" a "prophetic declaration of what must be, oracle, prediction," thus the Latin word's usual sense is "that which is ordained, destiny, fate," literally "a thing spoken by the gods," originally from the past participle of fari "to speak". It's often used in a bad or negative sense: I.e. "bad luck, ill fortune; mishap, ruin; a pest or plague."

**Weird**

The original word in English for “fate” was “wyrd” as in Shakespeare's weird sisters, the three fates or Norns (in Germanic mythology), the goddesses who controlled human destiny. In the theatre they were portrayed as odd or frightening in appearance, as in Shakespeare"s play "Macbeth" and especially in 18th and 19th century productions of it, which led to the adjectival meaning "odd-looking, uncanny" (in 1815); "odd, strange, disturbingly different" (in 1820).
The world "wyrd" comes from the Proto-Germanic “wurdiz”, from the Proto-Indo-European “wert-“ (“to turn, wind”) which is the origin of the name of the Norns, urðr. This is related also to the turning of the spinning wheel that the Fates use to spin the thread of your life.

**Fatal**

Finally, another related word is “fatal”. We use it to describe something like an injury or illness that brings death but the original meaning is that this was the fate that brought you to your death. Thus a fatal injury.

### Making Your Own Alexa

This YouTube video was really inspiring as it brought together many tools.

https://youtu.be/re-dSV_a0tM

## Projects

### Radiation Counter

* Radiation Counter attached to my Raspberry Pi. I found the serial port Geiger Counter that bought in 2011 and resurrected it. I also found a Linux Python script for it which I hacked a bit to be able to save the readings in JSON files. I'm planning on reading this with another program and feeding them into a RRD file and from that making graphs which I post can post to Twitter. After that I think I'll download the tweet archive for the radiation counter account that I made and see if I can put all the historical figure into RRD.

### Home Network Monitoring

I didn't know this command:

```
sudo arp-scan -l -r 3
Interface: eth0, datalink type: EN10MB (Ethernet)
Starting arp-scan 1.9.5 with 256 hosts (https://github.com/royhills/arp-scan)
192.168.3.1    30:f7:72:b5:0a:19       Hon Hai Precision Ind. Co.,Ltd.
192.168.3.9    70:73:cb:b3:49:cc       Apple, Inc.
192.168.3.10   ec:fa:bc:5d:c5:bd       (Unknown)
192.168.3.12   00:25:4b:04:5f:fb       Apple, Inc.
192.168.3.17   00:11:32:3b:f6:73       Synology Incorporated
192.168.3.11   50:02:91:ea:9e:dd       (Unknown)
192.168.3.25   70:73:cb:b3:49:cc       Apple, Inc.
192.168.3.16   7c:ab:60:69:c0:65       (Unknown)
192.168.3.27   0c:fe:45:c8:e8:48       Sony Interactive Entertainment Inc.
192.168.3.35   00:04:20:07:92:f4       Slim Devices, Inc.
192.168.3.37   bc:c3:42:6c:65:c0       Panasonic System Networks Co., Ltd.
192.168.3.15   6a:ad:b9:dd:79:13       (Unknown)
192.168.3.7    64:b5:c6:b4:da:42       (Unknown)
192.168.3.32   8c:85:90:89:71:52       (Unknown)
192.168.3.31   b2:70:0e:35:44:72       (Unknown)
192.168.3.41   da:f0:d6:f2:19:4d       (Unknown)
192.168.3.19   22:6b:95:93:04:18       (Unknown) (DUP: 1)

21 packets received by filter, 0 packets dropped by kernel
Ending arp-scan 1.9.5: 256 hosts scanned in 6.466 seconds (39.59 hosts/sec). 17 responded
```
### Personal Analytics

* Great Podcast: I love the story of Django.. https://overcast.fm/+F4RDYeRcw He talks about my passion for personal data collection. SQLite, JSON, data sources that you can tap into, Python.
* TODO: https://www.youtube.com/watch?v=CPQCD3Qxxik



## Interesting Stuff

* If you want to set goals or change your life in anyway, I really recommend this guy: https://youtu.be/LZZgxc1tnGM
* @OpenAI has trained a model that can create new images - you just describe them in English. 🤯 openai.com/blog/dall-e/
* The Art of Negotiation: https://youtu.be/_UaH98O7ku8 I’m tempted to say after listening to this guy for a while that a good voice trumps good looks..
* I really enjoy this guy’s videos. I would suggest watching all three of these but this episode is outstanding. After crossing Wales in a straight line, he tries to cross Norway in the straight line. Totally crazy. https://youtu.be/kwzIwFPEGbA
* Pretty amazing thread about how Amazon AWS started: https://twitter.com/danrose999/status/1347677573900242944?s=21
* I really enjoyed Amanda Gorman’s poem at the inauguration https://youtu.be/Wz4YuEvJ3y4 I looked at quite a few of her other performances and was again reminded of the power of words.
* Co-Pilot of the plane that went down in the Hudson River tells his story: https://youtu.be/qr5SxnDom7g
* Stumbled across this history YouTube Channel: https://youtu.be/vVgCy6iwrHQ
* How car seat laws have impacted the birthrate. Spoiler it is a bigger hassle/expensive to drive 3 kids vs 2 kids. https://overcast.fm/+WaLEzH_Wc
* Some good leadership lessons here: https://overcast.fm/+I6DC--ISU
* this was interesting when he got into talking about skills-domain-field… https://overcast.fm/+BcN3hQ3Jc
* wow if this really works https://twitter.com/mashable/status/1353034007517171712
*  Very inspirational and detailed story how a guy built his own business: https://www.listennotes.com/blog/how-i-accidentally-built-a-podcast-api-business-46/
* Mozilla Engineer Track: https://twitter.com/Gankra_/status/1046438955439271936
* The origin of the Beatles track "Dear Prudence" - https://youtu.be/_EENbm2oeX0


## To Try

* n³ The unorthodox terminal file manager. 
* I don't write much CSS/HTML at the moment but this looks like a useful tool https://docs.emmet.io/
* Haruki Murakami: Daily Routine - Balance The Grind | Conversations On Work, Life & Balance https://www.balancethegrind.com.au/daily-routines/haruki-murakami-daily-routine/
* This is the kind of website that I want to build. https://www.gwern.net/About I might make a static site generator to make this site look like it.
* https://github.com/itchyny/mmv
* https://www.snorkel.org/
* MIT’s Introduction to Economics: A Free Online Course. https://www.openculture.com/2021/01/mits-introduction-to-economics-a-free-online-course.html
* To listen: https://80000hours.org/podcast/episodes/we-are-not-worried-enough-about-the-next-pandemic/
* *A half-hour to learn Rust* https://fasterthanli.me/articles/a-half-hour-to-learn-rust
* https://www.youtube.com/watch?v=-knZwdd1ScU&feature=emb_logo
* https://twitter.com/thingskatedid/status/1316074032379248640?s=12
* https://www.sutori.com/story/hendrik-marius-jonkers-and-self-healing-concrete--VRqdpkdTCK13o6ABHoWGC3tF
* https://jvns.ca/blog/2021/01/12/day-36--server-sent-events-are-cool--and-a-fun-bug/
* https://carlschwan.eu/2020/12/29/adding-comments-to-your-static-blog-with-mastodon/

```
tldr jq     

  A command-line JSON processor that uses a domain-specific language.
  More information: <https://stedolan.github.io/jq>.

  Output a JSON file, in pretty-print format:

      jq . file.json

  Output all elements from arrays (or all the values from objects) in a JSON file:

      jq '.[]' file.json

  Read JSON objects from a file into an array, and output it (inverse of `jq .[]`):

      jq --slurp . file.json

  Output the first element in a JSON file:

      jq '.[0]' file.json

  Output the value of a given key of the first element in a JSON text from `stdin`:

      cat file.json | jq '.[0].key_name'

  Output the value of a given key of each element in a JSON text from `stdin`:

      cat file.json | jq 'map(.key_name)'

  Output the value of multiple keys as a new JSON object (assuming the input JSON has the keys `key_name` and `other_key_name`):

      cat file.json | jq '{my_new_key: .key_name, my_other_key: .other_key_name}'

  Combine multiple filters:

      cat file.json | jq 'unique | sort | reverse'

  Output the value of a given key to a string (and disable JSON output):

      cat file.json | jq --raw-output '"some text: \(.key_name)"'

		```

## To Learn

* https://datasette.io/
* How to write a simple slack bot on PythonAnywhere
* Find out how to use a different template on GitHub Pages.
* Slack API 

## Blogs
* New https://martin.kleppmann.com/


## Tools

* TabNine
* Vim


## Tools Used to Make This Page

### iOS

* Textastic
* Working Copy

### Services

* GitHub Pages
* Hover Domain Hosting

### TODO
* TODO: A shortcut or script that will make a nicely formatted insert from a raw YouTube URL

