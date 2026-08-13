---
title: Journey to GUADEC 2026
date: 2026-08-12 22:12:00 +0200
categories: [Technology, GNOME]
tags: [guadec, opensource, linux]     # TAG names should always be lowercase
description: A personal blog post about my journey to and experience at GUADEC 2026 in A Coruña, Spain.
image:
  path: /assets/img/guadec-2026/group-photo-in-front-of-the-entrance.jpeg
  alt: GUADEC 2026
lang: en
translation_key: GNOME, guadec, guadec-2026, guadec 2026
---

I went to GUADEC 2026 last month, held in A Coruña, Spain, between 15 and 21 July. It was my first time attending GUADEC. And it was also my first time attending an English-speaking conference. I met and talked with people in person whom I've admired for a long time. This experience was certainly not an easy one for me. The feeling was intense; it took me several days to calm down after coming back to Bordeaux. I feel lighter now.

## My dream 

Attending GUADEC was basically one of my dreams (yep, I have a lot of dreams; luckily, I've achieved some of them). To me, it was kind of a long journey.

Once I arrived in Bordeaux in September 2025, I started paying attention to GUADEC. When I learned that it would be held in Spain in 2026, I was so excited that I told my classmates I would go there no matter what! 

Almost 11 years ago, probably in 2014, I missed it in Beijing. At that time, I had just graduated and I had my first job as a developer. There was a lot of stress at work, and I didn’t have the energy to attend it, even though it was held in the same building where I was working.

At university, my major was Applied Spanish. In 2012, I became very interested in the Linux ecosystem. I switched to Linux, and I have been using Fedora and GNOME ever since. Later, I began teaching myself programming languages, such as C, Java, and JavaScript.

The Linux system helped me, as did the GNOME desktop. Years later, I became more and more reliant on GNOME, and the lack of a "save and restore sessions" feature annoyed me a lot. I did some research and found that many other users were annoyed by the same issue as well.

In 2019, I began writing a Python program to save and restore sessions, called [xsession-manager](https://github.com/nlpsuge/xsession-manager). As the name suggests, it only worked on X11.

In 2021, shungo27 submitted an issue (https://github.com/nlpsuge/xsession-manager/issues/30) asking, "How can I run xsm-s automatically when the system shutdown / reboot / logout?". I studied the issue for a while, but couldn’t find a solution.

Two weeks later, I realized that I could solve it by creating a GNOME Shell extension. That's how [gnome-shell-extension-another-window-session-manager](https://github.com/nlpsuge/gnome-shell-extension-another-window-session-manager) was born. I replied to the issue. I was probably the first person to implement this feature in a GNOME  extension, although I could be wrong.

During the development of the extension, I found it very interesting. To make it work as expected, I read a lot of the source code of GNOME Shell, Mutter, GJS, Clutter, etc. I also submitted a very small merge request to gnome-shell in 2023.

When I checked the GUADEC 2026 timetable in June, I suddenly saw a talk titled « Session Save/Restore » by Adrian Vovk. The description read: 
" GNOME 51 is on track to introduce a platform-wide session save and restore framework. This is a long-requested feature that allows session and app state to be saved when the user logs out, and restored when they log back in."

Quelle chance! 

I don’t know how to describe my feelings at that time now. Was I even more excited? Or maybe I just wanted to go there even more?

After I better understood the new policies affecting non-EU international students, I accepted the travel sponsorship granted by the Travel Committee at the beginning of July and began booking a room in Rialta (only one single room left in Residencia Rialta, no time to waste!) and buying my travel tickets.

## During the conference 

After the talk "Session Save/Restore", I asked Andrew three questions: 

1. Over the years, there have been many extensions, including mine, on the website https://extensions.gnome.org that do similar things in different ways. So what does this mean for those extensions?
2. Can we switch it off in an extension?
3. Will you provide some APIs for extension developers?

During the break, I talked with him for a while. The answers to the questions above were as follows:
1. I personally think those extensions can coexist with it, as the system-wide feature only provides basic Session Save/Restore functionality. With extensions, we can modify and enhance it.
2. Yes
3. Yes, but things could be complex. I don’t know, but extension APIs are not always stable anyway.

This feature might be rolled out in GNOME 52 or 53. Since applications (including GTK-, Qt- based applications) will need to save their window states so that they can be restored to their previous states. The adoption could take much longer. It’s more complex than I imagined, But let’s stay positive. :)

During the conference, I constantly felt that my English was not good enough to understand the talks and interact with others. But some attendees kept telling me that my English was okay, and that it was because of other issues, like the background noise. I’m glad that I still have two more years to improve it. What worries me more is my French.

I tried to talk to as many attendees as possible. To my surprise, a lot of attendees and volunteers could speak French. When they learned that I was learning French, we chatted in French for a while. I was happy that I could practice French during the conference. I tried to find native French speakers, but I only met one.

I met two Nepalese attendees, Aaditya Singh and Sailesh Singh, on my way to the conference on the third day. I hadn't slept well for two nights in a row and was tired, so I got up too late. I had to walk to the conference. I accidentally dropped my badge. Luckily, they found it and gave it back to me. Later they told me they knew a French person. They then introduced me to Guillaume Bernard during the break.

![Sailesh Singh and me](/assets/img/guadec-2026/sailesh-singh-and-me.jpg)
*Sailesh Singh and me*

I hope Guillaume Bernard’s proposal https://discourse.gnome.org/t/gnome-capitole-du-libre-toulouse-france-14-15-nov-2026/36033 gets approved, and I want to attend this event in Toulouse. I really appreciate his helpful suggestions about learning French, and writing a good CV and motivation letter. He sent me a handy website for checking grammar, which I’m actually using to help me edit this blog.

I also talked with Michael Calabrese, Laureen Caliman, Zelda Ahmed, Philipp Sauberzweig, Jiri Prajzner, Petr Kovar, and other attendees. My apologies that I didn’t remember all of their names. We had some good conversations. 

![](/assets/img/guadec-2026/group-photo-with-the-gnome-like-logo.jpeg)
*Philipp, Zelda Ahmed, Guillaume, myself and Tau in front of a building with a very sandy foot that looks rather similar to the GNOME Logo! (I copied this sentence from [Zelda Ahmed's blog](https://zeldathewitch.page/posts/guadec-2026/) ~~)*


And I’ll always remember that night in a small pub with some of them, ordering and drinking a very, very big glass of beer with the help of Petr Kovar, while watching the 2026 World Cup final between Spain and Argentina. Frustrated and cheering with other people, we congratulated Spain on winning. 

Then I took a photo of a group of people in front of the pub, where they were taking a group photo as a souvenir of the winning night. I said “Cheese!” to them, they of course ignored me. We laughed hard. 

The street was so lively, with a lot of people, some holding small Spanish flags. They were cheering and celebrating. There were also some small street performances. The cars were honking, and people were leaning out of the car windows, waving flags. 

We bought more beers at a shop…… After one of them finally found a taxi on the street, we went back to the hotel and continued talking outside. Someone had to get up early in the morning to catch a flight, so we said goodbye.

On the fifth day, I finally remembered to buy a T-shirt as a souvenir. I asked a volunteer in the faculty of the University UDC, where the conference took place, but it was too late. I promised him that at GUADEC 2027 next year, the first thing I would do once I arrived would be to buy a T-shirt!

That afternoon, I met two organisers while I was walking to Miradoiro Fiestra ao Atlántico along the road by the sea. They confirmed that the T-shirts had sold out on the very first day. Last year, they had prepared more T-shirts, but no one bought them. This year, however, they were in high demand. 

![](/assets/img/guadec-2026/two-organisers-and-me-1.jpg)

I also asked if they had any more blank badges, because I had lost mine, again. On the second day, Asmit Malakannawar replied to me that they had also run out. 

If I had one suggestion for the next GUADEC, it would be to prepare more T-shirts, and probably more blank badges as well.

As for another suggestion, I think it would be better to let us build a working application ourselves during the "GTK local-first workshop" and "Let's build an app for the modern GNOME platform using C++". I’m interested in these two sessions. I have always wanted to create a standalone GUI application in C/C++.

## My plans

I would like to continue contributing to the GNOME ecosystem and maintaining my GNOME Shell extensions. 

Meanwhile, I’m learning French in Bordeaux through university courses and have been learning it intensively for more than two years. I’m looking forward to starting a completely new life in France.

But even after living here for nine months, I’m still facing challenges in Bordeaux. I hope everything goes well.

In December, I plan to take the DELF B2 exam and pass it. Between March and July 2027, I will apply to master’s programs taught in French, wait for the admission offers and make my final decision. After everything is settled, I want to travel around France before starting my master’s program.


## ❤️ Huge thanks to GNOME ❤️

This journey to GUADEC 2026 is sponsored by the GNOME organization. I really appreciate the Travel Committee for granting me the generous financial support, which covers the transportation and accommodation costs. Huge thanks to everyone who made it possible for me to be part of GUADEC.

![](/assets/img/gnome/sponsored-by-foundation.png)

I’m looking forward to GUADEC 2027, and I hope that when we meet again, we will still remember each other or at least feel familiar.

