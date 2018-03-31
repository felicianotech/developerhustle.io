---
title: "Season 1 Episode 6: Kyle Galbraith (guest)"
date: 2018-03-02T15:40:00-05:00
description: |
  In this episode we talk with our very first guest Kyle Galbraith about two of his side projects: a fantasy motocross league and an AWS book. We dive into both the motivations behind the projects as well as the technologies and tools.
efile: "developer-hustle-season1-episode6.mp3"
duration: "0:33:11"
filesize: 79697820
---

## Audio

<audio style="width:100%;" controls>
	<source src="http://dl.developerhustle.io/developer-hustle-season1-episode6.mp3" type="audio/mpeg" />
</audio>

Other Places To Find This Episode:

- [Our podcast RSS feed](https://DeveloperHustle.io/episodes/index.xml)
- [iTunes](https://itunes.apple.com/us/podcast/developer-hustle/id1338544467)
- [Google Play Music](https://playmusic.app.goo.gl/?ibi=com.google.PlayMusic&isi=691797987&ius=googleplaymusic&apn=com.google.android.music&link=https://play.google.com/music/m/Iurdet57b3zqqvalbsksrvbinse?t%3DDeveloper_Hustle%26pcampaignid%3DMKT-na-all-co-pr-mu-pod-16)
- [Stitcher](http://stitcher.com/s?fid=165580&refid=stpr)

## Show Notes

- Kyle Galbraith
  - [website](https://www.kylegalbraith.com/)
  - [Twitter](https://twitter.com/kylegalbraith)
  - [GitHub](https://github.com/kylegalbraith)
- Kyle's Projects
  - [Ultimate Fantasy Supercross](https://www.ultimatefantasysupercross.com/)
  - [His upcoming book's sign up page](https://www.kylegalbraith.com/learn-aws/)
- [Dev.to](https://dev.to/)

## Transcript

**Ricardo:** Welcome to Season 1 Episode 6 of Developer Hustle the podcast about tech side projects and the people who make them. We’re your hosts Ricardo Feliciano and Will Blew. How was your week Will?

**Will:** It’s been good. It hasn’t been that many days between these so I haven’t gotten a lot done but I have mapped out some stuff for Krl that I need to improve which we discussed briefly last time. Still doing the course on modern React and just kinda making sure my backups have been tested properly like actually restoring from them but, it’s going well. I got a lot of stuff done either way.

**Ricardo:** Cool. Yeah, like you said this is probably our first time I think recording in such, only what? Four days in between the previous recording so this is a fairly tight schedule. I don’t even know what I did this past week. Honestly, I’m not sure if I worked on any well, I updated Discourse Directory I added I think two more forums to it you know not really a big deal. I didn’t really get a lot done I was doing a lot of CircleCI work this past week so I’ve been fairly busy myself. So, today, we have a very special episode of Developer Hustle. Today, we’re going to be doing, our first guest. So, Will you want to introduce our guest? 

**Will:** Yeah, so, our guest today is Kyle Galbraith right? I’m saying it correctly? 

**Kyle:** Yeah. You got it man. 

**Will:** Nice. We’re gonna discuss some of his side projects. How he manages those things and some of the other things that he’s done to make those successful and be able to continue to push forward with them and implement new things and I’m sure maintain them as well. So, I was just curious Kyle if you could give a rundown for us of the things that you’ve been working on that you put out to everybody so that they know why you made these things and what they are.

**Kyle:** Sure, so, the first side project I really launched was a platform called Ultimate Fantasy Supercross and that one was that one’s focused on so there’s motocross and supercross professionals essentially motorcycle racing and I grew up doing that ‘till I was probably from 8 years old to 18 years old roughly. And what I noticed is there just wasn’t a good fantasy sports platform for that sport. So, essentially I play a lot of fantasy football like a lot of people in the U.S. and I essentially created my own version and I launched that about 2 ½ years ago and it consists of public leagues which are free to join up to five public leagues and people can invite their friends. We have Facebook, Twitter all of that stuff. And then I have monetization model which is private leagues. Private leagues you can essentially customize totally customize whatever rules you want to have. That’s the first side project I launched. Then, I’ve had a couple failed ones I would say like Launched didn’t really take off and then the most recent one I’m working on and planning on launching end of March is I’m actually writing a book about learning AWS. I’ve used AWS my entire professional career and what I’ve noticed is a lot of folks that are coming out of college or coming out of code schools they wanna learn AWS. They know programming languages, they know programming practices but they’re not sure how to start with AWS. This book really focuses on learning AWS by focusing on a practical use case and learning the services by actually using them. I’m sure as you guys can attest some of the best ways to learn anything programming related is to actually just dive in and start using it.

**Ricardo:** Yeah.

**Will:** Yeah, for sure. I think we both found that and actually experienced that together when we were both working over at Linode and it’s definitely a good way to go about it. If not the best, I’m a little biased ‘cause that’s what I’ve always done for the most part so.

**Kyle:** Yeah, one of the best like career moves I ever made was joining a startup. I joined a startup when there was like five other people and essentially I had no choice but to be thrown in the deep end and learn things as I go and I think because of that. I’m probably a few years ahead of other people that would be my age in this profession.

**Ricardo:** Yeah, I completely agree. When I started Linode I think Linode was maybe about forty-five people and then starting CircleCI they were about at forty maybe even thirty-five and mind you no where near as little as the startup you started you joined but it’s a completely different experience than joining a big company that is already set in its ways and everybody has processes for everything that you just follow verse just jumping in there and having to learn as you go.

**Will:** Yeah and where are you at now Kyle? I can’t remember and I kinda want to let everybody know what you’re doing outside of this realm as well. 

**Kyle:** Yeah, so, I live in Portland. I’ve worked at a small company here in Portland called Zapproved for about 6 ½ years now. Like I said I started there when there was maybe six, seven other people and I’m actually I’m transitioning out of Zapproved now to join another company here in Portland called Slalom that is focusing on essentially helping mid-market companies in Portland re-architect their systems to be in the cloud. So, not really hybrid cloud more like transitioning to full blown cloud that’s what I’m focusing on right now and you know doing some side projects along the way.

**Will:** Cool. Yeah, there’s definitely a need for that working for an infrastructure as a service provider we definitely see a lot of people who need help with that transition. So, I think you guys got a lot to offer just off of you know what it is.

**Kyle:** Yeah, totally. I think you guys probably know better than I do at this point but I think there’s a lot of apprehension to the cloud early on a lot of companies are unsure and now I think companies are starting to see there’s a lot of power in it, a lot of value in it. It’s a race to get there and if you have technology changing right behind it too right Blockchain and all of that happening as well but it’s exciting times to be in the tech industry for sure. 

**Ricardo:** Yeah, I think we’re seeing a lot of these of certain just the concept of being in the cloud as well as cloud related technologies like Docker, and Kubernetes where many people were worried at first but I think we’re definitely seeing a momentum shift like Microsoft jumping on board and now you have the Cloud Native Computing Foundation that a lot of these projects are being they’re kind of sucking up to kind of solidify their place basically in the market and kind of say that they’re not going anywhere at this point.

**Kyle:** Yeah, I mean just like from a side project side hustle perspective the cloud has been one of the best things there could be for folks like us. You can literally launch entire companies or ideas in a day doing things like AWS or Azure or Google Cloud.

**Ricardo:** Yeah, who ever knew there would be $5 servers that you have full access too or with something like AWS pay for just mere seconds of computational time it changes the game. 

**Kyle:** Yeah, I mean Fantasy Supercross when I originally built it was essentially an angular app with an IAS web API but I mean behind it an Elastic Beanstalk and then Lambda came out now I’ve totally transitioned the entire API to run out of  Lambda so my AWS bill for the entire project is like $20, $30 bucks a month and that’s just for a database that’s running behind the scenes pretty much now.

**Ricardo:** Nice.

**Will:** That’s really interesting implementation. One of the things I wanted to ask you about Ultimate Fantasy Supercross is you know how you make it work? Like what that stack looks like and why you went about using that?

**Kyle:** Right. I chose the Microsoft Stack primarily because that’s what I use at Zapproved it’s what I was most comfortable with and I used to be the type of person that when I worked on side projects, I didn’t launch them you know what I mean? So, like they just sat on my laptop and it was great for like learning languages or learning paradigms but it didn't really stick until the Fantasy Supercross I was sitting around I was thinking you know I’m gonna launch it because then I will actually learn right? It’ll stick and so I went I didn’t want to go like too far on the risk-o-meter and I went with a paradigm and a language and a stack I was comfortable with. With the Microsoft Stack and so, I did that with C# it’s really just an angular app some Lambdas behind it now running .NET core and then there’s kind of I wouldn’t really call it a pipeline or anything like that I just call it an instance that comes up pretty much every Saturday every Saturday API parts as the results shoves them in the database and then also shoves them to S3 cause I have some machine learning stuff that I do on the results to kind of you know see trends and what scoring projections look like so that’s kind of the stack in a nutshell I would say. 

**Will:** Cool. Well, was there anything you know once you got all that put together or tried to get the minimum amount of that put together to test the idea. Was there anything that stood out right away as a big challenge that you had to work through?

**Kyle:** Oh yeah. The instance that comes up every Saturday seems an external API that I don’t control. That raised a bunch of interesting problems in that they could change the API any point in time and I could draw up results. My solution to that was to essentially make the worker be queue backed so I have one thing that thinks the API and just takes the raw results and then puts them in a queue so that the worker can then read off the queue and then shove them in the database and if something fails I don’t ever lose the message. [Will: Nice.] So, I can just essentially change the code adapt it to whatever the new API is replay the message and things are steered just fine that raised interesting challenges in that the worker needed to be essentially item potent. So, replaying the same message twice didn’t screw things up. Luckily, I have background in distributed systems so that wasn’t too much of a challenge but anytime you’re I would say hitting an external API that you don’t control that isn’t like a developer service or something like that isn’t really well defined it raises interesting problems in that you essentially want to have recoverability in those scenarios.

**Will:** Yeah, that’s definitely an interesting approach I’m curious how you know that that has happened? You know that failure has been triggered.

**Kyle:** So, I essentially just have a cloud watch alarm that lets me know if a message ends up in a toq. I know if a message ends up in a toq it’s usually the case that something with the API can’t be parsed now and so you look at what the message is figure out what can’t be parsed 

**Ricardo:** How often would you say this happens? Like how often do you think this API is changing on you?

**Kyle:** It usually so, there are two series that run every year. There's a series that runs from I would say January to May and then there's a series that runs June to roughly end of August and so where you really see the changes is where there's the first event for each series. So that's like where you really have to watch for changes in the API because it's live timing right? So, there essentially streaming data off of transponders. And so if they change transponders or they change the way the data is streamed or parsed they can change what the API sends back. 

**Ricardo:** Yeah, okay. 

**Will:** It sounds like you have a lot of parts all throughout AWS and your own systems I assume making this work. Do you have any sort of like workflows that you use to develop and maintain the entire you know system that you’ve developed?

**Kyle:** Infrastructure has code. That's the biggest thing I use because there are so many moving parts configuring that stuff by hand is just a recipe for disaster. So I use Terraform some cloud formation templates for some other things in terms of other workflows you know like any developer I think that's where drawn commercial software I hold myself to even test driven development but there’s a balance there with side projects I think you know I think when you’re working on a project yourself you run the risk of like over engineering your own ideas, you know what I mean?

**Will:** For sure.

**Ricardo:** Definitely.

**Kyle:** I just like any other engineer fall suspect to that and so, one like it’s funny to say but one strategy I use to prevent myself from doing that is actually I have like my wife testing things and test environments and we kinda have like our own, I would say like every like a weekly sprint we check in every Saturday type of thing to see is that feature making it in, is it not making it in. We have like a Trello board, we use like GitHub issues to track like bugs and stuff like that. So, it’s kinda weird to say but like I kinda hold even for my own personal projects follow some kind of natural process.

**Will:** Yeah, I know a lot of people that approach it that way. I kinda have this weird depends on the project approach and I don’t know if Ricardo’s approach is much different but I think it’s really if it works for you do it because otherwise you’re never going to hold yourself accountable. Like, you said you had a bunch of stuff earlier that you never really shipped and you never want to get back into that mode.

**Kyle:** Yeah, I think you guys heard about I heard you guys talk about him two times Pieter Levels or something like that?

Ricardo/Will: Yeah.

**Kyle:** His twelve ideas in twelve months after reading that I was like yeah okay you really do have to launch things and hold yourself to them. Otherwise, they’re not really a real thing. 

**Will:** Yeah and the worst case scenario is that it’s just you using it and hopefully you’ve solved a problem that you had or a need that you need to some extent even if it’s just for a group of friends and there’s no problem with that you still made something and you still learned from it got that experience it’s definitely super helpful in a lot of different areas of life. 

**Ricardo:** So, Kyle a question that I had for you is I know you mentioned earlier that you’ve had some failed projects along the way. What do you consider a failed project? Because speaking of launching in my recent experience, I always say that any project that you actually launch and is out there and it did that initial thing that you wanted it to do personally I no longer think of it as a failure. I used to but launching is so important and sometimes so hard to do that I feel like just getting it out there and launching it makes it a success whether you only have one user, ten users, a thousand users. How far did those projects go that you consider to be failures? 

**Kyle:** Most of them never even made it to launching. It’s kinda like some peaks my interest at like midnight or something and I then stay up til like 5 o’clock in the morning developing it and then I walk away for like two days and I come back and it’s like that’s actually not that great of an idea. It’s actually a pretty bad idea and I’m not really gonna keep working on it. It’s a failure to me ‘cause it’s like I didn’t launch it but you can also view it as ‘hey you didn’t launch something that’s totally useless.’ That’s a balance I’ve been struggling with I’d be curious if you guys have a similar problem but as developers we’re always hungry to try out new technology and implement things but there’s an important pre-step in that are you really solving a problem, that for me has been a bit of a struggle ‘cause I tend to write as a developer I want to dive in start writing code and you know get things done but like taking a step back and thinking about ‘well what problem am I trying to solve?’ Has been probably like that biggest shift for me in like thinking not thinking as a developer but thinking as more as an entrepreneur that’s been a bit of a shift. 

**Ricardo:** Yeah. I find that funny ‘cause that’s the exact same thing that happens to me and something that I mentioned in one of our earlier episodes I forget which one, while I’m not yet immune to that problem I still do it sometimes what’s helped me the most in terms of having an idea to start making it and putting in 10, 15 hours  and then realizing the idea is kind of useless was to write it down. So, writing down my ideas whether it’s on Trello, a notebook anything like that typically I write these down and already I feel a little less anxiety in having to do it because it’s down, it’s saved. And I tend to go back maybe you know on Fridays or weekends I go back through these ideas and if days later or a week later it still sounds good then maybe it’s something that I’ll do or maybe I’ve written down ten ideas and I realize three of them overlap to one better idea so then now I have that and then I go ahead and proceed and try to build whatever that is. 

**Kyle:** Yeah that’s a strategy I’ve actually been using too. I have a Trello board that has like a backlog of ideas and anytime I have an idea I put it in Trello and then I like give it 3,4,5 days to bake and I come back and I go ‘well on a scale 1-5 what’s my interest level in that?’ And then a scale of 1-5 ‘how much is that actually solving a problem or how big of a problem is that?’ 

**Ricardo:** Yeah, I would love to be able to talk about your book before we go. But just one other thing I wanted to bring up. So, I know you mentioned the idea of solving a problem and I think that’s interesting because what this whole podcast is about is side projects and there’s two sides to that because you can have side projects that are just for fun you know educational purposes but some people like with the entrepreneur spirit in them have side projects as an attempt to build a startup maybe at some point. Whenever you hear about building startups they always say you need to solve someone's problem. I haven’t started a company yet so you know I don’t have that experience of actually starting a successful company but all of my side projects that have gone anywhere like with the podcast where people actually listening or a side project that someone’s actually using. I’ve noticed I’ve put in the most work when it solves my problem. I took a break for a little while and said for me to stop trying to solve other people’s problems and solve my problem and then it turns out that someone has that same problem. Like, with this podcast for example, I just wanted a way to talk about my ideas, find other people who have ideas and kind of just collaborate. That was my problem and I contacted Will cause I knew Will he had the exact same problem. So, being able to find a solution for my own problems seem to help me in terms of being more invested into these side projects and pushing them over the line to the point where they launch.

**Will:** I think I might be a little bit different though because I don’t subscribe to the extremism of the problem being the best option for like the startup realm like a lot of these people are preaching in their vlogs and podcasts like ‘you gotta solve a problem, you gotta solve a problem, solve an f’ing problem’ but I always end up flashing back to the Ford quote about faster horses whenever I hear that and I definitely think it’s a good approach to solve problems don’t get me wrong but I also know that there are things that can be created that people don’t even know that they would want or need. So, I try to keep that in mind too with some of this stuff. I try not to restrict myself to some predefined box absolutely which I’m not saying you guys do but I know people tend to fall into that pattern. I try to consider the ideas when I approach them make a really small prototype with the ones that I’m really passionate about and then actually ask people to use it whether personally it’s or just you know a select group of people.  

**Ricardo:** I don’t mean to put you on the spot Will but do you know that Ford quote? Would you be able to share that? I’m curious just for myself.

**Will:** I think it was him and if it’s a true quote it is ‘if I’d asked people what they wanted they would’ve said faster horses.’ 

**Ricardo:** Okay. Yeah that’s a good one.

**Will:** But that could be a false quote for all I know. All I know is I read it on the internet and it flashes in my head whenever people get into that zone of only problem-solving.

**Ricardo:** It sounds real if that helps. 

**Will:** It’s real now ‘cause I said it and it was on the internet.

**Ricardo:** Exactly.

**Kyle:** Yeah, no, I think there’s totally a balance between problem-solving and what I would call innovation, you know? Would Facebook exist today? Probably not it’s not like there was a problem there to be solved. Not that I can clearly see and so that’s why I think it’s important when you’re working on side projects it has to interest you, right? There’s a lot of problems out there that need to be solved but there’s also a lot of things out there that don’t interest me. I kind of have that entrepreneur spirit I want to start my own company I want to do my own thing at some point in my life so, I tend to focus on problems but I still agree that the most important thing to a side project or any business venture if you’re going to start something and you’re going to take that big risk is it has to be something that truly interests you. And you’re happy to work on it day in and day out. 

**Ricardo:** And I think especially starting at the side project level which basically means this is not a VC funded startup at least not at this point you know you don’t have that money you’re probably working like we all are full-time job so, if you don’t have that interest, that passion, that excitement, why the hell would you work a full day of work and then go home and then keep working basically on something else. You need to have that level of excitement with it in order to be able to accomplish that.

**Will:** For sure, and I think you touched on it earlier Kyle when you kind of gave us a rundown why you started these two things. One, being the supercross project and your book and with the book I think it was specific to this because you seem like you had identified a problem that others had but you also understood that problem that they were going through and wanted to solve that pain that you probably felt yourself getting into learning AWS and how to effectively use it. I think it speaks volumes that we’re talking about this now when you’ve kind of already hinted towards it.

**Kyle:** Yeah. I think you hit the nail on the head. As everybody kinda knows that AWS documentation is kinda less than stellar and so when I was first learning AWS it was a slog to try and get to the bottom of ‘what do I use this services for and what do I not use this service for?’ What I found out is slogging through documentation sucks the best way to figure out what to use the service for is to dive in and start using it. That’s really what inspired me to start writing this book you know focusing on a real simple practical use case right? The use case in the book focuses on deploying, securing and delivering a static website on AWS. Well, there’s a million ways you can do that nowadays, right? You can do that with GitHub pages you can do that with Firebase there’s whole kinds of things you can do that with. [Ricardo: Yeah.] But, focusing on that simple of a use case actually if you do that on AWS you can learn 5,6,7 different AWS services just by focusing on that one simple thing. 

**Will:** So, would you say that that’s something that your book takes an approach on that other guides or tutorials doesn’t have?

**Kyle:** Totally. A lot of the stuff I have seen about learning AWS focuses on a very specific service, right? So, the most popular one right now as I’m sure everybody can attest is Lambda right, so, there’s blog posts left and right about Lambda. These limitations and those limitations but it’s really kind of just regurgitating the documentation, right? Everybody at this point knows Lambda has a five-minute limit on execution, right? But if I’m building a product or I’m building a business or I’m building a service in AWS. When would I choose Lambda over EC2, right? There’s a bunch of gaps missing that the documentation isn’t going to answer for you.

**Ricardo:** That’s a perfect way to describe that because I know whenever I go into AWS’s dashboard and once again like Will said we’re a little bias I come from Linode and Linode has [Will: Yeah, and I don’t go in their dashboard at all.] Well, at CircleCI we use AWS. When you log into that dashboard especially compared to something like Linode there’s so many services so many services to the point where they have to group them. Just to be able to page them and kinda see what’s related and like you said just going in there there’s more than one tool that can do the job. So which do you go with or better yet maybe the two different tools can do the job but you also need another piece and that first tool won’t connect with that second piece. Just knowing which tool is best for the job and then also which one’s actually integrate best together for what you’re trying to do is complicated and for the docs which is not really the docs fault at the end of the day the docs just explaining one individual thing but they don’t get to that level they don’t get to the experience level they don’t get to the integration level that you get at when you’re actually using more than one service together in a project. 

**Will:** Man, it almost sounds like you’re describing it being a bad user experience and poorly designed. One of the things I wanted to ask you about when writing this book because I haven’t written one myself. I’ve only written blog posts at most I would say is there something that you can identify that really slowed you down in the process of writing this book?

**Kyle:** Yeah I think it’s when you write a blog post it’s kind of a one and done type of thing, right? I mean, there might be some back and forth. You might have like a follow up blog post. When you’re writing a book you’re trying to create this one continuous streaming thought, right? And really tying back to if somebody is going to buy this book, why are they buying this book? Right? Because anytime you’re writing or talking to somebody about a very technical subject you want to dive into the beats like I know the in’s and out’s at Lambda I have enough scar tissue. I have been on enough AWS support calls at 2 o’clock in the morning that I know a lot of interesting things about Lambda but somebody that’s buying this book probably doesn’t care about that level of detail right now, right? They want to know ‘how can I use Lambda to solve my problem that I’m facing?’ So, I think the struggle I faced in writing this book is really trying to be general and abstract but still teaching what the point of a given service is. And how you can use it in your day to day.

**Will:** Yeah, it seems like you’d have to hit a really specific balance but once you found it it might be a little bit easier to continue forward. 

**Kyle:** Yea, totally. And the second challenge for me was I decided about a month and a half two months ago to not only just write a book but to do screencasts as well and kinda turning your book material into screencast is harder than I thought it would be and then recording screencast and like hearing yourself talk and recording that isn’t the most enjoyable experience as I’m sure like you guys can attest the first time you have to hear yourself talk it’s a bit weird.

**Ricardo:** We’re now recording our 6th episode and I have listened to almost none of them. I hate the sound of my own voice. 

**Will:** I’m a little more comfortable. I’ve done things like this not in the tech realm but like recorded things for a long time so, I have an advantage on Ricardo in that.

**Ricardo:** Yeah, he also raps. 

**Kyle:** Yeah, yeah, I’ve heard about this. I’ve listened to the first three. I haven’t looked up the rap songs yet. I think I’m gonna have to do that after this. 

**Will:** Let me know what you think?

**Ricardo:** In episode two or three one of the albums is in the show notes. But I do have another question Kyle. So, kinda coming from the side project aspect you’re not writing this book as a writer for some big publishing company right? So, you’re doing this on your own so, once you complete this writing what is your process in terms of getting it edited or figuring out how to publish and distribute it? Like what tools are you gonna use? Or maybe agencies, companies?

**Kyle:** I am going to self-publish. One of the best pieces of advice I got was from, are you guys familiar with Dev2? 

Ricardo/Will: No.

**Kyle:** So, Dev2 is kinda like a Medium but just for like developer blog posts and I read a blog post on there one day that a guy that was writing technical blog posts he wasn’t getting a lot of visits he wasn’t getting a lot of feedback and then he hired an editor something like I don’t know $100, $200 bucks to edit his blog posts and figure out where his writing essentially sucked and after he did that he wrote another five blog posts and got something like 25x conversion rate compared to his previous blog posts. [Ricardo/Will: Wow.] And so, before starting to write this book I went through that same exercise. With an editor here in Portland and she gave me incredible feedback like things that I think they probably try to teach you in college and high school and at the time you don’t really care to listen and so going through that exercise helped me write better now and then my plan once the book is finished to send the whole book off to her for editing and then probably a designer to kinda design a cover and then really the launch process is going to be updating the website. I’m probably going to use the service like Gumroad to see the digital asset although, I wish there was something cheaper than Gumroad they kinda have some insane fees but that’ll be the launching process is essentially going through editing some clean up and design, probably have a few reviewers that I know read it and see if there’s anything I need to fix. And then launch it on Gumroad and sell it on my website.

**Will:** Cool. Sounds like a pretty straightforward way to approach it and I think having that review is probably something that’s very useful especially for people who don’t have any background in writing things like that. 

**Kyle:** Yeah, I know it’s one of the best pieces of advice I’ve gotten like going through this exercise is pay the hundred bucks to have somebody that reviews blog posts and reviews technical writing all the time to just give your stuff a read and see there’s all kinds of little things you can do to improve your writing that makes it much more concise and to the point.

**Will:** Cool. When do you expect to be able to release it? You got a date yet or no?

**Kyle:** I’m shooting for the end of March to release the full book plus screencast and then go from there onto the next project probably do some marketing for a month. Focusing on that and then kind of start on the next thing.

**Will:** Well, we definitely wanna have you back when everything’s out so we can see if maybe there was some stumbling blocks in the release and get some feedback on how everything went and hopefully be able to discuss that whole process because it sounds like there’s a lot to that as well.

**Kyle:** Yeah totally. It’ll be a lot of fun to come back and talk about what went well. What I learned and try to help some other folks out.

**Ricardo:** Yeah that would be absolutely awesome. Thank you so much Kyle for being our first guest on the show. We really appreciate it. If you’re up for it if any listeners have any kinda questions or anything like that what’s the best way to contact you whether it’s Twitter, email anything like that?

**Kyle:** You can find me on Twitter. I’ll shoot you guys over my email and you guys can put it on the post notes. You can find me on Twitter it’s just Kyle Galbraith G-A-L-B-R-A-I-T-H yeah, if anybody ever has any questions about AWS or C# or anything kinda you know cloud related feel free to ask me I’m super active on Twitter helping people out answering questions and helping people solve their problems. 

**Ricardo:** Awesome. Thank you so much. So, Kyle’s information as well as links to all of his projects will be in our show notes. I think that I already forgot the name of it that website that you said is like Medium if we can get a link for that sometime after the show we’ll put that in the show notes as well. If anybody has any questions for us, feedback or they would like to be a
guest on our show please contact us. You can find us at Twitter.com/DeveloperHustle. Facebook.com/DeveloperHustle and our website DeveloperHustle.io anybody else have anything left to say?

**Will:** Buy Kyle’s book. 

**Kyle:** Yeah, buy Kyle’s book.

**Ricardo:** And hopefully Kyle when it does come out please shoot us a link and let us know as well and we’ll try to share that for you. 

**Kyle:** Awesome guys will do.

**Ricardo:** Awesome. Thanks everybody.

**Will:** Thanks.

**Ricardo:** And thank you so much Kyle for making it. We really appreciate it. We know you had traffic but appreciate it. 
