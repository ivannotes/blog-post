# What Help Me To Become An Efficient Programmer

I have always want to think thorough about what make an efficient programmer,
during my work I always try to fix things that seems not works so well with me
and myself is not a guy that can play tools by following manuals I want to make
tools for my use. So this article is about what I think could be efficient for
me and I intend to continue doing so.

Before I start I'd like to talk about what makes an efficient programmer in my
understanding. An efficient programmer for me is who can finish his/her work in
a reasonable time and with high quality. Capable of doing things which is repeated
very frequently very well. And he/she happens to believe that there is always a better
way to do one single thing.  

In order to let myself get close to what I mentioned above, I tried a couple of
things in the last couple of years which I'd like to share and get feedbacks.

### Communication Skills

The first tool is communication. The reason why I list it as the first thing is because
if something is mean to be created, first we have to know what it is, and by knowing it
we have to talk with a couple of people who owns the project at the very beginning. But
the reality is a different story there are something bad happening every day like below:

  > Tom:  "Hey, what's the progress of A ?"  
  > John: "Oh, I'm on it"  
  > Tom:  "Is everything okay, do you need my help ?"  
  > John: "No problem, I'm on it."  
  > Tom:  "Good, Let me know if you need anything."  
  > 
  > Couple of days later  
  > 
  > Tom:  "How's everything, are we able to release it tomorrow ?"  
  > John: "Er..., It's hard to say."  
  > Tom:  "What's wrong ?"  
  > John: "I found out I need XX and YY before I can start."  
  > Tom:  "..."  

If I'm Tom I must be pissed off by this. This conversation may look like funny but it's
not exaggeration. Communication is very important, make sure it happens before actually
start something and know as much more details as possible will make what you are going
to build more clear.

Typical communication scenarios for my daily life are requirements negotiation,
POC verification, dependencies management and job assignment. 

* Requirements negotiation

  > Requirements negotiation is mostly about get details about what need to be built, when doing
  > this kind of communication you must be concrete about almost everything. For example there
  > is a task add a remove button on staff management page, so what we need to know about this task ?
  > 
  > * Do we need promote a confirmation dialog before we actually remove it ?
  > * Is everybody have permission see this button ?
  > * Where should this button be put at, left or right ?
  > * Is a default style is enough or we need a customized icon for this button ?
  > * ...
  > 
  > As you can see there are a lot of details to ask about for this specific task. But if you don't
  > ask before hand, it might effect your design in code in an unexpected way. Because your code
  > is not prepared for all this at the very beginning, even worse you implement it in the opposite
  > way and you have to spend more time to make it right after your work is inspected by the project
  > owner again. More importantly there is no fun in it, and you won't feel proud of spend so much
  > time on the same code again and again.

* POC verification

  > Proof of concept verification is also something happens very frequently during software development.
  > I won't try something new before we know it could work, and it's very tricky. Imagine you are assigned a task
  > to see if it is possible to replace some Ruby service with Go, and what you do next ? Maybe you spent days
  > to do all kinds of experiment to verify the idea, and in the end you told other guys the answer is yes. But
  > nobody believe you, and you are left there wondering why they just not believe you.
  > 
  > For POC verification the most important thing is that people need to knows how and why this could work.
  > You did a lots of experiment but how you did it, what kind of strategy you use for this kind of approach and
  > what's the test data like ? In order to answer all those questions you have to record every step of your
  > work during POC experiment, it includes methodologies and output data. After that you have to reorganize them
  > because nobody understand raw data, process the data and show them in a way they could understand the
  > difference by using or not using the new technology.

* Dependencies Management

  > Dependencies management is about something you can not finish alone, you need help from others.
  > Others can only help you if they know what kind of help you need and what's the schedule like so
  > they can make arrangement for this kind of help. You should not assume you could get help whenever
  > you need them, it's never gonna be true, so make an arrangement before hand and be prepared for that
  > time window. And the most important thing is when the arrangement is changed please keep them posted.

* Job Assignment

  > Work for a company means there are a lot to do, but you are not able to do all of them by yourself so jobs
  > need to be assigned to your team members. Assign a job, track the progress and offer help whenever they need
  > it, sometimes you might need to offer help when you feel like they are struggling in it, everybody could use
  > a little help and it could also reduce the time you spend on tracking the progress. 

Documentation is another thing which I think is important for communication. Because I always believe
human-beings have a bad memory we can not remember anything, so it could be nice we put those important
things which are asked very frequently in some documents. And it could be even nicer if those documents
can be maintained online, so people can review, give opinions online to keep the document up to date.

### Developing Environment

Every programmer has his/her ideas about what's the best for work, and from my experience it could be
very different from different person. For myself the list below is a minimum must for me to work efficient.

