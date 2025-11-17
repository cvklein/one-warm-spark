---
title: "Explaining the joke"
date: 2025-11-17
---
[Yesterday's post](https://cvklein.github.io/one-warm-spark/2025/11/16/AI-Assessment/) about AI and assessment was prompted by being sent, for the hundredth time, something that said "Well, AI is here to stay, so we have to teach students how to use it."

I think this is incredibly naïve, in two ways.

First, generative AI is here to stay. But that's not the same as saying that cheap, good, easily accessible AI is here to stay.If you're imagining a future where your students get cheap, good, easily accessible AI for free, ask yourself: who's making a profit in that scenario? How does all that venture capital get its money back?

Generative AI is *staggeringly* expensive to run. My story was partly inspired by [recent](https://pluralistic.net/2025/09/27/econopocalypse/) [reports](https://www.wheresyoured.at/make-fun-of-them/) that OpenAI is losing billions of dollars a year just on inference. If you're not familiar with the jargon, inference is actually running the AI model to get the answer. So there are enormous losses involved in just delivering the core product -- not training new models, not salaries, not infrastructure.  *Just doing the thing* is an insatiable money pit.

But technology will save us, Colin! Costs of inference will go down, new chips, blah blah.  I mean, sure. Maybe electricity will also end up too cheap to meter. The problem is that there are hard scaling laws at work here. Models get better by making the context windows larger.  Making context windows larger scales badly. That's a fact about how the transformer architecture works.  That's why current models chew through electricity and GPUs like Cookie Monster after a few bong hits.

But ok, put that aside. Pretend tech is magic.  No matter how cheap things get, someone's gotta get paid. Right now we're in the stage where venture capital is shovelling money as fast as it can to effectively subsidise the staggering losses of AI. They're not doing that because they're nice, or because they like your students. They're doing it in the hopes of getting even more money back. Many of them will be disappointed. But eventually, someone's going to make a lot of money.

Now, that could end up looking a lot of different ways. The story assumes that OpenAI ends up like Adobe or Microsoft. Your University / workplace is on the hook for millions of dollars a year for a site license. Or you're an independent professional and get slowly screwed by weird subscription fees to get the tool that you're now dependent on.  But unlike (say) Microsoft Word, there won't be easy cheap alternatives: remember, part of the problem is that *just doing the thing* is expensive. Free models will go out of date quickly. Or will only run with short context windows. Or generally suck. And what's going to pay for the electricity and GPUs? Presumably, what the modern internet excels at: noxious bullshit advertising.

The world we should be preparing students for is not the world we're in now. It's a world where people charge money for AI. As much money as they can get away with.  Remember, there are lots of awesome things that we could do with current technology that we don't do, just because capital demands a return.  When I am in grumbly old man mood, I tell my students about the halcyon days of 2006, when I could get basically any movie ever made from Netflix. Gosh, that was great. We could do that now! The reason why we don't is not technology,  but the iron demands of capitalism.  And if anyone tells you differently, ask them what they're selling.

Second point of naïveté, following off from the first. There's this idea that we somehow need to teach students how to use the technology.

Now, there are a few ways to take this. I think sometimes people think something like  "wow, a new technology, the kids don't know how to use it! Maybe we need to teach them, like, the ins and outs of prompt engineering and such." Pshaw. The kids know how to use Chat. They use it more than you do. [Way more](https://arxiv.org/html/2501.10551v4). Also, chat-based LLMs are made to be easy to use: the big problem with LLM hallucinations is that it's trivial to get LLMs to confidently spit out bullshit. LLMs are like iPads. You pick one up, you fiddle with it, you've basically got it. A lot of smart people were paid a lot of money to make it thus. We do not spend any time teaching students how to use iPads.  

Now, maybe in one of the possible future cyberpunk dystopias where your salary is docked for every token over your allocation?  Sure, then let's teach them to keep it tight. But for now, there's no tech problem that students need to be taught to solve.

(It's not that new technology doesn't require big instructional changes sometimes. My father was a landscape architect.  He was trained in hand drafting. He had a beautiful drafting table, full of all kinds of neat little bits and bobs for measuring perimeters and those cool triangular scale rulers. His handwriting was great. Mid-career, CAD got too big to ignore. So he retrained. Later, when he became a professor and started teaching,  he waxed nostalgic about the value of starting with hand drafting before you moved to CAD. You didn't get the same feel for drawing that he had learned, he said. But he didn't push it.  Kids started with CAD from year one, day one; that was the modern world, and they needed to start early to master the tech. But that's because CAD is hard and finicky and also one learns to draft by learning to draft with it because that's definitely what you'll be using in your job. Different scenario.)

The smarter thing to mean by this something more like "Hey, students, use this the way *I* use it. Don't believe all the bullshit it spits out. Check your sources! etc!" People who like to say this tend to forget that they already have these skills, and they learned them in a different context.

 The technological analogue is a bit like calculators[^1]: you need to learn how to do the thing so you know when to do the thing and what failure to do the thing looks like, and and once you do that you get an extra-fast tool to help you out.

But of course, the analogy is there to make the problem obvious: *you shouldn't teach students arithmetic by using calculators*. You teach arithmetic first. Then you add calculators for the stuff they've mastered to make it faster and more reliable. If they start with calculators, they're not going to understand what they're doing, and they're not going to know when they've messed up. That's why we still teach arithmetic: not just in spite of calculators, but precisely so people know how to do the right thing when they have one.

Here's another way to put the same point. Suppose you had a perfect oracle, who would answer all the questions you put to it at no cost to you. Sometimes a bit touchy about phrasing, true, but phrase things correctly and you get back whatever you want to know. Does anyone need to teach you how to use the oracle? No, *because you can just ask it how it should be used*. It's going to be its own best instructor. If ChatGPT ends up like that, we're all out of a job. We don't need to teach students how to do anything. Not even where to find the unemployment line.

But if LLMs are not perfect oracles---and they obviously aren't---then the best thing we can do, by a long shot, is teach the skills that will, incidentally, let you realise when LLMs are making shit up, or has written facile and content-less prose, or whatever.

I'm not saying that we need to teach things in the same way, or using the same assessment structures, or whatever. What we had before often didn't work terribly well. But the idea that we need to suddenly drop everything and reconfigure University education is not a *fait accompli*. It's a sales pitch. And it's a sales pitch made by people who are desperate to sell you access, at extortionate prices, to the very thing they tell you the future will require. 




[^1] I stole the analogy from my wife. Thanks, dear!  Also note to self, figure out how footnotes work, because this ain't it.

Permalink: [{{ site.url }}{{ page.url }}]({{ site.url }}{{ page.url }})
