---
layout: post
title: TILvids Update - April 2022
---

Welcome to April 2022, TILvids community! Let’s take a look at what was happening at [TILvids](https://tilvids.com) over the last month:

- So, a funny thing happened on the way to the blog update. I have a calendar reminder set to write up a blog post at the end of the month, but my reminder series went out and I forgot to post last month! I said to myself, "Oh well, it wasn't a big month, I'll just squeeze March and April together, since there's probably not a lot to report..." Famous last words, as it turns out. I noticed toward the last week or so of March that the site was loading really slowly, video thumbnails weren't showing up on social media, etc. I reached out to the Yunohost community (we use their technology to admin the site) and they said that the 4.1.0 release might have some issues, and that updating to 4.1.1 should hopefully clear it up. I usually lag our instance behind a few weeks after updates, just to let the dust settle a bit, but it was bad enough that I opted to roll the dice. Oops. Upon initializing the update procedure, there were a number of errors that occurred. The system ended up bailing on the install, but it left the server in an inoperable state. I had to spend the next few days talking between the PeerTube and Yunohost communities to even track down what was happening. In the end, I had to manually dig into the PeerTube service and delete a plugin to support Chromecast playback that appeared to be no longer compatible with PeerTube, along with deleting over 150 database records that somehow became duplicated. All in all, it took about three days to get to the bottom of what was happening, but happy to report that the server did recover after that, update 4.1.1 was rolled out, and it appears the original problem I was trying to solve did indeed improve after the update. Lots of lessons learned and things to think about coming out the other side of this, but ultimately, just happy everything is back to a working state again. Thanks for hanging with me while I tried to sort it out!

- In more positive news, happy to welcome new TILvids creator [LINMOB](https://tilvids.com/a/linmob/video-channels) to our community, who is making some great FOSS hardware content! Also happy to welcome [v_brigham](https://tilvids.com/c/v_brigham_channel) who is bringing some neat Commodore 64 and other retro dev topics. We're excited and thankful to have our new creators sharing with the TILvids community. Welcome aboard!

- The question pops up from time-to-time, about what my goals are for TILvids and the community. I've touched on that before in [previous blog entries](https://blog.tilvids.com/TILvids-Update-May-2021/), but expounded on it in a few different ways in [this Reddit reply](https://www.reddit.com/r/tilvids/comments/tr65yr/2_questions_about_tilvids/) so I thought it was worth sharing here as well. Ultimately, I really want TILvids to be a positive force in the tech world that is driven by a sense of community. I drive most of my decisions about the site with that foundation in mind.

- I had a request to track some of the site stats. As of April 1st, 2022, we currently have 105,925 video views, 1502 users, and 193GB of local videos. It's worth keeping in mind that many instances don't clear out the spam accounts, but I do try to keep on top of that, which is deflating our total number of users (but is, in my mind, very much worth it).

Here are a few thoughts for May:

- Better backups. I could have saved myself a lot of heartburn by having a more robust backup strategy. It's a challenge, since I don't host TILvids locally and our database of videos isn't exactly small at this point. I've already made a few changes that should help make it better going forward, but I still want to investigate more.

- Server migration. While trying to fix the server issue, I had a good chat with some folks on our chat servers, and they tipped me off to some different hosting options that not only have better resources, but also might even reduce costs a bit (which is something that needs to be done to ensure long-term viability of the site). I'm going to investigate that a bit. I don't want to make any changes just yet, coming off of all the excitement from last month, but it's on the roadmap, so expect some changes there at some point.

I think that's it for now! Thanks so much to everyone for continuing to watch, comment, share, and support the [TILvids](https://tilvids.com) community! ❤️

![image](https://user-images.githubusercontent.com/69435791/161336613-36445ba5-43bb-4d34-9311-725c94d4e6a0.png)

(this image taken during a break period from trying to fix the outage, for posterity...)