* Have A Quiet Place
  > A quiet place could help me focus on my job with less interruptions. As a programmer quite often I need
  > to solve some "tough" problems, in order to solve them I need a continuous time window to focus on it, so
  > a quiet place will be a great help. But during the growth of the company the office is also getting more crowd
  > in this case a decent headphone to keep the noise out is also an acceptable choice.

* Official Website & Source Code
  > Every time I pick up new stuff I always visit its official website or read its source code to try to
  > understand it. Almost every time I found what I need from the official website, it's not likely you
  > could find it from other website which I think it's a third-hand knowledge. The source code is the
  > best source for learning since it always up to date. And the official website document are treated as
  > second-hand knowledge, because document could be missing and out of date even for official website
  > and a great programmer doesn't mean a great document writer.
  > Usually I will visit the official website get an idea about the new tech and understand the core
  > architecture of it and then I could read the source code for specific problem I meet. And it works very
  > well so far.

* Know My IDE
  > For the last 3 years I start using Vim for Python developing job (Before that I used some GUI IDEs), and I love it.
  > I'm not saying that Vim is better than other IDE like Pycharm, Atom and etc, I just mean it's the best for me.
  > No matter what IDE you are using please know them, I can not imagine somebody use Pycharm don't know
  > how to use short key for file search or refactoring code manually. I think it's very important for
  > a programmer to know why you pick your IDE, if you know it well you will gain tons of time for a cup of coffee.
  > I like to use Vim because I'm a terminal guy, I like to do everything in terminal,
  > it make the switch from different window smooth for me and I also like light-weight stuff,
  > it won't consume a loads of memory or CPU and it's also very handy for customization.

* Command Line
  > Just as I mentioned above that I love terminal more than anything else, this is mostly because I can use all
  > kinds of unix/linux tools together. With different kinds of combination you can achieve a lot of things like
  > text processing, file transmits, log analysis, performance analysis, network inspects and etc. Unlike GUI
  > different GUI tools can not work together but with command line you can always use different tools together to
  > achieve your goal. And knowing shell script is another big advantage of use command line tools, it could
  > keep your most used command line combination and save a tons of time.

* TestCase
  > A lot articles and TDD pioneers talked about the advantage of writing TestCase. But the biggest advantage
  > I learned from TestCase is that it could make me more efficient in a dramatic way. For many years engineers
  > think we are solving very hard problem so the code must be as complex as it should be, especially as the time
  > went by the code could be super complex. In the meanwhile most engineers are dealing with legacy code in a
  > daily basis, when I say legacy code it means hard to test, hard to change and hard to understand. Every time
  > when deal with legacy code first need to know how to run it, by knowing how to run it I need to read its code,
  > and since the code is hard to read it needs time to fully understand it, and that needs quite a lot time.
  > But unfortunately I have a bad memory like always, so every time I touch it I need to do this all over again
  > which is a big waste of time.
  > TestCase can help with it, every TestCase is like a memory been saved there you never forget and it did more
  > than that: it could also assure later change won't break exist functionalities and also provide a way to run
  > the code for free. With this in hand you will become more comfortable to make further change to legacy code to
  > make it easy to read and maintainable and not to mention how many times you need to run the code to test your
  > change before you can commit, it will save a lot of time.

* Automation
  > For developers, there is a lot of configuration and settings to setup locally or remotely. As for example we need
  > to download access log from servers to analyze the usage of client browsers, what we need to do is login to all
  > servers and download log files, process them and print the analyzed data. If we have to do this multiple times it
  > will need quite a lot of time, but instead of manually download them and processing them we could
  > write some scripts and output some beautiful and readable charts instead. As you can see this will save you a lot
  > of time and no matter how many times we run it, it will still be consistent as the first time you implemented it.
  > So if you have some job need to be done very frequently, it's worth to try out some tools to make it automatically happen
  > for you.

### Pay For Efficiency
I have to say most paid productivity tools worth the price and it usually has better user experience than free one,
so if you feel like it could help you just buy it. We are engineers we know how hard to create something which is
usefully, so pay for it to make better software.

### Get Feedbacks From Others
Talk about how you do your work with your co-workers/friends, express the things which pissed you off to them, most
likely they would know something which can ease your pain. You don't know what other's doing and they will surprise
you in a good way.

### Make Your Own Tools
I always say that every body is somehow different, no one could understand your requirements better than yourself, so
when you feel like there aren't any existing tools which can help you, just give a try to create one for yourself,
gains from it could be very fruitful, as for example you could write your own Vim plugin to simplify your work and you
could write your own log aggregator to analyze performance. Those things are doable and with great benefits, just try it. 

All above things I mentioned are about my daily work, the point is to keep my eyes opening to see those things which
not works so well and happens very frequently, What I need to do is find it and improve it. By doing this I think I 
could improve my efficiency and it's the same for everyone.
