+++
date = 2020-01-31T23:00:00Z
tags = ["privacy"]
title = "Breaking the Chains #3 - Taking Care of Your Online Accounts"

+++
**tl;dr** Delete old accounts. Use a password manager to generate new passwords for the accounts you keep. Turn on two-factor authentication. If you really don't care enough to secure your accounts, email me your account details (Don't actually do this. [It's illegal](https://www.eff.org/deeplinks/2016/07/ever-use-someone-elses-password-go-jail-says-ninth-circuit)).

I got my first email address, tranngocnam97@yahoo.com, in 2011 when I bought Minecraft Alpha. Nearly a decade later, I decided it was finally time to retire the email. One of the biggest challenges I faced when doing this was handling all the accounts that I had registered to that email over the course of a decade. This past week has made me realise just how many accounts I've had to make over the years. I'm sure I'm not the only one that has to delete 74 accounts (and counting), so I hope me writing about my week's experience helps inspire someone to take similar steps.

_Curious why I'm writing these posts? Check out the_ [_intro post_](https://omn0mn0m.github.io/blog/breaking-the-chains-1/)_._

# Making a List of All My Accounts

Fortunately for me, I apparently didn't believe in deleting emails once upon a time. This meant that my inbox of over 4000 emails was a perfect record of every account I ever owned. I used this to my advantage. Every time I removed an account, I deleted any emails relating to it other than a confirmation of account deletion.

In addition to my inbox to find my old accounts, I also used [Have I Been Pwned](https://haveibeenpwned.com/ "Have I Been Pwned") to see if any accounts registered to my email had ever been part of a data breach. The site keeps track of every data breach, and tells you which accounts associated with an email have been breached.

# Deciding What to Do With Each Account

Once I had had my list of all my accounts, I had to figure out what to do with all of them. I decided that there were three courses of action I can take for each account: delete the account, change the email to my new email, change the email to my new spam email. To decide which course of action to take, I asked myself the following questions.

## Do I still use the account?

**Yes: Migrate it to a new email. Decide which email in a future question.**

**No: Delete it.**

This is the simplest and most straightforward question. If I still actively use an account, I'm going to want to keep it. If I don't use it, why would I want to keep it? There's really no reason to keep an account that I don't use, especially since each account I own is another piece of data that can be sold about me. I'd say about 75% of the accounts I deleted over the past week were sentenced to death by this question alone.

The only weird scenario was when I found accounts for services that no longer existed. This happened primarily with MMOs and other multiplayer games I used to play, such as Marvel Heroes (AKA Marvel Heroes 2015 AKA Marvel Heroes 2016 AKA Marvel Heroes Omega). Multiplayer servers are expensive to keep running, so it makes sense that they would one day close down. In cases like this, I attempted to contact any email I can find or just accept that there will be some random mobile RPG account floating around somewhere.

## Are there better services that do the same thing?

**Yes: Delete it (and make sure the better service gets migrated to the new email).**

**No: Migrate it to a new email.**

Before I knew that you can search reviews for a program before you sign up, I used to trial a bunch of them and delete whichever ones I didn't like. Unfortunately, high school me made some weird software choices. I took this time to look at each account I made, and decide if I have have since found a better alternative. Deleting accounts that I have since found better alternatives to accounted for almost the other 25% of accounts I deleted.

We'll talk more in the future about finding better alternative software/services, since that is the bulk of my efforts to take back my digital freedom. For now though, you can do your own research if you want by using [AlternativeTo](https://alternativeto.net/) to find alternatives that work for you.

## Has this website been known to have data breaches?

**Yes: Delete it (or change the password if you still use the service).**

**No: At least, not yet.**

The first time I considered deleting my Yahoo! account was when it was announced that they had a data breach, resulting in a [$117.5 million class-action settlement](https://www.usatoday.com/story/money/2019/10/14/yahoo-data-breach-117-5-million-settlement-get-cash-monitoring/3976582002/). Yahoo! isn't the only place that I had an account compromised by a data breach, however. I found 12 different breached accounts when searching up my Yahoo! email on [Have I Been Pwned](https://haveibeenpwned.com/ "Have I Been Pwned"). Most of these sites, I haven't touched since high school such as [Edmodo](https://www.vice.com/en_us/article/ezjbwe/hacker-steals-millions-of-user-account-details-from-education-platform-edmodo), an education platform I had to use during French II and basically nothing else.

## Is this account used to send voluntary spam email to me?

**Yes: Migrate to a spam email.**

**No: Migrate to a legitimate email.**

For whatever reason, my friends and I go to TGI Fridays a lot. Because of that, I signed up for the TGI Fridays Rewards program a long time ago. To stay eligible to earn rewards points, you have to let TGI Fridays continue to send promotional emails to you. For cases like this, I created a new email account for just voluntary spam mail and newsletters.

# Migrating Account Emails

Okay guys, so I'm going to talk about all the bad practices I did as a middle/high school student with my online accounts, and what I had to do to fix them. Please don't laugh, and remember to review your own accounts to make sure you didn't do the same things.

## Reviewing Your Account Info

Having an abundance of information about yourself available online is clearly an issue, yet for young me, I guess the mentality was, "The more info I give, the less likely someone thinks I'm a catfish." Going through my accounts, I often found the following information set as publicly available.

* My full name (including middle name in some cases)
* My full mailing address
* My phone number

Yeah, I'm not sure what I was thinking at the time. I deleted all of it, leaving just my first name where possible. For any information that the account needed to keep to operate, such as my phone number, I set it to private information.

While I was at it, I also deleted a lot of posts and rather cringey fan fiction. That was more for my pride than my privacy/security.

## Changing Your Password

To delete each of my accounts, I had to log into the account first and then go to the Account Settings. I think out of all the accounts I deleted, I only had to reset my password 5 times. For the rest of them, I had used the same password as all my other accounts I made between 2011 and 2015. I don't think you need a cybersecurity expert to tell you why that's an issue. Naturally, I changed every single one of my account passwords.

### Use A Password Manager

Rather than trying to remember new, long passwords, I just started using a password manager. This way, I can have extremely long, random passwords without having to worry about forgetting them. There are a lot of password manager options out there. The main things I look for in a password manager are the ability to randomly generate a long password, and the availability of cross-platform software (mobile apps and desktop apps).

I personally went with [Bitwarden](https://bitwarden.com/) because it free and open source. Your passwords get synced on the Bitwarden server, so you can sync your passwords between your phone and your desktop. This does pose a security risk since you are allowing your passwords to be stored on someone else's server, but the [server software is available](https://github.com/bitwarden/server) for self-hosting if you want to do it yourself.

Some other popular choices include using Firefox's default password manager and[ Keepass](https://www.keepassx.org/). I did not go with Firefox's password manager because it uses a weaker encryption method than most password managers, making it easier to decode your passwords. I did not go with Keepass because then I would have to manually (or automatically using [syncthing](https://syncthing.net/)) sync my passwords between devices by moving a file around. If you want to go this route since it is much more secure (no internet access), you can [follow this guide](https://appliedcaffeine.org/using-keepassx-and-syncthing.html) to set it up.

### Randomise Your Password Manager's Master Password

The one issue that comes with this is that all your passwords can now be accessed if someone knows your master password to open your password manager. To decrease the likelihood of this happening, I used dice to get my master password. The steps are described [in details here](https://www.eff.org/dice), but I'll summarise them below as well.

1. Roll dice until you get 6 groups of 5 numbers.
2. Match each group up to a word in a word list.
3. Use that as your password.

The resulting password is going to be 1 of 221073919720733357899776 different possible passwords. Since the password will consist of 6 words, rather than a bunch of random letters and numbers, it should also be relatively easy to remember. If you are concerned about forgetting your password, you can always write it down somewhere and store it.

## Enabling Two-Factor Authentication

In case someone is able to breach my password manager, I have two-factor authentication (2FA) enabled on all my accounts whenever possible. For anyone that isn't familiar with 2FA, it's a generated code sent to you after you sign in with your normal password. The logic behind this is that some random person in another country might be able to guess your password, but they won't be able to steal your phone and look at the verification code sent to your phone. Without the verification code, the account won't log in even if someone knows your password.

This doesn't have to be the form of an annoying text message with a code you type in, by the way. In almost all cases, I was able to set up an authentication app to give me the verification code. For Android, I've been a fan of [Aegis Authenticator](https://github.com/beemdevelopment/Aegis).

# Deleting Accounts

The bulk of my accounts got deleted, so this section is going to be the longest section. Now that all the accounts I care about are protected and I can sleep well at night knowing no one is going to log onto my Facebook (getting rid of that btw), it's time to Thanos-snap the rest of my accounts away. This is a lot easier said than done, but sites like [Just Delete Me](https://justdeleteme.xyz/) exist that I used to make sure I was properly deleting my accounts.

## A Quick Note About the General Data Protection Regulation (GDPR)

While [the GDPR](https://gdpr-info.eu/) was created by the EU to protect EU citizens, the law applies to any company that provides a service to EU residents. This means that companies like Facebook are required to comply with the GDPR, even though they are US-based, because they have EU users. Most [US companies have decided to comply](https://gdpr.eu/compliance-checklist-us-companies/) with the GDPR instead of facing violation charges, but there are a few companies that have shut their services to the EU. For companies that refuse to comply and would rather lose their European customer base, I would strongly recommend not using their services any further if possible. It's an indicator that they may be doing something shady with your data. For companies that do comply with the GDPR, this means you have the right to delete your data/account from their servers.

## My Experience Deleting Accounts

### The Good

A lot of websites have made it really easy to delete accounts. In those cases, for the most part all I had to do was click a "Delete Account" button. One thing I had to keep in mind was if there was both a "Delete Account" and "Deactivate Account" button. Deactivation normally just means that it clears your info from public viewing, but your account will resume like it was just dethawed from a cryo chamber if you try to log back in ever. That is less the optimal if you are trying to prevent people from hacking into your account and pretending to be you. I made sure in those cases, I pressed "Delete Account" by trying to log back in. If your account was deleted instead of deactivated, you won't be able to.

One of my most positive account deletion experiences was [Fimfiction](https://www.fimfiction.net), a My Little Pony fan fiction site. The process went exactly as follows.

1. I logged in. Surprise: my password was the same password as all my other accounts from high school.
2. I hovered over my username, and clicked "Account".
3. Right next to "Save Changes" was "Delete Account". I clicked it.
4. For my reason for leaving, I selected "Cleaning up an unused account".
5. I confirmed my password, and I was done when I clicked "Delete Account".

They did give me this disclaimer:

> Deleting your account is **PERMANENT**. There's no going back. All your stories, blog posts, comments, etc will be gone for good. This includes any groups you have created too. Make sure you are 100% certain before filling out this deletion request.  
>   
>  Deletion requests have a minimum waiting period of **24 hours** during which time you can change your mind if you wish to. You will be emailed at **tranngocnam97@yahoo.com** when your account is deleted.   
>   
> If you require more expedient deletion for some reason, please contact knighty@fimfiction.net.

I appreciate that they gave me an option to expedite my account deletion, even if I wasn't in that much of a rush to delete my old fan fiction.

### The Meh

In a few cases, I had to contact customer support. These were a pain, and are the reason I have yet to delete my Yahoo! email. Many companies note that correspondence through the account email works best to speed up the account deletion process. Because this is a manual process, I still have a few open support tickets for account deletion. In no case so far, though, did I have a company refuse to delete my account.

### The Bad

There were a few cases where I could not delete my account, however. In cases like that, I just changed the account email to my new spam email so I can delete it in the future if the option becomes available.

One weird case I am dealing with right now is Netflix. I've had an open ticket to their customer support since Monday asking them to delete my account. They have yet to respond, while much smaller companies I emailed have already deleted my account in less time. Almost like a caged animal, Netflix has actually started to email me again for the first time in 6 months, at one point giving me a link to "Complete my account signup". Clicking it gave me an offer for a 10-day free trial if I gave them my credit card information, since I stopped paying for Netflix in August. This is good and all, but since when did I sign up again for Netflix? I was trying to close an already existing account that had been "completed" since 2015. Behaviour like this really makes you question whether you should trust a company, doesn't it?

# Conclusion

After a surprising long week of account deletions, I am almost done moving away from my Yahoo! account by handling all my old registered accounts. I feel a lot better at night knowing that I have a strong password and require a phone confirmation to log into the accounts I still use. And most importantly, I won't have a random My Little Pony fan fiction lying around with my name on it anymore. This was an extremely important step in taking back control of my digital presence, since there are (at least) 74 less traces of me floating around on the internet. 

For anyone who has read this far, I highly recommend you also take a look through all your old accounts. And don't use the excuse that you don't care enough to go through the effort of generating secure passwords and deleting accounts. If you really don't care, feel free to send me links to your old account profiles (Don't send me your passwords. [That's illegal]()). If the thought of me being able to see your account profile makes you cringe, you probably should take the effort to review you accounts a bit.