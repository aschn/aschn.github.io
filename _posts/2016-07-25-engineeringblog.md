---
layout: post
title:  "The engineering blog meta-post"
date:   2016-07-25 10:18:00
---

You just finished a pretty big project at work. Congrats! Your PM is happy, your users are happy, even marketing is happy.

And then you hear this: "Can you write a blog post about that?"

Um, what? But I’m an engineer, you think. I haven’t written anything longer than a facebook rant for months, maybe even years. Where would I even start?

Here :)

## Start with who and why

Just like with any project, the first thing to figure out is why you’re doing it. Who will be reading the post? What do you want them to take away from it? You can think of this step like defining the user stories for your blog post.

If you simply do a brain dump of your process behind the project, you’ll do a pretty good job of satisfying one user story:

**Other developers who are googling around because they’re trying something similar will get a head start on solving the problems we’ve solved.**

Write what you know, right? But whoever asked you to write the post probably has other user stories in mind too. Depending on the person and the project, here are some guesses of what they might be looking for:

**Users will be happy that we’re incorporating their feedback and improving to meet their needs.**

**Prospective hires will think that we’re smart, friendly folks who use snazzy tools to solve interesting problems.**

**Investors will be impressed that we’re growing fast and hitting milestones they care about.**

**Clients will see that we’re thoughtful, capable, experienced, and able to communicate clearly.**

If you’re not sure which user stories you should be working toward, have a chat with whoever asked you to write the post, and maybe other people on your team too. It’ll save you time going back and forth on edits later. Plus, you might be surprised by the insights you get into what your coworkers care about and where they see your company going.

Last but not least, it’s totally ok for you to add these user stories to your backlog too:

**My next employer will be able to discover my great work. (Especially important if you work on internal products or dislike networking!)**

**I’ll get better at explaining myself to coworkers, friends, and family so that they understand what I’m thinking and feeling.**

**Next time I have imposter syndrome, anxiety, or depression, I’ll be able to look back at evidence that people valued my contribution.**

Practicing writing also practices empathy and builds self-esteem. If you find yourself losing motivation to blog, remember that the time away from code is still time well spent for you personally and professionally.

## A framework for what and how

Once you’ve selected and prioritized your user stories, it’s time to start writing. Some people prefer to start with an outline then flesh it out, which might feel like stubbing out methods for a new class. Other people get better results from stream-of-consciousness followed by editing, like spiking and refactoring. Still others like to learn from frameworks and examples, then adapt them to their needs. Each of these styles are equally valid, so go with whatever feels most natural to you.

Since I’m in the framework camp, I give you: a framework for engineering blog posts! And if you’re in a different camp, you might find that you converge on a structure similar to this too. You don’t have to choose between strong content and strong narrative.

1. What’s the problem? Succinctly set the stage for the “developer googling” user story up front, so the people who care know to read on and everyone else can move right along to the next search result. *“I rebuilt our entire front end in TheNewHotnessJS.”*

2. Why does the problem matter? This is where you can start to weave in the user stories from marketing, management, etc. You can even include a tasteful humblebrag about your rabid fan base, mandate to keep up with the latest tools, or scaling challenges. *“This update allowed us to start offering our #1 most requested feature: accessible rainbows.”*

3. What were the design specs for a solution? Laying this out can help other engineers narrow in on the right solution for them, even if it’s a different path than what you selected. Plus, it might highlight to your customers that you value listening to their needs. *“Our legacy front end was written in YeOldeFrameworkJS, and we needed a more modern solution with better rainbow support.”*

4. How did you explore possibilities and choose a solution? I wish more people would talk about this! This can give prospective hires or clients a great sense of your team’s actual process and communication style. *“After our designer met the developer of TheNewHotnessJS at KatieConf, we fell in love with the all-emoji documentation.”*

5. Why is this solution a good one? What alternative solutions did you reject? A quick pros and cons list can be a good way to show how your solution satisfies your design requirements. *“We decided that this had better rainbow features than any other framework on the Top 1000 JS Frameworks of 2016 list.”*

6. How did you carry out the solution? At last, the meat of the developer user story! As with any other documentation, include enough detail so that you’ll thank yourself later. Since this is for public consumption, though, keep in mind that some details might need to stay proprietary. *“I started with this 140-character ‘hello world’ demo: [code blob here]”*

7. Did you encounter any surprises along the way? Sprinkling in one or two unexpected hiccups (and your creative workarounds) creates a more engaging read, and can help you avoid sounding overly simplistic or pedantic. Plus, these are the gems that are often most useful to other engineers. *“It turns out that TheNewHotnessJS doesn’t support 8-bit rainbows out of the box, so I added some middleware that solves the problem using SQL injection.”*

8. How’s it working so far? What’s next? Every story needs a conclusion. Any before-and-after visuals, happy user testimonials, or 10x-ed metrics you can include? If not, maybe wrap up with a hint at where this project might go in the future, or what you might do differently next time. *“Since launch, traffic for rainbows has increased 111%, and TheNewHotnessJS is performing beautifully.”*

Ta-da, a completed engineering blog post draft! All that’s left is to spice it up visually with some gifs, gists, or graphs to match your (and your team’s) style. And just like code review, don’t be afraid of soliciting and responding to constructive feedback.

## Don’t take my word for it

Want to read some real examples before diving in? Here’s a [list][blog-list] of hundreds of engineering blogs you can check out. I think [Airbnb][airbnb], [Caktus][caktus], and [Mailchimp][mailchimp] do a particularly good job of melding useful, clearly presented technical content with insights into company culture and priorities.

And for even more blog post frameworks and inspiration, the Talk Python To Me podcast has a great [episode][episode] about A. Jesse Davis’s PyCon [talk][davis-talk] (also [blog post][davis-post]) about writing a good programming blog.

Happy blogging!

[blog-list]: https://github.com/kilimchoi/engineering-blogs
[airbnb]: http://nerds.airbnb.com/
[caktus]: https://www.caktusgroup.com/blog/
[mailchimp]: http://devs.mailchimp.com/blog/
[episode]: https://talkpython.fm/episodes/show/69/write-an-excellent-programming-blog
[davis-talk]: https://www.youtube.com/watch?v=eHXq-IzlGUE
[davis-post]: https://emptysqua.re/blog/write-an-excellent-programming-blog/
