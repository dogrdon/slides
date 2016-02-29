###New Ways to Access Our Video Collections
  - or "What I learned about a sample of video collections from the DPLA, how it changed me, and maybe some interesting implications and stuff, maybe, I don't know."
  - my name
  - I work at a repository that deals with video data for researchers
 
###Provocation
  - I want to talk about video access through various collections
  - This started because I wanted to make a twitter bot pulling from the DPLA making gifs out of video files
  - This is not about the twitter bot, but rather the challenges realizing what I thought would be fairly trivial.
  - But I was wrong, fortunately it has some interesting implications

###Video
  - It is a complicated resource:
    - It is large
    - It is difficult to provide access to
    - It is difficult to search 
    - It has a complicated set of restrictions

###But why are we talking about this
  - Well, again, no one would really think to go plugging around for videos all over the place unless there was an amazing service that brought all of this stuff together in some standard fashion.

###Video in DPLA [SOME OBSERVATIONS]
  - It is not as widely accessible, the objects themselves, as say images are
  - Have a look at the JSON
  - Only Nara provides the actual location of their video files, and those are not directly accessible

###Video in DPLA [SOME STATS]
  - Had to pull down the bulk files
  - [Difficulties parsing those]
  - Found this: 
    - from my count, roughly a total of 27000 video items in dpla (this could have missed something)
    - of the __ providers, 17 have videos in their collections
    - some more than others: National Archives and Georgia by far provide the most
    - In fact, Georgia, Nara, along with USC, DigitalNC and Washington (get their actual names) made up about 72% of all the video items in DPLA. Making it fairly easy to rely only on those.

###Hacking and Scraping
  - So this is where the real "fun" began in order do some manipulation of tthe video files to generate a gif, had to download them (i'm sorry)
  - Scraping, every site does it differently. Set up some profiles for the most desirable (while also minding restrictions)
  - ContentDM - surprisingly, not standard in it's streaming of videos
  - It's not pretty, but it's done for a reason

###Implications
  - So this is where I wrap up
  - It occurred to me that there is a new potential for engaging video collections
  - Machines accessing video files could be the future of research & digital librarianship
    - DH
    - Creating better search for videos
    - With some really sophisticated machine learning and neural networks, 
    might begin to generate metadata from allowing machines to watch videos
    - And so on, lots of stuff that's probably not here yet.
  - But we have a problem, and it's that these videos are very difficult for machines to access without some pretty gnarly intervention
  - An interoperability for AV materials (audio are certainly not out of the picture here, I just didn't have a lot of time to investigate that part)

###End
