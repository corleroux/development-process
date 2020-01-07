# Untitled

Your Best Agile User Story

* Skip to primary navigation
* Skip to main content
* Skip to primary sidebar
* Skip to footer

[![](file://C:/Users/Corl/Documents/BRS/NTU/Your%20Best%20Agile%20User%20Story.assets/1769a2ffa3f44eebb3eec6b824a5db3d.svg?lastModify=1578363932)](https://www.alexandercowan.com/)

[Alex Cowan](https://www.alexandercowan.com/)

A set of tutorials on the Venture Design process.

* [Home](https://www.alexandercowan.com/)
* [Venture Design](https://www.alexandercowan.com/venture-design/)
* [Learn/Teach](https://www.alexandercowan.com/learn-teach/)
* [The Interdisciplinarian](https://www.alexandercowan.com/blog/)
* [Workshops](https://www.alexandercowan.com/lets-work/)
* [About Me](https://www.alexandercowan.com/about/)

## Your Best Agile User Story

Table of Contents

* Creating a User Story
* Knowing If You Have a Story
* Designing Better User Stories
* Testing User Stories
* Developing with Stories & Story Maps
* Example A: Example User Stories from Enable Quiz \(Startup\)
* Example B: Example User Stories from HVAC in a Hurry \(IT Project\)
* Citations and Image Credits

Views: 115,329

* [Click to share on Facebook \(Opens in new window\)](https://www.alexandercowan.com/best-agile-user-story/?share=facebook&nb=1)
* [Click to share on Twitter \(Opens in new window\)](https://www.alexandercowan.com/best-agile-user-story/?share=twitter&nb=1)
* [Click to share on LinkedIn \(Opens in new window\)](https://www.alexandercowan.com/best-agile-user-story/?share=linkedin&nb=1)

This article will show you how to create better user stories. You’ll learn how to write them like a designer, test them like an entrepreneur, and use them to drive better discussions like an agile coach.

### &lt;a id="Creating\_a\_User\_Story"&gt;&lt;/a&gt;Creating a User Story

#### What is a user story?

User stories have a specific format:

 “As a \[persona\], I want to \[do something\] so that I can \[realize a reward\]”

This format is designed to help the story writer be descriptive and to drive better discussions about implementation with the rest of their team. Done right, the format helps prompt the following important questions: ![](file://C:/Users/Corl/Documents/BRS/NTU/Your%20Best%20Agile%20User%20Story.assets/286b1d4abebb4733bb00b1be9d06b96e.jpeg?lastModify=1578363932) If answering those questions seems like a lot of work, I’ll mention here that taking stock of new product failure rates, IT project failures, and the portion of features that actually are substantially used, something on the order of most or at least ‘a lot’ of software ends up lightly used or quickly scrapped. Skillful use of stories will improve your outcomes, your economics, and, most importantly, your team’s sense that the work they’re doing matters to the user.

If you’re writing a story, your job is the fill in the \(red\) blanks. The persona is a vivid, humanized, yet operational description of your user \(see also [personas tutorial](http://www.alexandercowan.com/tutorial-personas-problem-scenarios-user-stories/)\). The ‘\[do something\]’ is a goal you assume the user has. The ‘\[realize a reward\]’ clause is a _testable_ statement of how you’ll know if the user realized that goal.  The \[realize a reward\] clause is the most neglected by most story writers and yet it’s the most important. The single best litmus test for whether you have a good story is whether you could put a simple prototype in front of a user, ask them to act on the goal you’re assuming, and see if they can achieve it.

Let’s look at a specific example to see how that would work in practice. Enable Quiz is a fictional company I use in a lot of my examples. They’re \(fictionally\) building an app that allows an HR manager to screen job candidates for a specific, technical skills sets relative to a job description. We might describe the goal of building a quiz to screen for a new open job description with this story:

“As an HR manager, I want to match an open position’s required skills with quiz topics so I can create a quiz relevant for candidate screening.”

With this story, a designer or developer \(or someone acting in that role\) could put a sample job description in front of an HR manager, give them the goal of picking quiz topics for it, and see if they’re able to realize that goal with the team’s current prototype or working software.

There are schools of thought that the specific story format or the third clause \[realize a reward\] isn’t that important. That just isn’t consistent with my experience. Every time I talk to a team that’s loose with story format, I’m seeing data that indicates they would benefit from front-loading value and driving to more specifics about user goals so they iterate to something valuable and avoid waste.

**Pro Tip**: There’s a tendency to want to build software that’s ‘not specifically wrong’ versus specifically right or specifically wrong. Resist it. Successful teams build in small batches with careful observation about whether they’re right or wrong, but they build against tightly defined assumptions about the user’s goals.

#### How do you organize stories?

Epic stories describe a user action and the child stories detail that action. Test cases and notes are a place to add further details and points to discuss relative to individual stories. Both types of stories have the same format- the format you saw above.

![](.gitbook/assets/286b1d4abebb4733bb00b1be9d06b96e.jpeg)

There’s a school of thought that epics are really big, and they certainly sound big. My general advice is to keep them relatively small. I do a lot of training on story writing workshops and 95% of the first time child stories I see are actually what I would start with as epics \(and the draft epics are overly broad in scope\). Why? Well, developing and operating software is expensive. You might as well have good narrative coverage with stories on everything you’re building to drive better discussions about what will be valuable to the user and how you’ll test it. The alternative is to just guess and I can tell you how that works out- not well.

Let’s look at a specific example. Returning to the narrative of an HR manager who wants to create a screening quiz for a new job description, we might start with this epic:

“As the HR manager, I want to create a screening quiz so that I can make sure I’m prepared to use it when I interview job candidates.”

The child stories and their test cases them decompose that epic into more detailed steps \(see Reference A for the full example\). By the way, if you have the urge to start drafting, good on you and here is a Google Doc’s template you may find helpful: [User Story Template](https://docs.google.com/document/d/1M7UGO-XymKBNfFvqIjeWdABO7z1f4JOaje_VjCOi4ss/edit#bookmark=id.940hayl8xj47).

#### User stories are a type of specification, right?

NO! They’re supposed to serve as a centerpiece for frequent interdisciplinary discussion about how to implement something valuable to the user. This is kind of where the use of stories and the practice of [agile](http://www.alexandercowan.com/agile-just-basics/) need to converge. If you’re not familiar with agile, I recommend the aforementioned link or, hey, my [agile course](https://www.coursera.org/specializations/agile-development), but the basic idea is that instead of working in a sequential \(waterfall\) way from specification to development to test to release you’re doing all of those things together in small batches. In the next section, we’ll step through how to create stories like a designer, but I’ll close with a few cautionary notes about what to watch out for with your user stories.

#### Why are most user stories so bad?

1. **Mistaken Belief that Software is Automatically Magic** I know it sounds silly, but you’re probably working with people that implicitly think this to a degree. It’s true- amazing things happen with software. But that software wasn’t automatically magic; someone had to put the magic in it. That someone is you. The next section will show you how to conjure that magic.
2. **We Measure Our Efficiency Locally** To a degree, we all just want to finish our work and go watch Netflix. That’s fine. That’s natural. But, if you want to build great software, you have to want to consistently ask the hard questions of your colleagues and your work about whether what you’re doing is still making sense. Is there a strong, testable case that it’s going to valuable to the user? That’s hard to do consistently. A lot of product managers just slam user stories into JIRA and call it a day. It’s not that hard to run a more thoughtful, disciplined program, but it’s not that easy either. You have to really want it.
3. **No Data** You have to know your user and what’s on their A-list to write good user stories. Without that, you’re just going to be groping at some idea about what the software might do and then spending way more money than you need to to find out if you’re right or not. There’s an easier \(and way cheaper\) way, and that’s what this next section is about.

### &lt;a id="Knowing\_If\_You\_Have\_a\_Story"&gt;&lt;/a&gt;Knowing If You Have a Story

#### Who are we talking about?

Remember when your high school English teacher told you to ‘Write about what you know?’. That was always hard for me in high school because, really, I didn’t know much. Likewise, if you don’t know your user, writing good stories will be hard. This is not to mention that now what you’re writing really matters- you’re about to define lots of spending on creating and operating software.

The alternative is to end up on one of these two anti-poles of design failure:

![](file://C:/Users/Corl/.config/joplin-desktop/resources/9f033786bca24b8282678aa3f8f0d17a.png?lastModify=1578363932)

Do precisely what the user asks and you’ll probably end up in what my friend David Bland calls the ‘Product Death Cycle’: a\) no one uses the product b\) you ask customers what features are missing c\) you build these ‘missing’ features d\) go back to ‘a’. Assume that you already have all the answers and you’ll probably end up with a market size of close to one \(you and maybe a few people just like you\).

![personas-icon-200px](file://C:/Users/Corl/.config/joplin-desktop/resources/77b12fa51c1448d28b54cb4fcebef4bb.png?lastModify=1578363932)What’s a conscientious product person to do? The good news is that there’s an approach that consistently works. The bad news \(it’s not really bad ; \) \) is that it takes some work of a type that may be new to you. The tool I’d start with is the idea of ‘personas’. These are humanized views of your customer, be they buyer and/or user of your product. It turns out this is the most actionable and testable way to build products and systems.

![personas](file://C:/Users/Corl/.config/joplin-desktop/resources/a3d40a64ffcc4b77a5cf33cac2f31070.png?lastModify=1578363932)The basic idea is that you want to name the persona to humanize them \(‘Helen the HR Manager’\) and have an idea about a day in their life. What shoes do they wear? What’s the first thing they do in the morning? Then you want to dig into how they relate to your product or system. What do they Think about how things work now vs. how they’d like them to be? What do they See others doing that influences that perspective? How do they Feel about the job or habit you’re building software to improve? What do they actually Do in your area of interest? How much? How often?

You’ll probably find you need to go out and talk to a few of them to obtain this information, but if you have a strong Think-See-Feel-Do understanding of your user, I think you’ll find stories are a lot easier to write and to discuss.

For more depth and some examples see: [Personas Tutorial](http://www.alexandercowan.com/tutorial-personas-problem-scenarios-user-stories/).

For notes on how to interview users to create personas see: [Customer Discovery Handbook](http://www.alexandercowan.com/customer-discovery-handbook/) \(Persona Hypothesis\).

For a structured tour of these, see [Agile Meets Design Thinking](https://www.coursera.org/learn/getting-started-agile) on Coursera and the Personas section of [Running Design Sprints](https://www.coursera.org/learn/running-design-sprints).

#### What do they want?

![problem-scenario](file://C:/Users/Corl/.config/joplin-desktop/resources/414a90ba19264e68b9c5e336062a9513.png?lastModify=1578363932)Once we have a strong persona or personas, we need to consider and test what underlying jobs or desires we’re going to make better for this user. Do they really exist? Are they important? This is worth exploring since if you’re solving a problem that doesn’t exist, you can develop perfect software and still fail to deliver any value to the user.

How do you identify and describe these problem scenarios? First, simply consider what it is that you’re actually doing for the user- helping them stay connected to friends? checking their accounts payable for suspicious patterns? Then make sure you can describe an alternative \(ideally you’ve talked to users and already know\). Maybe your user sends out a holiday card to stay in touch with their friends. Maybe they just look at large accounts payable and spot check/audit them. Make sure your definition of the problem scenario is general and could apply equally well to the current alternative as it could to whatever it is you’re planning to do to make things better. This will help you avoid bias and stay focused.

Let’s look at a specific example. For Enable Quiz \(see above\), their core problem scenario of interest might be:

‘Screening technical talent.’

I said a good problem scenario can be applied equally well to the alternative or your new proposition. Helen the HR Manager’s alternatives for screening technical talent might be: checking resumes, calling references, or just taking their word for it. I’d say the problem scenario definition works for those alternatives as well.

What if we took the problem scenario and went up a level of abstraction? Then it might be something like ‘Hiring technical talent.’ Now, that’s probably too broad, but it’s helpful to know so that a\) you know you’re at about the right level of abstraction with your core problem scenario and b\) that you’ve identified the general area in which you’re working.

What if we went down a level? Then we’re probably get lots of more tactical problem scenarios like:

‘The HR manager preparing a new quiz from an open job description.’

‘The HR manager sending notes on candidates to the functional manager.’

These all flow from the core problem scenario on screening, but we’d still want to make sure they’re important before we start writing stories and consider investing in software. A summary of the first few problem scenarios for Enable Quiz might look something like this:

![](file://C:/Users/Corl/.config/joplin-desktop/resources/aaa51d0b3ae74e88b57472a0fcc2fe0a.jpeg?lastModify=1578363932)

When you work forward to build up your understanding, the sequence goes something like this:

![](file://C:/Users/Corl/.config/joplin-desktop/resources/2249613a9fbd420897668713e363a5dd.jpeg?lastModify=1578363932)

Here’s an example of what it might look like in the case of Enable Quiz:

![](file://C:/Users/Corl/.config/joplin-desktop/resources/97cc5cbe7bd34e0a87cc4ed18c18f4ba.jpeg?lastModify=1578363932)Now, you may notice the note about ‘Why? \(Motivation\)’- I do also recommend testing whether the customer prefers your solution\(s\) to a problem scenario over their current alternatives. However, I don’t want to stray too far from the topic at hand. If you’re interested in the overall process, check out the [Venture Design](http://www.alexandercowan.com/calendar/business-plan-2-0-practice-venture-design/) page.

For related tutorials, templates, and online courses, see the end of the section above on Personas.

### &lt;a id="Designing\_Better\_User\_Stories"&gt;&lt;/a&gt;Designing Better User Stories

#### What’s the right level of detail?

Once you’ve learned about your user enough to know you really should build software, it’s time to work through some stories. What you want to do to make their lives better? How will you know if you did that?

Your user stories should be detailed and they should be testable. Why? Well, because what you’re really deciding is how much of the software/systems you’re going to invest in building will be supported by carefully considered ideas about what’s valuable to the user. Based on the stat’s I cited at the intro. \(that something on the order of half of all software ends up in a fail\), I’d say odds are many teams have room for improvement. That’s easy to say, but hard to do. I know I’m always working to do better. Let’s take a look at a few specific examples.

If you’ve never written a story before, you’ll probably start with something overly broad. For Enable Quiz, it might be something like: **‘I want to properly screen engineering candidates so my company can get the best possible hiring outcomes.’** You could use this as a starting point for your next stories, but it’s not immediately actionable for design or coding. Also, if you’re only going to work with one additional layer of abstraction in your stories \(child stories under an epic\), I think you’re going to end up with stories that are too vague and a working environment that’s not well backstopped by narrative. The story above is really analogous to the problem scenario we talked about in the last section: ‘Screening Technical Talent’. For stories, I’d start with more actionable specifics \(and tie them to problem scenarios if you want to make sure they’re well supported by customer discovery\).

Here’s a more specific story: **‘I want to easily screen an engineering candidate, so I know their skills profile.’** This story has some issues. Let’s tighten it up! First, it’s missing the first clause identifying the persona. That’s an issue since there are at least two distinct personas involved: Helen \(or Hank\) the HR Manager and Frank \(or Francine\) the Functional Manager. We need to know who we’re designing for and whether we should screen for subjects that match Helen or Frank when we’re testing usability. \(We may get very different results testing with Helen/Hank that has a background in HR vs. Frank/Francine that has a background in software\). Here’s an updated version of the story: **‘As Helen the HR Manager, I want to easily screen an engineering candidate, so I know their skills profile.’**

Do you see any issues with that story now? I always tell students to avoid normative terms like ‘easily’. I mean, what does that mean to a designer? A developer? Did you think they were going to design it to make things hard? If you think particular moments in the customer journey are important in some particular way, capture that in a storyboard and/or get that up on a [story map](http://www.alexandercowan.com/storyboarding-tutorial/) \(see section ‘Developing with Stories’\), and really describe what’s important and why and how you’ll observe whether you’re succeeding. \(I know, designing thoughtfully is a lot of work!!\) Let’s remove ‘easily’ from the story: **‘As Helen the HR Manager, I want to screen an engineering candidate, so I know their skills profile.’**

How about now? Is that about the right scope for an epic? I don’t know about you, but I have mixed results thinking that through in my head. I have to work through it on paper. One thing I find is really helpful for exploring an epic \(particularly at the beginning of a new project\) is to [storyboard](http://www.alexandercowan.com/storyboarding-tutorial/#Storyboard_an_Epic_User_Story_Agile) it. Here’s one view of what the major steps to the above epic might be: [![](file://C:/Users/Corl/.config/joplin-desktop/resources/82c69e5963634ae38a2aadfacba30ea0.png?lastModify=1578363932)](http://www.storyboardthat.com/userboards/alexcowan/agile-epic--enable-quiz) Looking at this, I see a lot of stuff- creating the quiz, paying for Enable Quiz \(if it’s the first time or requires a subscription change\), consulting with a colleague \(Frank\), administering the quiz, and making the results available to Frank. I’d say just about each of those feels like an epic. What I think I’d do is start with an epic about just creating the quiz: **‘As Helen the HR Manager, I want to create a screening quiz so , so I know their skills profile.’**

I’d say this is getting close, but that last clause about the reward, ‘so I know their skills profile’ still needs some work. That clause is so important, I think it deserves its own subsection! That’s up next.

Storyboarding is an excellent tool pushing yourself and your team to think substantially about your customers, what they want from you, and what they’re really doing in real life. Especially if you’re developing something relatively new, I highly recommend storyboarding your epic agile user stories.

The process of storyboarding will help you:

1. test the depth and scope of your understanding about the persona\(s\) and problem scenario\(s\)
2. stimulate interest and discussion in the story with your implementation team \(and peers on the product side\)
3. push you to think through the details so you’ve implementors don’t have to start from scratch there

This last one is particularly important if you’re new to product development. I coach lots of first-time entrepreneurs, and their \#1 challenge at the product implementation phase is thinking through what they want in enough detail. Most of their stories are actually epic stories \(or broader\) and need more granularity and sequence- storyboards help. A classic failure mode is leaving your development team to design your product. This not to say your developers can’t think creatively or answer these questions, and part of the point of these inputs is to stimulate creative discussions with them so the team’s collective imagination and expertise is maximized, but your job as the product person is to provide a well-articulated, thoroughly considered starting point.

For more on the process of storyboarding \(including tools and templates\), please see: [Storyboarding Tutorial](http://www.alexandercowan.com/storyboarding-tutorial/).

#### What’s their reward?

The last clause of your user story should always contain a testable reward. Reward sounds exciting but all we’re talking about is: a\) does it describe the successful accomplishment of whatever goal first triggered the story and b\) can observe in a user test?

Does the current 3rd clause \(‘so I know their skills profile’\) meet those criteria? I think we could test it- put a prototype in front of an subject, step them through creating a quiz, then administering it and seeing the results and ask them to tell us the skills profile. But is that reward even relevant anymore? It doesn’t really make sense with the intent. What does Helen really want at this point? There are a few possibilities. Fundamentally, she wants to figure out, with the functional manager, who they should interview and who they should hire for the best possible \(mutual fit\). I’d say ‘so that I can understand whether I want to send possible recruits to the functional manager’ is a good candidate. Another more immediate possibility is ‘so that I can make sure I’m prepared to use it when I interview job candidates’. Let’s try that on for size: **‘As the HR manager, I want to create a screening quiz so that I make sure I’m prepared to use it when I interview job candidates.’**

Now how does the clause do on our tests about a\) describing their accomplishment and b\) being observable in a test? I’d say it describes the HR manager’s immediate goal- being able to use the test. Is it testable? We could take the user through the creation of a new test and then ask them how they’d administer it and see if they have the right answer. I’d say it’s testable.

### &lt;a id="Testing\_User\_Stories"&gt;&lt;/a&gt;Testing User Stories

#### What are we testing?

When it comes to testing, I think the most important thing is to a\) draw a clear distinction between usability and motivation and b\) understand the relationship between them. My favorite tool for dealing with this is BJ Fogg’s curve:

![](file://C:/Users/Corl/.config/joplin-desktop/resources/3ff97d9facdf4c41862224ad8835eb4c.jpeg?lastModify=1578363932) Basically, what this is saying is that if the customer/user is really motivated to do something \(imagine a point on the upper left\), then it can be relatively harder for them. If a user isn’t that motivated \(imagine a point on the lower right\), then the action needs be relatively easier.

If you’re building a product or feature, what this clearly implies is that you need to take a balanced view of motivation vs. usability. Most products and projects I see are very focused on usability. However, most of them haven’t tested motivation: Will the user really prefer this product or feature over their current alternatives?

Instead, they often confuse it/mingle it with their usability testing, for example asking about a prototype ‘Do you like this? Will you \[use it, buy it\]?’. That doesn’t work- the subject will always give you a ‘yes’. For more on why see specifically this post on the ‘[yellow Walkman problem](http://www.alexandercowan.com/yellow-walkman-data-art-of-customer-discovery/)‘ or more generally the here tutorial on [Lean Startup](http://www.alexandercowan.com/creating-a-lean-startup-style-assumption-set/). Suffice to say here that the kind of testing we do relative to user stories deals with usability- that’s why they call it ‘usability testing’.

What they means is that we’re assuming they’re motivated \(controlling for motivation, if you will\) and just testing for usability. What this means is that if we’re testing a piece of software that allows users to paint virtual walls \(bear with me\), then we don’t ask them ‘Do you want to paint this wall?’. We don’t even ask them ‘What color would you like to paint this wall?’. We ask them ‘Would you show me how you’d paint this wall yellow?’ and then we’re seeing how hard it is for them to do that and thinking about how we can make it easier.

#### How do we test stories?

Have you ever heard something like this: ‘We don’t do as much user testing as we probably should because by the time we can test the software we’re already up against our deadline.’ As sympathetic as I am to those deadlines, I just don’t think this is a good reason not to be testing usability.

A generally accepted \(though not universal\) view of user testing is that it’s best to think of it having phases like you see below:

![](file://C:/Users/Corl/.config/joplin-desktop/resources/3ee87a2e6eeb40c388a971413b22d4b5.jpeg?lastModify=1578363932)When you’re doing early testing, rough [prototypes](http://www.alexandercowan.com/build-your-first-prototype-in-30-minutes/) \(physical or virtual\) will work fine- you don’t need an engineer or \(with the right process\) even a formally trained designer to test the efficacy of different approaches. My advice is to maximize these opportunities early on in your story formulation. On a related note, I highly, highly \(2 highly’s\) recommend anchoring your test items in user stories as opposed to interface-specific goals like ‘see if the user understands our drop down menu’s’.

For a quick overview of how to do this, I recommend the [Usability Testing section](http://www.alexandercowan.com/customer-discovery-handbook/#Usability_Hypothesis) of the Customer Discovery Handbook.

For a more in depth view, I recommend [Running Design Sprints](https://www.coursera.org/learn/running-design-sprints/?utm_medium=institutions&utm_source=UVA-DARDEN&utm_campaign=ACC-Feature) \(course 2 in my agile specialization on Coursera\) and [Testing with Agile](https://www.coursera.org/learn/agile-development/?utm_medium=institutions&utm_source=UVA-DARDEN&utm_campaign=ACC-Feature) \(course 4 of the same\).

#### When is a story done?

I think you’ll find this is a valuable question to answer with your team. I’d also bracket it with the other end of the larger question, which is ‘When does a story begin?’

![agile-learning-loop](file://C:/Users/Corl/.config/joplin-desktop/resources/5bb70dfd9cad437a955de734e69d6fec.png?lastModify=1578363932)The prevailing thinking around modern software development is that you should treat your product, in fact, every feature within your product, as an ongoing experiment.

While it drew heavily on agile, it’s really the body of work around Lean Startup that’s popularized this. Their central heuristic is ‘build-measure-learn’. I prefer the terms you see in the blue loop here but fundamentally they amount to the same thing.

The beginning of any good answer to the question above begins with the acknowledgement that you just can’t predict \(with any consistency\) what’s going to be valuable for the user. Therefore, you need to work with testable ideas and closed-loop experiments to see if you’re right or not.

Ideally your stories begin with some kind of observation about your user and the problems \(jobs, desires\) they have. Then you come up with a testable formulation of how you’ll know if your solution idea is really better than what they have now. A very tactical examples from Lean UX is that you might put in a placeholder menu item or button for your new feature and just see if users click on it \(at which point they get a ‘coming soon message’\). Once you’ve validated that some motivation exists for your feature, you move on to actual user stories, testing usability as you go along. Then, once you release said feature into the wild, you have some metrics on usability and motivation that tell you whether, in fact, you really are right \(and to what extent\). Ideally, this feature you’ve implemented is the simplest possibly version \(minimum viable product\) that will allow you to learn whether you’re right or not. Basically, you want to achieve something like this:

![Agile-Development-Process-Lean-Startup](file://C:/Users/Corl/.config/joplin-desktop/resources/02aed13a12ed4126bd364023ce1d4f2a.png?lastModify=1578363932)

Yup, it’s a lot of stuff. My particular approach to making it manageable and actionable is [Venture Design](http://www.alexandercowan.com/venture-design/), which is described in the diagram below. If you really want to dig in and make sure you’re iterating to something valuable with a minimum of waste, I highly recommend taking a look. That said, let’s move on to developing with stories!

![](file://C:/Users/Corl/.config/joplin-desktop/resources/7fde7b524a7c4967b3c5c4128771c490.png?lastModify=1578363932)

### &lt;a id="Developing\_with\_Stories\_Story\_Maps"&gt;&lt;/a&gt;Developing with Stories & Story Maps

#### Who writes user stories?

Odds are good that if you’re doing agile you’re using scrum or a scrum-informed take on agile. If you have someone in the ‘product owner’ \(PO\) role scrum prescribes, you’ve probably heard that it’s their job to write the user stories. That is a reasonable starting point. That said, the best way of looking at it is probably that the PO is the lead on writing the user stories vs. solely responsbile.

WAIT! This is really important- it’s not just touchy feely stuff. It might even matter more than the prescribed mechanics of scrum. Here are the specific reasons why: **1. The 1/40 Problem** Based on experimental results, it’s possible \(I would guess likely\) that people are only actually understanding 1/40 of what we think we’ve told them. A PhD candidate at Stanford did an experiment where one person \(a ‘tapper’\) would tap out a song and another party \(‘listener’\). The tappers guessed that they’d been understood 50% of the time where actually the listeners had actually understood only 2.5% of the time- off by 20x. Yikes!

What if that’s true of the stories we’re writing and the understanding we assume a designer and/or developer will have about how to build software against that story? Is that somewhat consistent with the kind of disconnects you see between ‘businesspeople’ and ‘technical people’?

If you’re slamming your user stories into JIRA and assuming they’ll be understood, you’re probably going to run into issues. By the way, I first read about this in the Heath brothers’ excellent book ‘Made to Stick’.

**2. We Measure our Efficiency Locally** A certain part of us just wants to know in the simplest possible terms what our job is and how much of it we have to do. We crave certainty and an immediate sense of accomplishment. If someone tells me my job is to dig six holes, part of me just wants to do it and be done. It’s fine- it’s just human nature.

Unfortunately, you can’t build software that’s valuable to users this way \(at least not with any consistency\). If you don’t co-create stories with your team, they’re just not going to feel like they own them and their work won’t be as thoughtful. Since the stories are probably your job I’ll apologize in advance for saying so, but don’t blame the implementation team- you’d act the same way in their position. Again, it’s just human nature.

In the classroom, I often reference the ‘blue button moment’. In a low-functioning agile team where the implementors don’t understand and/or haven’t bought into the idea, it looks like this: ![](file://C:/Users/Corl/.config/joplin-desktop/resources/cc0630fb63ad4df8890a64681ce90444.png?lastModify=1578363932)In a high-functioning agile team, it looks like this: ![](file://C:/Users/Corl/.config/joplin-desktop/resources/23f91db22b1349e8b8d2ea8cd6684318.png?lastModify=1578363932)If you’re the lead on creating stories, part of your job is to solve for the two problems above and help elevate your team to a high functioning practice of agile.

As if that wasn’t enough there’s one more reason why you should write stories as a team-

**3. You Don’t Have All the Best Ideas** Naturally, others will have great ideas about what the user might want and how to implement that in software. Beyond just doing your story writing with the extended team, this is the reason why the whole team is generally included in the increasingly popular practice of running [design sprints](http://www.alexandercowan.com/venture-design-sprints/).

One specific method of encouraging good outcomes around stories is having the PO/story lead run story writing workshops, which we’ll cover in the next section.

#### How do you use stories within a team?

User stories are your anchor for working together on what you’re going to build and how you’ll know if it’s working. In a perfect world, the whole team is conducting [design sprints](http://www.alexandercowan.com/venture-design-sprints/) together to learn about that and cultivate a shared understanding. Regardless, to arrive at a strong shared understanding it’s critical to formulate the stories together and make them highly visible to the team. On popular tool for this is the story map, popularized by Jeff Patton:

![](file://C:/Users/Corl/.config/joplin-desktop/resources/ed4d2683e7744ba0a5575c7b83b0194c.jpeg?lastModify=1578363932)

The story map does a few jobs for you: 1\) helps you think through the right stories 2\) helps you prioritize them and 3\) serves as an ‘information radiator’ to keep the stories visible as you work on them over the course of weeks or months.  If you’re in charge of managing your team’s story writing workshops, I think you’ll find it’s a very valuable tool.

Let’s talk about how to make one. The first stripe \(0\) defines the x-axis of the story map and represents the customer/user journey. It’s best built with [storyboard](http://www.alexandercowan.com/storyboarding-tutorial/) squares. The reason why the seemingly silly details in the storyboard squares matter is that every single thing you can do to help keep your focus ‘outside the building’ and on the life of the user is going to help you drive to better outcomes more efficiently. Fine point: If you’re storyboard your epics \(great idea!\), then what you’d probably want to do on ‘stripe 1’ is to pick and choose among those to create a kind of summary. The reason this is a good idea is that a well articulated epic will usually have many more storyboard squares than you’ll want with the size and density of a typical story map.

Let’s talk about stripe 1+ and the y-axis. The y-axis describes relative priority, so stripe 1 is higher priority than stripe 2 and so forth. If you have a bunch of stories about how a user would search for a product, you’d put what you assume is the most common/important story in stripe 1, and then less common types of search stories in the same vertical space within stripes 2, etc. Careful prioritization on this axis relative to the x-axis/user journey is a subtle but important part of any high-functioning agile program.

The best explanation I’ve heard comes from agile thought leader Bill Wake: Let’s say you’re building a site where the basic  user journey is a\) search b\) select c\) purchase. It’s natural \(but a terrible idea\) to build out all the search functions and then move on to select, etc. The reason it’s a terrible idea is that you won’t be able to do any meaningful user testing or market/release testing. The user can’t do anything potentially valuable by just searching for stuff. In a high-functioning agile team, you’re iterating through the thinnest possible slices of your story map, testing, assessing, and then building more software.

#### How do you use stories day to day?

In a high-functioning agile environment, when anyone is unsure of an implementation detail, they have a discussion around user stories- see the blue button moment above. I’ve shown you how to put yourself in a position to write strong stories that are anchored in the life of the user and highly testable. You’ve also seen how to organize and prioritize stories with a story map.

It takes practice to consistently write good user stories and apply them effectively to help your team work better. For overall breadth on how to think about this, my favorite heuristic on user stories is Bill Wake’s INVEST acronym. Bill Wake introduced the INVEST mnemonic in his seminal post on creating better stories, suggesting they should be Independent, Negotiable, Valuable, Estimable, Small, and Testable. The INVEST checklist is a guideline, not a commandment, as Bill Wake makes clear in [his post](http://xp123.com/articles/invest-in-good-stories-and-smart-tasks/). When in doubt, always do what _you_ think makes sense. All that said, here’s an overview of INVEST:

**Independent**

![Spotify-Agile-How-Build-300px](file://C:/Users/Corl/.config/joplin-desktop/resources/43abececab5f44d28a958b76c8dc9c8f.jpg?lastModify=1578363932)Ideally, you should be able to implement your stories in any order while still realizing the benefit of seeing something working at the end. This is important for two reasons. First, you lose a lot of the adaptability agile’s supposed to deliver if your stories have \(many\) interdependencies. Second, independence makes it much more likely that you can sequence what you do such that it’s meaningful to users and testable with them by the end of an iteration.

Spotify is known for its success with agile and other adaptive techniques. This slide from one of their talks summarizes the value of Independent \(and Valuable and Testable\).

**Negotiable**

![Agile-User-Stories-Negotiable](file://C:/Users/Corl/.config/joplin-desktop/resources/5622c14c54d148d5899622722436b58d.jpg?lastModify=1578363932)User stories are not requirements. It’s a combination of stories and regular discussions that are meant to replace requirements. You should revise stories freely as you and your collaborators come up with better ideas.

**Valuable**

![Valuable-Agile-User-Story](file://C:/Users/Corl/.config/joplin-desktop/resources/a899a928982443749242b4667131e158.jpg?lastModify=1578363932)Each story once implemented should be both functional and relevant to the customer/user.  We’ve talked a lot in this post about how to achieve that.

A quote from Bill Wake’s original post on why this is important in software development projects: _Developers often have an inclination to work on only one layer at a time \(and get it “right”\); but a full database layer \(for example\) has little value to the customer if there’s no presentation layer_.

**Estimable**

![User-Stories-Estimable-300px](file://C:/Users/Corl/.config/joplin-desktop/resources/9fc87eb4ca54431286277d6a5c334b46.jpg?lastModify=1578363932)It should be possible for a developer with relevant experience to roughly estimate a story. That estimate’s then used by the product person to prioritize their list of stories, taking account of both value and cost \(in terms of developer time\).

Estimating’s kind of controversial in the agile community and not without good reason: It can lead unnecessary overhead and pointless recriminations when the final output doesn’t ‘agree’ with the original estimates. These are all things agile strongly tries to help avoid.

If I were to offer three silver bullets on this, they would be: 1\) Write good stories based on validated insights about the user. 2\) Make sure everyone understands and agrees that the estimates are very approximate \(like Small-Medium-Large\) and for purposes of prioritization. 3\) If you want to do post-mortems on estimates vs. actuals, make sure there’s general agreement that it’s to help the team in some actionable way and not just because someone’s frustrated there isn’t more implementation done.

**Small**

![Valuable-Agile-User-Stories](file://C:/Users/Corl/.config/joplin-desktop/resources/f5cb88a0ef1b474a8fede2183a4be04c.jpg?lastModify=1578363932)Your unimplemented stories are like a box of chocolates…ah, scratch that, reader; never mind.

Basically, your stories need to be Small for you to get the adaptability and reduction in overhead that agile offers. Big stories reduce opportunities for incremental testing and require more elaborate planning.

**Testable**

![Testable-Agile-User-Stories-300px](file://C:/Users/Corl/.config/joplin-desktop/resources/d9d93c3216b5473993e0a72726ba010b.jpg?lastModify=1578363932)As the author of a story, you should be able to write tests that would allow you to validate that an implementation delivers on your intent. Many teams operate this way, but regardless of what everyone else does, you’ll do yourself a big favor by writing some functional test cases in advance- you’ll be much more likely to get what you want more easily.

### &lt;a id="Example\_A\_Example\_User\_Stories\_from\_Enable\_Quiz\_Startup"&gt;&lt;/a&gt;Example A: Example User Stories from Enable Quiz \(Startup\)

#### Example Epic I

This epic story deals with the example company Enable Quiz and the HR manager wanting to create a quiz to screen engineering candidates. is organized in a more conventional fashion \(vs. the epic above that’s storyboarded\).

**Epic Story:** “As the HR manager, I want to create a screening quiz so that I make sure I’m prepared to use it when I interview job candidates.”

[![](file://C:/Users/Corl/.config/joplin-desktop/resources/82c69e5963634ae38a2aadfacba30ea0.png?lastModify=1578363932)](http://www.storyboardthat.com/userboards/alexcowan/agile-epic--enable-quiz)

|  |  |
| :--- | :--- |
| **USER STORY** | **TEST CASES** |
| As a manager, I want to browse my existing quizzes so I can recall what I have in place and figure out if I can just reuse or update an existing quiz for the position I need now. | Make sure it’s possible to search by quiz name Make sure it’s possible to search by quiz topics included. Make sure it’s possible to search by creation and last used date. |
| As an HR manager, I want to match an open position’s required skills with quiz topics so I can create a quiz relevant for candidate screening. | Make sure the quiz topics are searchable by name. Make sure the quiz topics have alternate names, terms for searching |
| As an HR manager, I want to send a draft quiz to the the functional manager so I make sure I’ve covered the right topics on the screening quiz. | Make sure it’s possible to add another user by email in this flow Make sure it’s possible to include notes and customize the email Make sure it’s possibly to just copy a link \(for case where HR manager wants to send their own email\) |
| As a functional manager, I want to send feedback on the screening quiz to the HR manager so I make sure I’m getting the best possible screening on candidates. | Make sure it’s possibly to supply comments in-app. Make sure the above are quiz-specific by default but can also be general. Make sure it’s also easy to copy the name or URL of the quiz for their own correspondence. |
| As an HR manager, I need to purchase an upgraded service tier so I can add additional topics to my quiz. | Make sure that users with billing privileges can upgrade the service. Make sure that If the users don’t have billing privileges, they see a list of those that do and can contact them. Make sure the charges are correctly prorated against the billing anniversary of the account. |
| As an HR manager, I want to add custom questions to the quiz so we cover additional topics that are important to the functional manager. | Make sure the customer is not charged for this bank. Make sure the custom bank is owned by the client organization and not accessibly by any other accounts on the system. |
| ’As the HR manager, I want to try out the screening quiz so that I can make sure it works as I expected and that I’m ready to both give it to candidates and share the results with the functional manager.’ | Make sure there is a clear indication that the user can \(and should\) test the quiz Make sure there’s a ‘view as test taker’ mode available to the admin. |

Here are a few other epics that might follow this one.

#### Example Epic II

‘As the HR manager, I want to give the screening quiz to a job candidate so I can assess their skill sets against the needs of the position.’

#### Example Epic III

‘As the HR manager, I want to share and explain the results of our screening with the functional manager so they can decide who they want to interview.’

READY TO WRITE USER STORIES LIKE A DESIGNER?

RECOMMENDED: [Course 1: Getting Started: Agile Meets Design Thinking](https://www.coursera.org/learn/getting-started-agile/?utm_medium=institutions&utm_source=UVA-DARDEN&utm_campaign=ACC-Feature) [START CREATING STORIES](https://www.coursera.org/learn/getting-started-agile/?utm_medium=institutions&utm_source=UVA-DARDEN&utm_campaign=ACC-Feature)

### &lt;a id="Example\_B\_Example\_User\_Stories\_from\_HVAC\_in\_a\_HurrynbspIT\_Project"&gt;&lt;/a&gt;Example B: Example User Stories from HVAC in a Hurry \(IT Project\)

#### Example Epic I

‘As Ted the HVAC technician, I want to know the pricing and availability of a part that needs replacing so I can decide my next steps.’

![](file://C:/Users/Corl/.config/joplin-desktop/resources/5eb58c11cbce408ba5b9a3d8f8056cef.png?lastModify=1578363932)

|  |  |
| :--- | :--- |
| **USER STORY** | **TEST CASES** |
| I know the part number and I want to find it on the system so I can find out its price and availability. | Make sure it’s possible to search by part number. Make sure descriptive info. appears as the search narrows \(photo?\) to help avoid error. |
| I don’t know the part number and I want to try to identify it online so I can find out its price and availability. | Make sure it’s possible to search by make/model of units Make sure it’s possible to search by type |
| I don’t know the part number and I can’t determine it and I want help so I can find out its price and availability. | Make sure an estimate of the turnaround time for an expert to review is available |
| I want to see the pricing and availability of the part so I decide on next steps and get agreement from the customer | Make sure it’s possible to dispatch a request by email to the customer in case they order their own parts and/or carry their own inventory of spares. NOTE: How would the customer respond so we can help structure the next steps as we would otherwise? |

### &lt;a id="Citations\_and\_Image\_Credits"&gt;&lt;/a&gt;Citations and Image Credits

Pair Programmers: By Lisamarie Babik \(Ted & Ian Uploaded by Edward\) \[CC-BY-2.0 \([http://creativecommons.org/licenses/by/2.0](http://creativecommons.org/licenses/by/2.0)\)\], via Wikimedia Commons Chemist: By Linda Bartlett \(Photographer\) \[Public domain or Public domain\], via Wikimedia Commons Present: By Kgbo \(Own work\) \[CC-BY-SA-3.0 \([http://creativecommons.org/licenses/by-sa/3.0](http://creativecommons.org/licenses/by-sa/3.0)\)\], via Wikimedia Commons Chocolates: By Dwight Burdette \(Own work\) \[CC-BY-3.0 \([http://creativecommons.org/licenses/by/3.0](http://creativecommons.org/licenses/by/3.0)\)\], via Wikimedia Commons Meter: By Iainf 05:15, 12 August 2006 \(UTC\) \(Own work\) \[GFDL \([http://www.gnu.org/copyleft/fdl.html](http://www.gnu.org/copyleft/fdl.html)\), CC-BY-SA-3.0 \([http://creativecommons.org/licenses/by-sa/3.0/](http://creativecommons.org/licenses/by-sa/3.0/)\) or CC-BY-2.5 \([http://creativecommons.org/licenses/by/2.5](http://creativecommons.org/licenses/by/2.5)\)\], via Wikimedia Commons

* [Click to share on Facebook \(Opens in new window\)](https://www.alexandercowan.com/best-agile-user-story/?share=facebook&nb=1)
* [Click to share on Twitter \(Opens in new window\)](https://www.alexandercowan.com/best-agile-user-story/?share=twitter&nb=1)
* [Click to share on LinkedIn \(Opens in new window\)](https://www.alexandercowan.com/best-agile-user-story/?share=linkedin&nb=1)

Filed Under: [Product Development](https://www.alexandercowan.com/category/product-development/)

### Primary Sidebar

THE VENTURE DESIGN PROCESS You are here.

[![](file://C:/Users/Corl/.config/joplin-desktop/resources/fdf463220e7a4e62bf90afa9067af270.svg?lastModify=1578363932)](https://141nh047iozd1l75s22eer06-wpengine.netdna-ssl.com/wp-content/uploads/2016/09/5_ProcessDiagramForward.svg)

[OVERVIEW](https://www.alexandercowan.com/venture-design/)

![](file://C:/Users/Corl/.config/joplin-desktop/resources/c148aec9cef344b8963cff0078b22245.svg?lastModify=1578363932)

GO DEEPER:

Want to make innovation an everyday thing? RECOMMENDED: Agile Development Specialization on Coursera [CHECK IT OUT](https://www.coursera.org/specializations/agile-development/?utm_medium=institutions&utm_source=UVA-DARDEN&utm_campaign=ACC-Feature)

* [Home](https://www.alexandercowan.com/)
* [Venture Design](https://www.alexandercowan.com/venture-design/)
* [Learn/Teach](https://www.alexandercowan.com/learn-teach/)
* [The Interdisciplinarian](https://www.alexandercowan.com/blog/)
* [Workshops](https://www.alexandercowan.com/lets-work/)
* [About Me](https://www.alexandercowan.com/about/)

### Footer

LET’S STAY IN TOUCH

JOIN ME ON:

[![](file://C:/Users/Corl/.config/joplin-desktop/resources/98e72145319245f2aadab61531c13580.svg?lastModify=1578363932)](https://twitter.com/cowanSF)[![](file://C:/Users/Corl/.config/joplin-desktop/resources/db0f5a8b1c5c4f1a807dbb33a862a9b7.svg?lastModify=1578363932)](https://www.facebook.com/StartingATechBusiness)[![](file://C:/Users/Corl/.config/joplin-desktop/resources/7b4821f3251c41819453a5e3691a8805.svg?lastModify=1578363932)](https://www.linkedin.com/in/alexcowan)[![](file://C:/Users/Corl/.config/joplin-desktop/resources/aed54a6bbdcd4b099293560d44d32f94.svg?lastModify=1578363932)](https://plus.google.com/117579985647346229026)

Copyright © 2016 Alex Cowan · All rights reserved.

Back to Top

