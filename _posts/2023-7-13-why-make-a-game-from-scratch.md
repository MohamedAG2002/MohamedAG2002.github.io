---
layout: post
<<<<<<< HEAD
title: Why make a from scratch?
=======
title: Why make a game from scratch?
>>>>>>> 0f928a9 (Update why-make-a-game-from-scratch)
subtitle: The ultimate question
comments: true
tags: [gamedev, discussion]
---

# What?
Programming a game from scratch is not the easiest thing to do in the world. It is, in fact, very difficult. Some might even say it is a pointless and time-wasting endeavor. Why waste time programming systems which already exist and are way better than whatever it is you're going to write? Why waste *time* programming such things when you can spend that time learning other tools which will get the job done in an easier and faster way? Of course, everyone is entitled to their own opinion and I, nor anyone else, has the right to take that away from you. However, what I am trying to do here today is not to invalidate your opinions but, rather, I will try to make you understand why someone--me or anyone else--might program games from scratch in 2023--or whatever year you're in--while having many other superior tools at our disposal. And who knows? Perhaps you will like the idea and would like to give it a try sometime.

# Do you want to make a game or an engine?
If you've ever seen a video or read a post where the subject of "making a game without an engine" popped up, you probably heard of this question before: "Do you want to make a game or an engine." In my opinion, this question at its core is terrible. It suggests that, whoever it is pointed at, will never be able to make a game without a game engine, which is completely not true. I can point you toward many games which were made without the need for robust GUI tools, fancy post-processing, or--in some engines--an in-engine editor. However, that's not the point. The point here, in fact, is the question itself is very misinformed. This question cannot be answered with A or B. The answer would rather be, as with all things, very complicated. 

Making a game or an engine entirely depends on the game dev at the other end of this question. It entirely depends on what kind of game this game dev wants to make. Pushing that dev into a corner and telling them to never attempt to make a game without an engine since they will just be making an engine at that point, is very terrible. And, as discussed before, it is very, very misinformed. I believe, whoever is asking this question, had gotten used to engines like Unity, Unreal, or Godot which provide a vast toolset to make whatever kind of game you want. The sky's the limit with these engines. Yet, that is not what we--those who do not use an engine--are trying to do. We are not trying to make another Unity or Godot and, certainly, we are *not* trying to make--or even compete--with Unreal. Instead, what we are trying to make is... games. So, to understand why and how this question is misinformed, let me explain to you what an engine *really* is.  

# What is a game engine?
If you are reading this post, you probably know what a game engine is, and, don't worry, I will not try to explain to you what an engine is, as you probably heard that explanation many times. Rather, what I will try to do is to explain to you what a *small* game-specific engine looks like. 

When you think of an engine, the first thing that comes to mind--or at least the thing that comes to *my* mind--is a slick editor with many, *many* features which permit you to make any kind of game you want; no matter the genre. You'll probably think of a slew of post-processing settings that will make your game look fancy and realistic. Perhaps many supporting ideas like animation trees, robust particle systems, and a complex collision system. Now, let me tell you what a small 2D engine that is only designed to make top-down strategy games consists of. Ready? 

None of these things.

Perhaps, it will have some post-processing settings to make *some* things look nice. Maybe a 2D camera designed to make the player zoom across the map with their mouse/joystick or some shortcuts on their keyboard/controller... but that's it. Everything else that will be added to this "engine" will only serve to make 2D top-down strategy games. Nothing else. 

Back then, programmers made engines specifically for the games they were making. Developers at the time didn't care about adding features that will never be used for their games. Whoever was making 2D platformers only added features to support that. Whoever was making racing games didn't care about adding gravity, combat, or health systems. And so on. In fact, the id tech engine was made specifically to create first-person shooters much like Wolfenstein 3D, DOOM, and Quake. The folks at id software(all hail John Carmack)didn't care to implement features that did not help them make these kinds of games. Unreal Engine even started as a first-person-centric game engine, which would make it easier for developers to make 3D FPS games. 

So you see, making a "game engine" doesn't necessarily require you to add complex features like the ones found in Unity or Unreal. When you make games without an engine, you are only required to implement features that will support the games you are trying to make. You don't even have to make things like animations complex as you only care about the animations in *your* game. When you add features to your "engine" you only care about it working for your game and no one else's.

Engines like Unity, Godot, Game Maker, Construct, Unreal, CryEngine, and so on are made for "general-purpose" use. They are made to make games of *all* kinds, not just FPS games, strategy games, or racing games. They are made to make all of these types of games. When you're trying to make a game without using them, you are not trying to add all of the features, since, simply, you will NOT be needing them. 

Now, all of that is great and all, but it still does not answer the question. Why should I be making games without an engine? Sure they have complex features that I will probably never use, but there are a *ton* of great games made with them and these games also did not use the plethora of features these engines have. So why don't I use one of these engines when there are many examples of amazing and fun games made with them? 

# Why not use an engine, then?
The answer to this question is very simple: I enjoy it way more. With game development specifically, it is very easy to get lost in many roles. You have to wear so many hats in order to make a game. You have to be an artist, a designer, a musician, a programmer, and a marketer. If you're making games on your own, which is probably most people nowadays, you have to dip your toes in many of these professions. As a result of that, it is hard to focus on one thing and one thing only, at least it is for me. Sometimes you have to make some new art for a monster, another time you have to design a new level, and another time you have to implement many other gameplay features. This, for me at least, is very hard to do. Instead, I decided to focus on the things I enjoy the most about game development: mainly, programming and design.

