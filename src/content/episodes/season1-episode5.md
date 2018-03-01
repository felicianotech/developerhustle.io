---
title: "Season 1 Episode 5: Work In Progress (wip.chat)"
date: 2018-02-26T12:30:00-05:00
description: |
  In this episode we discuss Work In Progress, a new online community of makers geared towards motivating each other to ship projects.
efile: "developer-hustle-season1-episode5.mp3"
duration: "0:22:24"
---

## Audio

<audio style="width:100%;" controls>
	<source src="http://dl.developerhustle.io/developer-hustle-season1-episode5.mp3" type="audio/mpeg" />
</audio>

Other Places To Find This Episode:

- [Our podcast RSS feed](https://DeveloperHustle.io/episodes/index.xml)
- [iTunes](https://itunes.apple.com/us/podcast/developer-hustle/id1338544467)
- [Google Play Music](https://playmusic.app.goo.gl/?ibi=com.google.PlayMusic&isi=691797987&ius=googleplaymusic&apn=com.google.android.music&link=https://play.google.com/music/m/Iurdet57b3zqqvalbsksrvbinse?t%3DDeveloper_Hustle%26pcampaignid%3DMKT-na-all-co-pr-mu-pod-16)
- [Stitcher](http://stitcher.com/s?fid=165580&refid=stpr)

## Show Notes

- [Work in Progress (wip.chat)](https://wip.chat/)
- [Telegram](https://telegram.org/)
- [Ricardo on Telegram](http://t.me/felicianotech)
- [Will on Telegram](http://t.me/willblew)
- [Will's blog post on Developer Hustle](https://willblew.com/2018/02/20/podcast/)

## Transcript

**Ricardo:** Welcome to Season 1 Episode 5 of Developer Hustle the podcast about tech side projects and the people who make them. We’re your hosts Ricardo Feliciano and Will Blew. So, Will, it’s been a little while for us about what? A week and a half? Two weeks and a half since we’ve recorded I guess?

**Will:** A week and a half I think. 

**Ricardo:** Oh, it’s been a little bit. How’s your week been? 

**Will:** Good. I started off pretty poorly, got a root canal but it was fine. And then I got some stuff done. I mean it’s been probably two days since I got anything serious done. But, beginning of the week I fixed the band system for <https://Krl.io> because it was being abused not anything malicious really but just too much volume and not real content, and then I started testing vanity nameserver system and I’m having pretty good results and I can even support SSL certs so got pretty far with that but nothing deployed just testing on my end. I fixed a bunch of stuff with Coinstreams error handling because Twitter tends to spit out ridiculous characters of all types and in Python it’s real easy to not handle them correctly and then just kinda taking a little rest here. ‘Cause I’m gonna start pushing a little bit harder starting probably Wednesday or Thursday and we got somebody who’s gonna join us for the next episode too so that’ll be nice.

**Ricardo:** Yeah. I’m definitely excited for that. Can’t wait. Curious, so, you said you’re going to be gearing up a little bit is there any particular reason for that? Any specific thing that triggered that? 

**Will:** No, I just tend to go in like groups of really high velocity output in medium and low kind of like go back and forth. So I kind of anticipate those so I can line up my tasks and timelines and time boxes for all the stuff before I jump in. How was your week?

**Ricardo:** My last two weeks have been a little tough. So, anyone who’s listening remembers I’ve been traveling a little bit. I went to Seattle and then I went to San Francisco and I finally got back to New York and things collapsed a little bit for me so the minute I got back I picked up my car and drove it and within fifteen minutes of me driving I heard a popping noise and the whole car kind of just stopped and apparently I blew my transmission. So, that was fun. [Will: Oh man, that’s the worst.] Yeah, exactly. And my car itself isn’t too old but I’ve put a lot of miles on it. I’ve driven it a lot and it’s already over 140,000 so I was kind of confused trying to figure out what to do with it. I couldn’t drive home so I ended up getting a hotel for a little while and a rental car and spent way too much money and way too much stress focused on this problem. So, unfortunately for me I didn’t really get a lot of projects done. But, before I flew back in I did get that first Hugo newsletter release out. So, the Hugo newsletter like February issue that did go out. Went out to sixty plus people I didn’t really hear from most people which I assume is a good sign. Except for this one random guy who just emailed me back and said he loves it especially the theme section he was like being able to find themes easily and see what’s new that’s a good feedback for the first issue that was exciting I’m happy something went well. And yeah, I did the first Ubuntu logo San Francisco meetup in San Francisco right before I left the day before and we barely had anybody show up but we did have one person show up and it was fun we kinda just talked we didn’t just talk about Ubuntu. We talked about Ubuntu, MacOS, Apple and some other stuff it was a good first start. We’ll be gearing up for the next meetup soon and hopefully I do a NYC Ubuntu meetup at some point. I don’t know lastly, I think the last thing is I organized a Write the Docs NYC meetup and we were supposed to have that on Wednesday but we had low turnout for RSVPs we just cancelled it so that’s unfortunate but, I’m trying to present for March like I said I work with Hugo a lot so I’m gonna try to do something with building doc sites with Hugo and see if that catches anybody’s interest so hopefully March will have some more RSVPs and we’ll see what happens. Like I said the past two weeks have been kind of low progress for me unfortunately. 

**Will:** No that sounds like you did as much as you could with the situations going on. I actually had my battery die the other day it stunk. I did forget to mention something I wrote my blog post and it’s on my blog at <https://Willblew.com> and I’m gonna reference it so I wanted to make sure that I mentioned that I did actually do that too. 

**Ricardo:** Cool, yeah, I will make sure we put that in our show notes as well. [Will: Sweet.] Yeah that’s gonna be a good read for people. So, Mr. Blew what are we talking about this week?

**Will:** I believe we’re talking about work in progress.chat so, wip.chat. It’s really hard to describe honestly but...

**Ricardo:** Yeah honestly, I wasn’t even sure how to say it I wasn’t sure if you call it "whip" if you call it "Work in Progress" I wasn’t even sure about that.

**Will:** I think either way it works but it’s essentially a productivity tool for makers. So you can use it how you want is what I found. Has a question section where you can answer and ask questions about all sorts of things and you can get feedback there and you can read people's feedback and get advice from that feedback there’s tons of really good questions. You can also use it as a to-do list but it doesn’t really work as a traditional to-do list that you’ve probably used before which is honestly what I like about it. So, you can close to-dos, you can open to-dos and all sorts of things with the to-dos tasks whatever you want to call them. Essentially it all runs through a Telegram bot you can close them on the website and I think you can edit them but you definitely can’t make them unless I’m really missing something big. I haven’t been able to find that but essentially you send this bot commands including the sign-in command after your account is setup and you manage everything with that so you do /to-do put the title for the to-do in it and it’ll be in your pending section on the website and you can list it via the bot and when you wanna close one just /done with the name of it is and through doing these actions you actually get streaks. So everyday you do one it adds to your streak if you miss a day you lose that streak. Looks like you can even recap your last streak or current streak to see what you got done during them and it’s really interesting.

**Ricardo:** I like the concept of streaks and I believe if I remember correctly you were an Ingress player correct?

**Will:** Yeah. 

**Ricardo:** One of the things I like about Ingress was those badges and I’m not even going to try and pronounce the name of that badge but basically it awarded you for streaks for consecutive days of hacking portals. I’m a big fan of gamifying with any kind of system you can as long as you know you do it the right way and you’re promoting the proper activities and actions. So, that sounds kind of fun and what interests me about Work in Progress is I actually attempted to use it a long time ago not a long time ago but when it first came out at the time you needed a Telegram account to sign up. I don’t really like signing up for too many new accounts. I’ve seen a few big makers, builders, whatever you want to call them on Twitter using it so I figured I’d give it a try and I couldn’t sign up for Telegram. So, I used Google Voice for my phone number and I’ve used Google Voice since 2009 so I’ve had the same number for a really long time I don’t feel like changing that setup. And I went to Telegram.com or whatever the website was signed up and they would not accept my Google Voice number so there was no other way for me to sign up so I gave up on everything. Fast forward I was at the Snapcraft summit and they were considering using Telegram for communications for the summit. So I told them my story but I said I’ll try again. I tried again it worked signed up I know have a Telegram account. My username is `FelicianoTech` on there. I have yet to sign up for Work in Progress so I have some questions for you in order to see if maybe this is something that I might be interested in. So, one of my questions for example, is, is it worth the money? And I say that because I don’t know if at the beginning they were charging but when I saw that you started using it. I was like hmm maybe I’ll try it. Went to the website and there was a paywall call me cheap I’m not a fan of paywalls. I pay for very little things Buffer being one of them I tend to use tools for free first when they have a free tier and only if I feel like I’m getting value out of it that’s usually when I then bump up and spend money same thing with Reddit for example, I use Reddit for free but I’ve enjoyed it so much that I’ve actually bought Reddit Gold and given it to people on occasions. As far as I can see, there is not free tier for this right? You just have to pay?

**Will:** I don’t know for sure honestly, it looks like that but I’ve heard many of these guys that are on here and ladies that are on here, discuss the concept of fake paywalls so, I don’t know if there’s a way around it or not. I definitely have seen people who don't have the patron tag which is what you get when you pay so I don’t know if they got in before the paywall or if there’s a way around the paywall or if it’s purposely only shown and then you can click out. I have no idea it’s totally possible that that’s the case but as far as I can tell now you do have to subscribe either monthly or yearly.

**Ricardo:** When did you sign up?

**Will:** I don’t remember. It was probably two weeks ago though like at the latest. 

**Ricardo:** I would give it another look but I wanna say I tried maybe last week and I saw that paywall and that turned me off. 

**Will:** Here are my thoughts on that price and is it worth it question, is, there are two ways to look at it, where it can be worth it and it depends on you. The first being the value of the tool, the community and the advice essentially, so, you have a tool for to-do and execution tracking for if you’re finishing your tasks and then you have the tool of the question portal where you have all these makers. Every type of engineer from very beginning people to people who work for large companies or very popular companies to everything in the middle. So, those questions and answers and the ability to ask those people as a tool to improve your knowledge and help the community obviously. Then there is the other aspect which isn’t those tools but just contributing to the continuation of that conversation within the makers space and having that community have its own place that value to all of us you could argue that it’s worth that. I’m a believer in both. It’s worth both things for $20 a month or whatever the annual fee is so I have no problem continuing to pay for it.

**Ricardo:** I honestly didn’t even know there was an answer and question portion of this. So, you remember back in the day on Facebook I made that braintrust page and now I have the hacker cabinet slack which the idea behind both basically was just to get together people like us who like to make things and ask each other for advice, get feedback from each other and have it semi-private like it’s not 100% private but at the same time it’s not out in the open you have to actually sign up and get in. [Will: Yeah.] So, would you actually say this is kind of serving that purpose for you now? 

**Will:** To a degree. So I haven’t asked any questions I haven’t felt the need to but if I did I would. I have answered a couple questions nothing super technical really just like general getting things done, side project related questions so, yes, to a degree and I definitely think that just being able to read that content is also really helpful and I think that’s kinda the core principle you're looking for so it definitely could fill that void if you use it that way. And that’s one of the interesting things about this is it is what you make it. It could be one of those things is all you use it could be all the things it really depends on what you need and what you want to contribute as well. 

**Will:** Yeah, on the to-do side of things I’m fairly happy with the setup that I went over I think it was last episode of how I use Trello kind of crazily. It’s definitely missing that community aspect of it being able to share with people and answer or ask questions. So, I’m really big on community and also I need that help for a lot of my projects a lot of the times my goal is to just get it started but I’m kinda hoping for people to kinda join and submit their ideas and contribute themselves as well might be interesting.

**Will:** Yeah, and one other pretty cool little thing that they have that I don’t think is fully developed yet but is an idea and a thing that you use for submitting your products to the community. So I put Krl.io and Coinstream both in there and I’ve actually seen traffic from other sites that are listed as products and refers from here of people using those services so that was interesting to see. Not a super high volume of it but people actually looking at it and then using it.

**Ricardo:** So, we’ve talked about Product Hunt before. How well do you know Product Hunt?

**Will:** Pretty well. 

**Ricardo:** I know that Work in Progress and Product Hunt are not the same thing but the communities I would definitely say overlap and I know for a fact that there's a few people using Work in Progress that launch on Product Hunt. How would you say that they are connected? How much of an overlap is there? Or is there no overlap? What are your thoughts on that?

**Will:** I don’t think there's an overlap yet but there may be in the future. Like I said not fully developed it seems like and that’s what I thought of at first as well but right now it’s really far apart, in what they’re being used for. One is like a sharing if you want to look at it and the other is like a here’s my thing and please look at this thing and give me feedback and I’m very proud of this thing which both I’m sure those feelings are there but they’re definitely different right now.

**Ricardo:** Yeah, ‘cause the idea that I’ve gotten is that Work in Progress is definitely starting from the beginning of the journey where you know you have those to-dos and you’re trying to build something and maybe even getting ideas and Product Hunt is the end of the journey where you’re actually shipping something. But I’ve noticed with Product Hunt and following Ryan Hoover I believe is last name is the guy who created Product Hunt. They seem to be releasing more and more features that are bringing them earlier in that spectrum you know they have ship which is preparing to ship their product and having people sign up with like a launch page to kind of build anticipation and they’re creating more and more tools now to get people earlier in the process before they even get ready to launch that product. I wonder if these two projects might butt heads at all at some point in the future and there are also very different approaches where Work in Progress is on Telegram where you’re kind of communicating with a bot versus Product Hunt which is as far as I know all web app on a desktop. Anything else you wanna talk about? I think you had something you wanted to bring up?

**Will:** Yeah, my blog I mentioned something that when I wrote it I just wanted to make sure I mentioned it in regards to some of my other comments about like just start doing it and all that stuff it’s a pretty common thing with people that watch things like Gary Vaynerchuk, Casey Neistat, Tim Ferriss any of those types of guys that are just like put in the work and get it done and that’s definitely positive advice but, it’s important to remember that you do need to have a process for some things. You do need to think about things before you do them in some situations and execution does matter how you do it and if you just dive in sometimes your going to set yourself up for failure. You should identify if you need to think about how to handle a process or what order to execute in. I think it’s underrated thus far in our conversations. I think we’ve been a little bit closer to realism but in other conversations similar to what we discuss or just our motivation behind doing these things. They make it real simple like “put in the work.” Well yes, obviously you need to do things to produce results but you also need to think about it before you do it and that was all I really wanted to touch on and I put it in the blog post and I just really wanted to make sure I came back and referenced that.

**Ricardo:** Yeah, I think that’s a good point on the business side of things. Clearly, that’s really important and you have teams with managers who are trying to look out for these like certain traps that you might fall into but I think even for side projects, I tend to get real excited about projects and I think there are some aspects where it’s really easy to just do and that’s fine but there are also some things where for example, things that involve money like when I start spending money on bumping up my servers or most domain names are cheap mostly $10, $11 but once in a blue moon I’ll come across, I have some idea I search for a domain name for it and I find it and it’s a premium domain name and it costs $670 and I’m just doing it right? I’m gonna go full on this and get this started so I buy the domain name and get started for a project that may not even finish and I just dropped $600 on it. That’s probably a first world problem of mine unfortunately, but, especially when it comes to money you gotta really think about that and for anybody that has family also which I think is something that you do a really good job at is making sure you set aside time for your family for your career as well and make sure you don't get too excited and too involved in certain projects and kind of let everything else drop around you.

**Will:** Yeah, I’m okay at it now in comparison to the past. I’d say I’m good at it but it’s easy to get carried away even now so, it’s something that you have to pay attention to.

**Ricardo:** Yeah, in the coming week like you mentioned before we have our first guest. So, I’m really really excited about that I can’t wait to record [Will: Yeah] that episode that is gonna be freakin’ awesome as far as goals or my plans for the next week. It’s still a little early but I’m gonna be gearing up for the March issue of the Hugo newsletter but we’re still a little ways from that and I don’t know if I mentioned this before I have a project called Discourse Directory currently the website is Discourse.Directory and it’s basically a listing of random discourse sites from around the internet organized by category. I have a lot of plans for that and I already have another name called Discourse Hub that I’m kinda gonna move it to cause I have all these features I wanna add. I wanna add a plugins directory. I wanna add a chrome extension android app. I wanna kinda get started on that and the first step for me is going to be redesigning the site there’s actually a bug report on the project now. Where the logo kinda just goes crazy on Firefox. So, I think for this week one of my plans is going to be redesigning Discourse Directory and moving it under its future home which is gonna be DiscourseHub.com hopefully, by the next time we record I don’t know if it’ll be the episode with our guest maybe maybe not if not the episode after that I will be able to say that I got that done. [Will: Cool.] Any plans for you?

**Will:** I definitely want to continue working on the KRL API I’ve been grinding that out not as far as I would like but see how it goes keep going. I need to continue working on the vanity server/certificate support for Krl.io. And I'm taking a class in modern react development because it's a weakness for me so I have a couple of those I think it's like 13 I'll be doing some of those aside from that I'm not sure I'm not like 100% sure but those things I definitely need to focus on. 


**Ricardo:** Well I feel like you answered the question for me whenever I think of JavaScript the comment joke is that there’s a new JavaScript framework every week. I think everyone could agree there's a few large players there React, Angular, Ember for example, I'm guessing you're saying you would agree that React is If anyone is just starting fresh for example, React is probably where you should spend your energy versus the other two?   

**Will:** I don’t know that’s tough. I think it definitely is one you should start with but I think they all have their place and you can definitely find work with any of them. I would go React if you’re in my area because my company has that as a technology that’s on our job site but there are many others that do as well and I think it applies to any of those but I like React and I think it’s a big player for sure. 

**Ricardo:** I’m a big fan of Facebook. You know, people can have their opinions on what they do with our data I guess and certain like political or personal privacy issues but in terms of Facebook tech, everything they do in the tech side with them pushing GraphQL and everything they’ve done with PHP and now React I’m real excited for those projects. Yarn for example. [Will: Yeah. Yarn’s great] Yeah, that alone is why I myself am gonna try React just to kind of try something different see how it is. I’m old school so I very much code all of the front end myself so I’m trying to see if I can change that up a little bit see what’s out there.

**Will:** Yeah, it’s definitely worth checking out.

**Ricardo:** Cool, anything else you wanna discuss this episode?

**Will:** No, I think that about covers it. I mean the next episode is gonna be really fun and I’m excited. 

**Ricardo:** Yeah, me too. So yes, everybody definitely stay tuned for I guess that would be episode 6. We will be having our first guest on the show I am really really excited and if you’re interested in being a guest you can definitely contact us. Where you can contact us? We have our website Developerhustle.io. You can contact us at Twitter at <https://Twitter.com/DeveloperHustle>. Facebook at <https://Facebook.com/DeveloperHustle>. We don’t have an email address yet do we? 

**Will:** No, I don’t think so.

**Ricardo:** Should we ever?

**Will:** I don’t know, I mean, Twitter’s pretty easy.

**Ricardo:** Email too old school? 

**Will:** Email to Twitter.

**Ricardo:** Oh! What about Telegram?  

**Will:** Telegram me at...what is it? I don’t even remember what it is. I’ve just been using it. 

**Ricardo:** One of the podcasts I listen to regularly is the Ubuntu podcast and one thing I always hear on their show is that they have Telegram so they actually have a Telegram account for the podcast. So, anyone can submit questions. Honestly, I haven’t used Telegram too much myself maybe there’s like a group chat kinda thing.

**Will:** There is. There’s one for Work in Progress. I can’t even find my username on here it doesn't even show me. I don't remember having a username. I’m sure I do but…

**Ricardo:** I know I do. So, how about this...

**Will:** Here it is, it just says Will Blew.

**Ricardo:** Yeah, your name’s easy.

**Will:** It’s just Will Blew.

**Ricardo:** Okay, so, we’ll put our Telegram usernames in the show notes and perhaps maybe by next episode we’ll have a Telegram account for the podcast itself we’ll see. 

**Will:** I’m down.

**Ricardo:** Alright well, nice talking to you and we’ll see you guys next week. 

**Will:** Thank you.

**Ricardo:** Bye.
