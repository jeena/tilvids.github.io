---
layout: post
title: TILvids Update - April 2021
---

Welcome to April 2021, TILvids community! Let's take a look at what was happening at [TILvids](https://tilvids.com) over the last month:

- A big TILvids welcome to new content contributor [Polarhive](https://tilvids.com/video-channels/polarhive)! He's bringing some great shows about privacy and open-source, so make sure to check out his channel!

- Our self-uploading crew continues to push out lots of great new content for the TILvids community! Thanks to [Vex0r](https://tilvids.com/accounts/vex0r), [PizzaLovingNerd](https://tilvids.com/accounts/pizzalovingnerdtilvids), [GeoTech](https://tilvids.com/accounts/geotechdigital), [Athena Productions](https://tilvids.com/accounts/athenaproductions), [The Attic Dwellers](https://tilvids.com/accounts/theatticdwellers), [Tyler's Tech](https://tilvids.com/accounts/tylerstech), [Always Asking](https://tilvids.com/accounts/alwaysasking), and [the Pine64 Community](https://tilvids.com/accounts/pine64tilvids) for continuing to share their content!

- Some unfortunate news about the NewPipe mobile client. After some user reports that TILvids videos were no longer loading, we [tracked the issue down](https://github.com/TeamNewPipe/NewPipe/issues/5964) to a switch we made to using PeerTube's HLS streaming option instead of WebTorrent. Because this is now the recommended streaming option from the PeerTube developers, we're going to keep it configured that way, but unfortunately it means that NewPipe's mobile client won't work until they implement this method of streaming support. Make sure to let them know if this is important to you!

- I had a request to track some of the site stats. As of April 1st, 2021, we currently have 69,681 video views, 615 users, and 145GB of local videos.

Here are a few thoughts for April:

- I get asked a lot about why TILvids doesn't federate with the larger PeerTube ecosystem, and there are two main reasons for this. First, there is a *lot* of questionable content across the ecosystems, and this has given PeerTube a bad reputation. I started the community with the hopes of changing this reputation by curating the creators that share with the community. Second, some of the creators sharing on TILvids want their content associated with "TILvids", and not federated PeerTube, so I want to be able to respect those wishes. That said, I really don't want TILvids to become a complete island. What I'd love to see happen is for some of the creators on TILvids that grow their own following to start up their own personal instances, and then federate back/forth with the larger TILvids community. This will help the community to grow beyond just TILvids, and we can all help each other rise. This is a long-term vision, but one that I think will be healthy in the long-run.

- In March, we finally hit the point where it was time to add more space again. This also meant the next tier of service doubled our processing (from 2 to 4 vCPUs) and memory (from 4 to 8GB). I've noticed the site running a lot faster, and it's also able to process and transcode more videos, so they go live more quickly. All of this comes at an additional cost though. Up until now, we've been fortunate to have enough donations to offset the cost of running the site, but we're starting to get close to needing more, if we want to be able to add additional space. If you enjoy the videos shared in the TILvids community, and want to help it continue to grow, [donating is a great way to make that happen](https://www.patreon.com/tilvids).

- As always, please continue to spread the word online! Every month our community continues to grow, and this just makes it easier to convince new creators to give it a shot. If you want to see TILvids continue to get new creators, sharing the site is the best way to do it!

I think that's it for now! Thanks so much to everyone for continuing to watch, comment, share, and support the [TILvids](https://tilvids.com) community!