I am not a very artistic person. In fact, I think I am devoid of any artistic ability. Also, I am very broke, so buying assets is not a choice. So when making a game on my own, I often would code a lot, think about the gameplay a lot, and not make any progress on visuals whatsoever. I tried to make art before, believe me, but all that turned out was a 1-year-old's rendition of what a spaceship looks like. 

I also discovered that I absolutely *love* graphics programming. I love the way I interact with memory, bytes, and low-level systems. I love learning about geometry, rasterization, shaders, and compression. I love everything about it. While engines do have some fun parts as well, they just don't give me the satisfaction of creating my systems from scratch and seeing them all work in-game together like a soothing symphony. I fell in love with lower-level game development the very first time I displayed a window without the help of Unity--the engine I used at the time. 

It was hard for me to accept the fact that I was a game *programmer* first and foremost. I, as well as many others, think of game developers--or at least the indie game devs--as the jack of all trades. A game dev knows how to do many things not just *one* thing. But I came to realize that the notion of an all-in-one game dev doesn't really apply to me--if it exists at all. Sure, there might be others who are like that, but it's certainly not me. I enjoy programming, *game* programming and I am ready to do it even on my deathbed.

So, why don't I use an engine? Simply put, I don't want to. I enjoy making games without a game engine. But, as it turns out, not everyone is like me(SHOCKER!). People have different preferences and different goals. My game dev "goal" is not to make an AAA game. I don't want to make the next Elden Ring or Call of Duty. I want to make simpler games that connect with you. Games that you can have an emotional connection with. Simple games that don't require complexity to be fun. I might not be at the point of making these games yet, but that is my goal and that is what I will be working towards. 

But what if you *want* to make AAA games? Well, you have to learn *when* to use a game engine.

# When to use an engine?
It might seem, from everything above, that I am an advocate for completely abandoning game engines and never using them ever... and you'd be right... mostly. I do think that every programmer should, at some point in their life, attempt to make a game without the help of an engine. However, not everyone. Again, as with many things, it is complicated. They are some cases where I would advise *against* making a game without an engine. It might seem to go against everything I stand for to suggest using an engine in a post where the main idea is to *not* use an engine... but hear me out.

Let's say you grew up playing FPS multiplayer games. Games like Call of Duty, Counter-Strike, and Battlefield. Perhaps you grew up playing MMORPGs like Dota, WOW, and Runescape. Maybe you also loved playing big action AAA games like Uncharted, Bioshock, and GTA. You always played and loved these games. You always dreamed of *making* these kinds of games... if that's you... **please** use an engine. 

As I said before, engines like Unity or Unreal are made for general-purpose use. They have every tool ready at your disposal to make any type of game you want. And, especially in the case of Unreal, they are used to make big and expensive games. Your scope needs to be limited and reachable. Making AAA or even AA games without an engine needs a big team of talented and experienced developers who have been making games for years. That said, even when you're using an engine, do not over-scope your game. If you're on your own, make a game that only *one* person can make, not a team.

However, that is not the only outlier. As I said before, game developers wear many hats but from the many hats they wear, they mostly identify with one hat. Maybe you come from an artistry background. Maybe you don't like programming or you're not interested in it all that much. In those cases, I implore you to use a game engine. You will benefit yourself more if you use a game engine as it will really help you make the game you want to make faster without the nooks and crannies you have to go through when you're not using an engine.

Finally, the last piece of the puzzle is the beginner. If you're a *complete* beginner and you do not know *anything* about programming or game development, please use an engine. It's still too early for you to make your mind up about those things. I used Unity for a year before switching to a lower-level programming "lifestyle". You need to learn what a game engine *is* before trying to make a game without one.

# How not to use an engine?
You took the plunge. You decided that you are going to make a game without an engine. You're also interested in graphics programming and lower-level systems... but where do you start?

A lot of tutorials suggest that you start with C++ as that's what most people use. They would be right. However, you don't have to go with C++ to begin with. As I am sure you've heard, C++ is a very hard language with multiple levels of complexity. So, to make it easier on yourself, you can perhaps use C#, Lua, or even Java(please don't use Java)to start with. But always remember, all roads lead to C++ in game development. You don't have to use it now but, eventually, you'll have to get your bum touched by C++ at some point. 

Once you picked the language you want to use, you now have to pick a game framework. What's a game framework? As a gross oversimplification, frameworks are just a bunch of functions and data types(Vector2, Color, Rect, etc..)that will help you on your game-making journey. I suggest you research them a bit more. Nonetheless, there are a bunch of game frameworks for *every* programming language out there. Whatever programming language you're thinking about at night while in bed probably has a game framework made for it. For example, C# has MonoGame, Java has LibGDX, C/C++ has Raylib, SDL, and SFML; Lua has Love2D, Python has PyGame, and Javascript has Phaser... as I said, every language has a game framework. Of course, they are different levels of complexity with each game framework and how much they offer. There are also game frameworks that are harder than others. But at the end of the day, they will help you make games without using an engine.

That's not all. You also have lower-level graphics APIs like Vulkan, OpenGL, and Direct3D. These are the lowest you can get. You *can't* go lower than these APIs(except if you want to program games like it's 1993). I say refrain from these for now but definitely give them a look once you've grown a bit more as a lower-level game programmer. 

And lastly, I just want to say to take things slowly and understand that it will take time until you actually start making a "viable" game. You will make a lot of Space Invader clones before making the next DOOM. You will fight with yourself a lot. You will want to give up... but know that everyone went through everything you're going through right now and many came out the other end stronger and more knowledgeable than before. Know that you will struggle.. but, remember, there is no success without failure and pain.

I swear I am not a Sigma male advocate. I was just trying to motivate you. Hopefully, you got motivated nonetheless.