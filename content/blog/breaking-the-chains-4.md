+++
date = 2020-02-07T04:30:00Z
tags = ["privacy"]
title = "Breaking the Chains #4 - Annoying my Friends About Switching to Signal"

+++
**tl;dr** Download [Signal](https://signal.org/) as your texting/messaging app because Big Brother is watching you. Or something like that.

# Story Time

For the first time ever in my life, I wore a literal tin foil hat. Let me take it back a few steps though, and tell you just what led up to this pivotal moment of my life where I became one of the crazies.

## An Experiment

Last week, I walked into my housemate's room for my weekly attempt to get him to [use Signal](https://signal.org/), a messaging app that uses end-to-end encryption (message is scrambled as it travels from one phone to another, only being unscrambled on the app) when talking to other Signal users. One of my reasons for why he should switch is that it would allow him to send images over WiFi, saving his mobile data. He was confused as to why that was special, since he claimed his phone already was able to send images with mobile data off and without WiFi. I thought he was confused, since my phone didn't do that. So we tested it by calling up some of our friends and trying a bunch of combinations of cell carrier, messaging app, and phone model. The results are as follows.

|  | Control | Test 1 | Test 2 | Test 3 | Test 4 | Test 5 | Test 6 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Carrier | Verizon | AT&T | Verizon | Google Fi | T-Mobile | AT&T | AT&T |
| Phone | Pixel 3 | Moto G5S+ | Note 5 | Pixel 2 | Pixel 2XL | iPhone 11 Pro | Moto G5S+ |
| App | Messages | Signal | Signal | Signal | Messages | iMessage | Messages |
| w/ WiFi Only | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| w/ Data Only | Yes | Yes | Yes | No | Yes | Yes | Yes |
| w/ Cell Signal Only | Yes | No | No | No | No | No | Yes |

From our very small sample size, you can notice that the only time one of the test phones was able to send an image using only cell signal was when using Android's default Messages app. While I still don't understand the value of sending memes over cell signal instead of waiting until you have WiFi, it was admittedly a feature of Android Messages that Signal couldn't do. So after an hour of conducting this "research" to try convincing my friend to switch to Signal, I gave up. That was the end of it, or so I thought.

## This is When My Paranoia Kicks In

Fast forwarding to this week, I switched to my cell carrier to Google Fi to be on the same plan as my mum and my little brother. Now, you might be asking: if you care so much about your privacy, why are you feeding your messages to Google? The answer is simple: all the major cell carriers have been caught collecting and selling data ([like to bounty hunters](https://techdator.net/class-action-law-suit-hit-sprint-att-verizon-and-t-mobile-for-selling-customers-location-data/)), so the only way to protect your privacy is through encrypting your messages like with Signal. Because of this, it doesn't matter which carrier I choose, so I chose the one most convenient and cheapest for my family.

Anyways, due to some technical difficulties, Google had trouble transferring my number from AT&T to Google Fi. This left me for a few days without cell signal, so naturally my first thought was to ask everyone I regularly text to switch to Signal. This was my chance to get my housemate to switch to Signal. Well fast forward to when my phone number finally transferred (required some arguing with Google's customer service), and my housemate still refused to download Signal. So as I'm going downstairs to heat up some dinner, I tell him I sent a text to piss him off, specifically the auto-generated Signal invite message. It reads exactly like this:

> Let's switch to Signal
>
> https://signal.org/install

I finish heating up my food and head back upstairs, and my housemate says, "Hey you never sent me a text." Weird. So I tried to send it again; still nothing. I thought maybe something was wrong with Google Fi, seeing as they had issues transferring my number earlier, so I texted a few friends. They all replied within a reasonable time frame. So I tried to text "Test" to my housemate, and the message goes through just fine. I kept alternating between texting him to switch to Signal and just random messages. Without fail, the random messages would always go through, while the Signal ones never got delivered. We tried this with another friend, calling him after a bit to see if he got the Signal invite. He didn't even know that I sent him a message. 

This is when I went downstairs and wrapped tin foil around my head. I felt like a secret plot was unfolding before my eyes, and that secret agents were going to close in on my location at any moment. I had to protect myself. All the warnings that we're being watched were sounding true. What else are they hiding, lizard people? That paranoia passed when I realised my whole blog already shows I'm onto them, whoever they are.

I sent more texts to my housemate over the next few days, occasionally asking him to switch to Signal. He has yet to receive a single link about Signal, but every single one of my other texts. I've sent him plenty of other links, including ones that were to somewhat suspicious sites, so it isn't that Google is attempting to block malicious links getting sent to Android devices. We aren't sure what's going on exactly, but it's not a good look for Google. The fact that Google could possibly be censoring his texts is what finally convinced my housemate to download Signal. He still keeps Android Messages for sending memes over cell signal, for whatever reason.

# A Note About Different "Secure" Messengers

Signal isn't the only app out there trying to win over the hearts of privacy-minded individuals. However, Signal is still, in my opinion, the best one. Here's a few short things I have to say about some of the common apps out there. For any other apps that you might be considering, [check out this website](https://www.securemessagingapps.com/) that compares the major ones.

## WhatsApp

WhatsApp also supports end-to-end encryption, just like Signal. In fact, it implements the [Signal protocol](https://signal.org/blog/whatsapp-complete/) for its end-to-end encryption. This is great and all, but the app is both closed-sourced and now [owned by Facebook](https://www.wired.com/story/facebook-messenger-whatsapp-instagram-chat-combined-encryption-identity/). Because of this, we don't know if and how Facebook has modified the Signal protocol to potentially add ways to read your messages anyways. And of course we can trust Facebook to respect our privacy, [right](https://www.forbes.com/sites/daveywinder/2019/03/17/facebook-privacy-update-mark-zuckerbergs-response-to-cambridge-analytica-scandal-one-year-on/#55a1268c2198)? /s

## Telegram

According to security experts, Telegram [isn't actually all that secure](https://www.dailydot.com/layer8/telegram-isis-encryption-cryptography/). Its encryption algorithm was written by Math PhDs that may not know anything about encryption, and its servers hold all the encryption keys so the company could theoretically read all your messages. It also doesn't help that Telegram has yet to release their server code, so no one will know for sure if Telegram is snooping through messages. Lastly, Telegram (at least since the last time I used it in 2016) does not encrypt your messages by default. It is a feature you have to turn on, so if you insist on using Telegram, then make sure to do that.

## iMessage

Actually, y'all are doing pretty good, as shown by the FBI's failed requests for Apple's help to [decrypt some terrorists' iPhones](https://time.com/4262480/tim-cook-apple-fbi-2/). Keep doing you, iPhone users. Please stop supporting overpriced tech, though.

## Signal

We've talked about Signal all throughout this post, so I'll keep it brief. The app has gotten really good reviews from [security audits](https://www.cyberscoop.com/signal-security-audit-encryption-facebook-messenger-whatsapp/). It's free and open-source. Additionally, Signal is run by [a non-profit](https://signal.org/blog/signal-foundation/) and have committed to never becoming for profit, although there is no guarantee that we won't see "Telegram by Facebook" in the future. It might be the best choice for Android users. For iPhone users that want to switch, apparently iMessage won't allow you to import your old messages (probably due to encryption differences) and it won't let you set Signal as your default messaging app. But that's whatever; keep doing you, iPhone users.

## The Others

I don't really have the drive to download every "secure" app on the Google Play Store or F-Droid, so can't say too much about Wire, Viber, Wickr, and whatever else is out there.