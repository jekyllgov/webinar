# Webinar notes
## Intro Ideas
### Define the problem
* Regardless of what CMS you use, the act of choosing one is a heavy burden.
	1. Designers are frustrated by the spaghetti code that many WSIWYG editors provide, and how they allow less experienced users to break their designs.
	2. IT departments rarely hire dedicated web staff to continue integrations with the content management system, which means that — at best — new features fall to the bottom of the list as general purpose programmers focus on business systems, but didn’t provide developer support. This creates unnecessary tension between design and development.
	3. Systems that don’t give great flexibility to designers (or ones that require handoff to more technical staff) tend to get outdated quickly, and much of the information is presented in ways that don’t work well on web.
	4. Many cities don’t even have a designer on staff, instead opting to let people write long articles rather than creating a strong web experience.
	5. Resources are in the wrong place.
## Sound Familiar?
If not, congratulations on being a healthy, non-dysfunctional organization

* The more people who have to interact with your content management system, the more negative opinions you’ll see.

**[Catherine Takes Over]**

## What’s in the box?
1. What are we really buying with a CMS?
	1. User management — Every system you use has one already. That’s why IT departments try to integrate with Active Directory, but not all systems let you bring your own login system.
	2. Editor software — Every piece of information your city maintains already has a piece of software to manage it that works better than a web editor … even if it is just Microsoft Excel. For the content that is strictly web, many editors are the similar, but there is significant variance in quality.
	3. A database of content/version control to keep track of how content changes, stage new content etc. This, again, is highly variable from system to system. How do you really need to stage your content? Individual sections? Whole pages? Do changes need to be scheduled?
	4. A way to pull content into a template … there are thousands of template languages out there, and if you’ve been keeping up with some of the newer changes, Javascript itself is now a template language.
	5. And of course. Form tools. Basic forms that someone has to handle via email. Some systems are more robust, but anything more than an email form usually requires some pretty heavy developer intervention.
2. If we stop looking for the silver bullet, we see a much richer landscape. There are systems dedicated solely to copy workflow … and they have APIs to integrate into any system. There are private form builder services that make better quality forms than any all-in-one CMS. Version control and even secure portals for editing content are available widely through Github, Bitbucket and others. You can even tie many of these services together with project management tools.
3. If no platform can meet the needs of every party involved in a website, then why shouldn’t the platform change to focus on connecting everyone’s systems instead of forcing people to use a system.

[Greg Takes Over]


## The Flaw
* Thinking a CMS will solve your problems is why they tend to be sold with redesigns. If the content looks different and the interface looks different, it must be better. It’s a one-time expense and then everything is supposed to just work, and any problems are just a question of training.
* The reality is that there are many kinds of existing data available through internal system and (in many cities) data portals and APIs provided by software, and without a lot of work from developers, no CMS will integrate with every system … and that means extensive duplicated data entry and human capital when automated processes would be more efficient.
* There is very little thought given to how each group responsible for web content stores data already and how it could be brought into a system. We start with the solution of what to buy, rather than what problems are we trying to solve. It’s an approach that hurts everyone


*  [fill in with thoughts here] This isn’t just a random idea; it is the way all software today has gone.
	1. Discuss what development world looked like for corporate in the past.
	2. Explain how work now is focused on connecting APIs
	3. How has this improved/changed the developer experience?
	4. How static site generators, REST APIs have improved security

[Brian Takes Over]

## You Need a Content Management Strategy
Here are a few hard truths you won’t hear when people are selling you a new website or CMS. You don’t have to change your CMS to change your website, and vise versa. The very best software can be a giant headache if it doesn’t fit the workflow you’ve created.  And when you pack a bunch of tools together into a single suite, they may work together better, but some pieces are not going to work for you. The real question is are you going to change your processes to fit your system, or should we be looking for a way to put together software that works for our organizations?

## Demo
So to get an idea of what mean, we’re going to go behind the scenes of this presentation. You may have noticed we are using a website instead of a traditional presentation. Well the backend of this presentation is actually part of the presentation. So I am going to hand it off to Catherine to make an update.

[Catherine loads demo page in CloudCannon]

So we have a  non-technical user who needs to tweak this presentation in this scenario, so we’ve decided that CloudCannon is the best tool for that person to edit it.
[ Add sentence below the CloudCannon Scenario ]

But now we are going to hand off this page to a designer, who also needs to make a change, but she is more comfortable working with code.

[ Go in through github and add an image under github on the same page ]

So we’ve changed the same page with two different interfaces,  If you know the second one, Github, you know there are many MANY more collaboration options available.

## What is Jekyll

Major points:
* Static site generator, but with built-in support for structured data, common web designer/developer workflows like CSS pre-processing.
* Allows multiple views of content and other data by allowing web designers to author any kind of standard text file (like JSON and XML) using the same template engine as HTML pages
* Based on Ruby, a language that is very popular among start-ups and tech-forward companies.
* One of those tech-forward companies, Github, provides direct support of the Jekyll project, and has even built it into their site. You could host your city’s website for free on Github using a Jekyll-based site, which automatically gives you a strong editor, version control and protection against denial of service attacks through Github’s CDN.


## What was the transition like?


Short recap from Brian and Catherine of their experiences

## Quick Tips to keep in mind if you transition

* What kind of staff structure best supports the system?
* How should repositories be structured.


## Questions
