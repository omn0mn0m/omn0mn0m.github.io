+++
date = 2020-01-23T05:00:00Z
tags = ["privacy"]
title = "Breaking the Chains #2 - Why I Chose Firefox Back in 2011 (and Stayed)"

+++
**tl;dr** Switch to [Firefox](https://www.mozilla.org/en-US/firefox/) instead of whatever other web browser you're using.

One of the darkest secrets I am willing to admit is that I used Internet Explorer until my sophomore year of high school. I was still using the family computer to do schoolwork at the time, and like many family computers, it was heavily guarded by my parents. I wasn't allowed to install anything onto it. This was the case until I joined my high school robotics team. Somehow, my involvement in an engineering extra-curricular made me suddenly qualified to do whatever I wanted to the family computer. So the first thing I did was install [Firefox](https://www.mozilla.org/en-US/firefox/), since I thought the logo looked cooler than Internet Explorer's and I had seen all the memes about IE being garbage.

Side note: Prior to being given free reign, I secretly was running a Minecraft server on the family computer so Firefox wasn't the first thing I ever installed on the family computer... But my Minecraft server deserves a blog post of its own.

It's been about 7 years since I first installed Firefox on a computer because I liked the logo. I still install Firefox on any computer I obtain, but for much more legitimate reasons now. As part of my blog series on gaining back my technological freedom, it makes sense that the first software I talk about is a web browser since nothing I do would matter if a company can still see everything I do through my browser.

_Curious why I'm writing these posts? Check out the_ [_intro post_](https://omn0mn0m.github.io/blog/breaking-the-chains-1/)_._

# 5 Reasons I Use Firefox

Let's start by discussing why I personally still use Firefox, which should hopefully also serve as reasons why you should switch to using it.

## 1. Firefox is free and open-source

Free and open-source software (FOSS) doesn't necessarily means that a software is more secure and privacy-respecting, but it does mean that any data collection code is out in the open.  It also means that I get to do what I want with the software without being tied down by seemingly endless EULAs filled with legalese. Firefox has and always will be released as [FOSS](https://github.com/mozilla). While both Microsoft Edge and Google Chrome are based on the open-source Chromium project, the distinction is that they are **based** on an open-source project. The final code that runs on your computer isn't freely available for scrutiny, meaning it's extremely difficult to know what the browser is actually doing behind-the-scenes.

## 2. Mozilla, the company that develops Firefox, is a non-profit organisation

This means that Mozilla isn't trying to make money from your data, receiving their operational budget through donations instead. Mozilla has been vocal on their [stance regarding digital rights](https://foundation.mozilla.org/en/advocacy/) in the past, building up trust in its users including myself.

> "Firefox is built by a non-profit. That means we can do things that others can’t, like build new products and features without a hidden agenda. We champion your right to privacy with tools like Private Browsing with Tracking Protection, which go beyond what Google Chrome and Microsoft Edge offer."
>
> \- [Mozilla website](https://www.mozilla.org/en-US/firefox/features/independent/)

In comparison, Google makes [116.32 billion dollars](https://www.statista.com/statistics/266249/advertising-revenue-of-google/) in advertising revenue. I wonder which company is more likely to sell your data to advertising companies? I don't think I have to explain [why Microsoft can't be trusted](https://www.gnu.org/proprietary/malware-microsoft.html) to respect your privacy. While trusting the people who make your software isn't necessarily an indicator of good software, it definitely helps in easing my concerns for my privacy.

## 3. Ad-blockers actually work in Firefox

Google announced Manifest v3 in 2019, which included changes that would supposedly make Chrome more secure. These changes [will make most ad-blockers ineffective](https://www.ghacks.net/2019/11/13/google-implements-controversial-manifest-v3-in-chrome-canary-80/) by preventing extensions from intercepting web requests. I wonder why an advertising company wouldn't want ad-blockers to work on their browser. This change won't just affect Google Chrome users, but it will affect all Chromium-based browsers. This includes Microsoft Edge, leading Microsoft to ask its users if they would want an [ad-blocker custom-built to work for Edge](https://www.forbes.com/sites/kateoflahertyuk/2019/06/16/microsoft-just-dealt-a-blow-to-googles-ad-blocking-plans/#110600ea16ff) in the future. Maybe Google might actually start paying YouTube content creators now that their ads will always go through.

## 4. Firefox Sync lets me sync between my phone and my desktop

I have Firefox as my main browser on my phone, my laptop, and my gaming PC. My laptop and gaming PC both are dual-booting Linux and Windows, so in total I have 5 different installations of Firefox. Firefox Sync is a feature much like logging into Google Chrome that syncs my browsing history, bookmarks, add-ons, and customisations for all of my Firefox installations. It's not privacy related, and might actually be a bit worse for privacy, but it's a convenience that I have come to greatly appreciate.

## 5. Mozilla acts like they care :)

It's clear at this point why privacy-minded and digital rights-minded individuals would choose Firefox, and Mozilla has come to realise this. The ways that Firefox is designed to respect your privacy and your technological rights has become a major emphasis point, as seen on their [features page](https://www.mozilla.org/en-US/firefox/features/). In addition to explaining the ways that Firefox respects your freedom, Mozilla has been recently working to [add more privacy features](https://blog.mozilla.org/blog/2019/01/29/todays-firefox-gives-users-more-control-over-their-privacy/).

# How To Switch

So hopefully my reasons were reason enough for you to be itching to close your browser and reopen this blog in Firefox. Luckily for you, the switch isn't hard.

## Desktop

Mozilla has made it extremely to switch over to Firefox without much headache on our parts. All you have to do is as follows:

1. Open up the [download link](https://www.mozilla.org/en-US/firefox/new/) on your current web browser. This will be its last curtain call.
2. Click `Download Now`
3. Run the installer once it downloads (OS specific)
4. Close your current browser and open Firefox for the first time.
5. Go through the Import Wizard that pops up to import all your old stuff from your last web browser.
6. Accept the option to make Firefox your default browser when it pops up.
   * If it doesn't, click the stack symbol in the right corner > `Preferences` > `General` > `Always check if Firefox is your default browser`. Close and reopen Firefox and it should ask to be your default.
7. Delete your last web browser.

## Mobile

Honestly, I never actually stuck with Google Chrome ever on my phone, so I have no idea what the experience is like to switch over. However, the basic steps are as follows.

1. Search for Firefox on the Google Play Store (Android) or App Store (iPhone)
2. Install it.
3. Open it for the first time, and hopefully it has some sort of import tool? If not, Firefox Sync will help sync your settings from the desktop browser if you log in.
4. Disable/delete your old web browser. For Android, you have to disable it because Google won't let you delete Google Chrome.

# Making Firefox More Secure (While Still Being Usable)

## Preferences (Basic Tweaks)

By default, Firefox will already be more privacy-respecting than Google Chrome and Microsoft Edge. However, here are some settings you should check on to make sure they are enabled. I'll write a little blurb about anything that might be new to most people. Anything I don't mention is a personal preference thing and not all that related to privacy/security. You can always go further than this, but these settings should suffice for most users. One important thing to note is that these settings are for the desktop version of Firefox. The mobile app may be lacking some of these settings, so you'll have to play those settings by ear.

### General

* Under `Startup`
  * Check `Always check if Firefox is your default browser`
* Under `Tabs`
  * Check `Enable Container Tabs`
    * This allows you to place websites into a container. Each container cannot see anything in a different container, so it lets you isolate your websites from each other (for example, making sure your shopping cart on Amazon isn't read by Facebook).
* Under `Files and Applications`
  * Under `Digital Rights Management (DRM) Content`
    * Disable `Play DRM-controlled content`
      * **DO NOT DO THIS** if use any paid-for streaming services (Hulu, Disney+, Netflix, etc). We'll talk about alternatives to these services in a future post.

### Search

* Under `Default Search Engine`
  * Select `DuckDuckGo`
    * We'll go over search engines later because that's a long topic, but for now, DuckDuckGo will be fine.

### Privacy and Security

* Under `Enhanced Tracking Protection`
  * Select `Strict`
    * Even though Firefox gives you a warning about some sites not working, I have had almost zero issues.
  * Set `Send websites a “Do Not Track” signal that you don’t want to be tracked` to `Always`
* Under `Cookies and Site Data`
  * Check `Delete cookies and site data when Firefox is closed`
    * This will make it so you have to re-enter all your passwords every time you want to log into somewhere. I don't think it's that big of a hassle, but others might. Do what you want.
* Under `Logins and Passwords`
  * Check `Show alerts about passwords for breached websites`
    * Part of why I am trying to regain control over my digital life is because it seems like every website has to get breached at least once to be inducted into the cool kids' club. Knowing that a website you are logging into has been breached in the past will help you know when to change a password (or deactivate your account altogether).
  * On saving passwords through Firefox: Firefox comes with a password manager built in, which makes re-logging into websites because you don't save cookies less of a hassle. I've read good reviews for it, but also that it isn't the most secure option out there. Because of this, I don't use the built-in password manager. If you're following my blog series, I would wait for a future post about passwords before checking anything related to password saving.
* Under `Permissions`
  * Check `Block pop-up windows`
  * Check `Warn you when websites try to install add-ons`
* Under `Firefox Data Collection and Use`
  * Either uncheck or check everything. I leave it all checked so Firefox can use me as debugging and test data so they can work towards making future updates. If you're going for full privacy though, uncheck everything.
* Under `Security`
  * Under `Deceptive Content and Dangerous Software Protection`
    * Check `Block dangerous and deceptive content`
      * Check `Block dangerous downloads`
      * Check `Warn you about unwanted and uncommon software`
  * Under `Certificates`
    * Select `Ask you every time`
    * Check `Query OCSP responder servers to confirm the current validity of certificates`

### Sync

* I use Firefox Sync for convenience, but optimally you wouldn't if you care about keeping as much data about yourself off the cloud. If you do use Sync, make sure to enable two-factor authentication (2FA). Once you make an account, you can turn on two-step authentication[ here](https://accounts.firefox.com/settings).

## Add-Ons

One of the necessary features of any modern web browser is customisability through the use of add-ons/extensions. Firefox is no exception to this, and we'll be using add-ons to further secure our browser. One thing to consider when installing add-ons is that having more add-ons makes your browser [more identifiable](https://www.securitee.org/files/extensionbloat_www2019.pdf). Because of this, I have very few add-ons. The list is as follows:

1. [Facebook Container](https://addons.mozilla.org/en-US/firefox/addon/facebook-container) - This locks Facebook into its own virtual space, preventing Facebook from giving me targeted ads based on what I search for in another tab
2. [Privacy Badger](https://addons.mozilla.org/en-US/firefox/addon/privacy-badger17) - This blocks trackers that ignore "Do Not Track" signals sent by Firefox, adapting as it finds new trackers
3. [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin) - This is one of the best ad-blockers I've used and is very lightweight
4. [Invidition](https://addons.mozilla.org/en-US/firefox/addon/invidition) - Automatically redirects all YouTube and Twitter links to free and open-source versions of the sites. These versions don't track you, and also don't come with ads.

All of the listed add-ons are also on the Firefox mobile app except for Facebook Container.

# Advanced Tweaks

Even with everything listed above, many people will still consider Firefox to be spyware. In all honesty, I did not even consider that more could be done than just the basic settings I listed until I started doing more research.

I'm not going to list them all now, but instead will make another blog post once I've had a week or two to try out all the recommendations.

# Conclusion

So if you're at this point in the post, hopefully you have installed Firefox and made the basic settings changes. There are many more changes that can be made to Firefox to make it even more secure, but I'll save those for a future article after I've tried them out myself.

Chrome accounted for 67.28% of the [browser market share](https://netmarketshare.com/browser-market-share.aspx) in 2019, while the next most used browser was Firefox with 9.00% of the market share. Google Chrome may have [won the browser war](https://andreasgal.com/2017/05/25/chrome-won/) according to Mozilla's former CTO, but that doesn't mean we should all submit and use it. I will continue to use Firefox, even as they continue [changing their cool logo](https://1000logos.net/mozilla-firefox-logo/), and I highly encourage everyone I know to do the same.