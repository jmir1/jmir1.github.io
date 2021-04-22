+++
title = "i think i made a mistake"
date = "2021-04-16T05:45:00+02:00"
author = "jmir"
authorTwitter = "miramon_joel" #do not include @
cover = ""
tags = ["android", "development"]
keywords = ["app", "tachiyomi"]
description = "making an app is way too hard"
showFullContent = false
+++
so a few days ago i had the brilliant idea of making a fork of [tachiyomi](https://github.com/tachiyomiorg/tachiyomi) (a superb app for reading manga and comics etc.) 
and add anime/video watching capability to it.  
so i started by copying and rewriting a buch of classes for the new anime functionality (this is also my first time using kotlin so that's cool)  
after many many hours i finally got it to compile and not crash instantly when opening the app! wow! sadly, pretty much nothing is implemented yet, 
i only added a new tab at the bottom that doesn't do anything yet.  
the best thing about tachiyomi are the source extensions though. you can download extensions for the app that are basically webscrapers of manga websites. 
those let you download and read what you want, from literally hundreds of websites to choose from!  
so the next step was (i think) to make a new extension for an anime site (i am using my own ([2dgirls.tech](2dgirls.tech)) because it just works and is the simplest website ever.  
i had to rewrite some stuff in the github action scripts (and i learned how to sign an apk!) and now i have my own repo of tachiyomi extensions!  
sadly, the app has a lot of bugs and my extension isn't displayed in the extension download section ;(  
so that's basically where i'm at right now. what's left is to fix the current bugs and implement a video player, then rewrite the tracking functions (anilist etc.)  
this leaves me thinking if i'm in a bit over my head...  
nevertheless, if i finish this or not, it will have been a good learning experience, as i've never developed an android app before!  
that's all, good night!
