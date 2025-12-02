# [I.e. AI, AI, Oh](https://www.youtube.com/watch?v=eudOwe3Rz-0)

## The Turing Test

The [Turing test](https://en.wikipedia.org/wiki/Turing_test) is not a test for intelligence. Back in 1966, running on puny hardware, [ELIZA](https://en.wikipedia.org/wiki/ELIZA) was almost, kinda, able to pass it.

But I was not aware of ELIZA in 1997 when I first got access to the Internet. And, of course, to the [IRC](https://en.wikipedia.org/wiki/IRC). One of the first things that happened to me after joining #bulgaria on EFnet was to be kicked from the channel by someone with the nick Doroty. Little did I know that this was a [bot](https://www.youtube.com/watch?v=RYQUsp-jxDQ). I immediately confronted her in a private conversation. I figured out that something is fishy no earlier than the fourth line of exchange. I later learned that the bot chose randomly from a pool of about 100 fixed lines disregarding any input from me.

Perhaps I was young and foolish but at that time I realized bots don't need much more than a bit of luck in order to pass the Turing test for every specific human evaluator.


## The Artificial Intelligence Course

One year later, I enrolled in a course named "Artificial Intelligence" at my university. The exam was easy, compared to subjects like Differential Equations, Statistics and even the Theory of Computation. Here is what I learned about neural networks:

1. A neural network must be trained with a lot of data in order to be able to do something useful.
2. An useful neural network is so huge that it is not debuggable. No one can tell why it arrives at a specific conclusion. Magic.
3. A neural network leans towards the mean of its training data. The more you train it, the more mediocre it becomes.

As of 2025, we have solved the problem posed by 1., even if at a huge price (both in money and to our planet's climate). 2. has become an even harder problem. 3. can be reworded as: A neural network cannot devise anything exceptional - it just regurgitates its training data.


## AI Overviews in Google Search

Barring some demos of chat-bots by colleagues of mine on how they will save us from processing customer bug-reports (yeah, right), my first encounter of LLMs were the AI overviews of Google. At first, I thought that the thingy above the search results was a quote from some more distinguished source, like the official documentation or at least Wikipedia. But in most cases, the advices from the overview were wrong. For example, once I was looking for a Linux kernel parameter for setting this and that. The AI overview, without any uncertainty, claimed that the name of the parameter is this.and.that but in reality it was something similar, yet different (e.g. that.and.this). I enthusiastically set the parameter in /etc/sysctl.d, rebooted and... nope, still no fun. The result was a waste of time pretty much every time I paid attention to the overview. I started to ignore the fake stuff and eventually I learned what it is.


## ChatGPT Itself

My next encounter with an LLM, this time with the much hyped ChatGPT, was in September 2024. I was playing in a [CTF](https://en.wikipedia.org/wiki/Capture_the_flag_(cybersecurity)) competition. At one point I got two fractional numbers that I knew are the astronomical coordinates of a star. If I'd enter the name of the star in the CTF grading system, I'd get some points. I asked ChatGPT and it very confidently told me that this is Star A. No points. "Are you sure, Wikipedia shows different coordinates for Star A?" "Yes, I am absolutely sure." Then I did it the old-fashioned way: I downloaded Google Earth, entered the coordinates, and saw that the star is, in fact, Star B. I got the points. ChatGPT was still absolutely sure that Star B was not what I was looking for. Very confidence. Many wrong. Wow.

On another occasion, I asked ChatGPT to count the number of characters in a string. Luckily, the number it gave me was ridiculously low and wasn't even even (as I was expecting). WTF, a computer that cannot count?!

Then I realized that an LLM is not your grandmother's computer. It is not a computer at all. It is a chat-bot, a somewhat realistic simulation of a conversation. Precision is not among its goals. Only plausibility is. Is this number a plausible answer? Of course - it is a number. And if the English language had a bit different semantics, it might have even been the exact one.


## Doom-Scrolling

At the end of 2024 I got kicked out (not LLM-related) of my job. Naturally, I started doom-scrolling LinkedIn in order to get an idea of what interviews look like nowadays, what my chances at finding a job at my age are, etc. What I found was a tsunami after tsunami of hype about LLMs. The term "vibe coding" was codified during my quest for a job. Rather sooner than later, all white-collar jobs (with software-producing ones first) will be replaced by AI. The LLMs are learning at an exponential rate and we are months away from Artificial General Intelligence (AGI), so [Jonh Connor](https://en.wikipedia.org/wiki/Skynet_(Terminator)) better hide in the nuclear shelter ASAP. As a result, the managers in the technological companies are holding their breaths and refraining from new hires. OK, the last one was useful in my situation.

There were (and still are) countless of postings boasting 10x software development enabled by vibe or merely LLM-assisted coding. Complete original applications were built in hours by a single seasoned professional who, of course, knew what he was doing (supposedly, reviewing and fixing the LLM-produced code). And funnily enough, no example code to back these claims. All successful code, produced by LLMs, turned out to be highly secretive proprietary software. Coincidence?

The sceptics (including yours trully) were scared to say anything, at least at first. What if the hypers are right? Perhaps the steam-powered looms looked ridiculous in the eyes of the original luddites but then they took their jobs anyway. What if we are the present-day [buggy whip](https://en.wikipedia.org/wiki/Whip#Buggy_whip_and_coachwhip) proponents?


## [Extraordinary claims require extraordinary evidence](https://en.wikipedia.org/wiki/Extraordinary_claims_require_extraordinary_evidence)

Hype not subsiding, the sceptics started to ask some inconvinient questions. Some even tried vibe coding and reported that the resulting code is close to unmaintanable (even more funnily - again without example code). ChatGPT 5 came out and no one was impressed - at best it was reported as an incremental improvement over ChatGPT 4. Some AI researchers shyly suggested that maybe [the hallucinations will never be eliminated](https://www.computerworld.com/article/4059383/openai-admits-ai-hallucinations-are-mathematically-inevitable-not-just-engineering-flaws.html).

I found a job and even installed Copilot in my IDE. I let it write a whole method once, only to refactor it inside-out. Occasionally, it does some copy-pasting for me. Most of the time its suggestions have nothing to do with what I have in mind. I even tried some vibe coding but not on a real project. I keep using ChatGPT as a glorified search engine and it keeps misleading me (and then apologizing). In general, I give AI-assisted coding a rating of "meh".


## Still Sipping from the Kool-Aid

At the moment (late 2025), the prevailing opinion among the sceptics is:
- AGI is nowhere near.
- LLMs will not replace many jobs.
- But LLMs have a positive value and being able to use them will be a crucial ability of the white-collar worker of the near future.

I do not share the last part. IMHO, LLM use is not acceptable in any field where a simple preventable mistake may cause harm. The reason is simple: AI cannot bear responsibility. Here are some examples:
- Law. Hallucinations of precedents can easily lead to a wrongful conviction in case law. I still cannot believe how lawyers caught using LLMs are not being disbarred on the spot.
- Practicing medicine. Dr. House's approach of confirming or rejecting the diagnosis based on an autopsy is not applicable in the real world.
- Development of any software that has anything to do with security (nowadays, this includes pretty much everything).

## Applicability of LLMs in programming

### Hallucinations in AI-assisted Program Code

Hallucinations for program code are bugs (otherwise they would not be considered as such). Any bug has the potential to become a security vulnerability. Even dead code may get activated under obscure conditions and increase the attack surface. Code of low readability (not exactly a hallucination itself but a common defect of LLM-produced code), even if correct today, makes future bugs more likely.

LLM proponents and even most of the sceptics suggest the following counter-measure to hallucinations and low readability: code reviews by seasoned programmers. This may work only in the short term (we're still here). Here is why:

Programmers become good at reviewing someone else's code by performing the following activities:
- Writing code.
- Having their code reviewed by colleagues.
- Performing reviews themselves.

All of the above are required. The less code you write, the weaker your code-reviewing abilities become.

There is one more circumstance that will make the approach of "LLM codes, human reviews" unsustainable: human negligence. Sooner or later, the human reviewers will switch to rubber-stamping, especially if the code is of low readability. This happens even without LLM-assisted code - big changes with hard to understand semantics frequently get few or no comments from the reviewers.


### Mediocrity

Let's assume for a moment that the hallucination problem gets solved. Then remember that neural networks tend to produce mediocre results and are not capable of original... uhm... "thought" (3. above). Can't we use them at least for the boring stuff?

A lot of the software that needs to be written is not particularly challenging. It does not need neat tricks. Mediocrity should be fine for it, right?

But productive code is of above mediocre quality. While this may sound as a paradox, it is easily explainable. Mediocre code in the context of LLMs is the mean of all the code examples used to train them. This includes:
- Textbooks, tutorials and their likes. Unless the studied topic is security then the latter is simply ignored. Productive code, however, needs to be secure.
- StackOverflow, Reddit, Wikipedia and similar user-generated sources. The same concern as above.
- All possible code found on the Internet, most of which has never been used productively. You know, those repositories with a single commit from 8 years ago.
- The training data certainly includes a lot of code of productive quality. But the above bring the mean down.

Additionally, the merged code in a project is of higher quality than the mean level of the programmers working on it. A piece of code written by an inexperienced programmer will get reviewed by a more experienced one and this will get its level up. A review by an inexperienced programmer does not push the quality down.

Of course, vibe coding is totally fine for prototypes, provided no attempts for their direct productization are made afterwards.


### A Simpler Argument

"A computer will do what you tell it to do, but that may be much different from what you had in mind." - [Joseph Weizenbaum](https://en.wikipedia.org/wiki/Joseph_Weizenbaum) (the creator of the aforementioned ELIZA)

We have spent the last 70 years defining formal languages that help up us tell a computer what we want it to do while bringing down the likelihood of misunderstandings. And we have done a pretty good job. We have various programming languages of different levels of abstraction that give us good confidence that a computer will do what we really want.

And now come the Large *Language* Models. The language here is not a formal one. It is a context-dependent language, riddled with ambiguities, intended to be complemented with things like intonation and facial expression. It is naive to expect that inserting our beloved English (or whatever tongue) in the tool stack will not lead to a higher incidence of bugs.


## What Could Possibly Go Wrong?

Are we willing to lower the quality of software for the sake of making a few billionaires richer? I'm not. Humanity, represented by the said trillionaire-wannabes, seems ready to try. The attempt will fail disastrously for one simple reason: the [black hats](https://en.wikipedia.org/wiki/Black_hat_(computer_security)). They will not willingly dumb themselves down. The incidence of exploitable vulnerabilities will go up.


## AI Slop

Enough with software. What's with the arts?

In late 2024 I was watching season 2 of [Silo](https://www.imdb.com/title/tt14688458/). Just like with other mystery-based shows, tiny details matter. So instead of watching each episode multiple times, I resorted to searching YouTube for videos that highlight the details I might have missed. Such videos should have existed, right? And they probably did but I could not find them. All I could find were AI-generated retellings of the episodes. Totally bland. Told with an emotionless voice. Full of inaccuracies.

AI slop can drown us and, unfortunately, it will. The war for clicks and views basically guarantees that. Many people are doing their art only for the recognition they get from their fans. When they become unfindable in the ocean of AI-generated mediocrity they will simply give up.

AI slop is great for disinfomation campaigns. The latter have the potential to end liberal democracy.

BTW, AI slop and hallucinated coding bugs are the same side of the same coin.

But AI slop is what ultimately may lead to the demise of LLMs. Remember 1. above? If you want your LLM to become "better" (however this is defined) you must train it with more data. But remember 3. above? If you train an LLM with its own vomit it will only become worse - the so-called [model collapse](https://en.wikipedia.org/wiki/Model_collapse). Until recently, this was not a problem. LLMs were trained on everything their creators could lay their hands on. Good or bad, all content on the Internet was human-generated and at least somewhat original. Discerning orignal content from AI slop is hard even for many humans and it is certainly not doable en masse. Training an LLM one article at a time will not produce noticeable effects either. It is very likely that "the best" LLMs ever will turn out to be those from 2025, or maybe even 2024.


## Copyright

Training an LLM is feeding it as much data as possible, most of which is copyrighted under [not-so-permissive](https://en.wikipedia.org/wiki/Free-software_license#Comparison) licenses. The LLM owners claim that this is the same as a human reading/listening/watching the material. But we know it isn't. They know it isn't. Everybody knows it isn't. The training material stays in some form in the neural network even if nobody knows how to decode it (because of 2. above).

But how do the LLM owners avoid the wrath of the copyright owners? Why aren't they swamped with lawsuits? I genuinely don't know. The only hypothesis I have is that those that have the greatest copyright potfolios and can hit really hard are the same who have invested in LLMs the most expecting them to become AGI.


## tulips.com

Pretty much nobody denies the existence of the AI bubble. But some claim that this time it is different (yeah, it always is). The bubble will not pop because the extraordinary expectations will, in fact, materialize! The AI companies are burning through investors' money like ~~there is no tomorrow~~ LLMs will soon become AGI and will let said investors rule the world.

If I am certain in one of the claims made in this document, this is the one: **LLMs will not become AGI**. AGI is certainly possible - after all, our brains are made of ordinary atoms. But the limits of the LLMs have been reached. They can only go down the slippery slop(e) from here on.

Many people cannot find jobs now not because no employer needs them but because said employers naively believe that they will not need them. Some employers hold back projects, others double down on LLMs and introduce problems that will be harder and more expensive to fix later.

The sooner this bubble pops, the better (or less bad) for everybody, including the aforementioned investors. People will become employable again, the projects will finally get moving, the wages will go up, remote work will no longer be denied for those professions that can utilize it.

LLMs will not disappear after the bubble bursts, of course, just like the Dutch did not lose their affinity for tulips. But a long [AI ice age](https://en.wikipedia.org/wiki/AI_winter) will very likely ensue. The LLM usage prices will have to become sustainable (i.e. much higher) and only those who get real value from LLMs will continue to use them. Hopefully, AI slop will disappear. I am not so optimistic about the disinfomation campaigns, though.


## The Minority Report

But why should you trust my fringe opinion? Well, probably you shouldn't but in case you decide differently: Those are my credentials, and if you don't like them... well, I don't have others.

I have an MSc in Computer Science. It is from 2001 and is not AI-related. I have been programming ever since I discovered computers in 1991. Programming is both my hobby and my profession. Rarely a day passes with me not reading or writing some code. I am not your average CEO of a multi-billion technological company. I am not even a low-level manager. I am still in the trenches and I refuse to retreat from them. I have seen a lot of dangerous bugs, many of them authored by very experienced programmers (including me). I have been interested in the security aspects of software since my day 1 in front of a computer. I have some experience as a penetration tester, even though I have never worked formally as one.


*Vladimir Panov, 2025.10+*
