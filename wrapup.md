# wrap-up: takeaways from code4lib 2014

I enjoyed the hell out of [Code4Lib 2014](http://code4lib.org/conference/2014/schedule) in Raleigh, NC back in March. Code4Lib is a group of library/ish web/software developers/aficionados. We are loosely organized around a [listserv](https://listserv.nd.edu/cgi-bin/wa?A0=CODE4LIB), an [annual conference](http://code4lib.org/conference) and regional sub-conferences, and an [open-access journal](http://journal.code4lib.org/).

I went to the conference last year, too, and [wrote that up](http://erinrwhite.com/fou-things-that-inspired-me-at-code4lib-2013/). 

This year I [took a lot of notes for the sessions](https://github.com/erinrwhite/c4l2014-notes), but I wanted to loop back a few weeks after the fact and talk big takeaways. 

## Community and diversity

This was my fourth Code4Lib conference. By this point, this group is like family for me - it's always great to catch up with people in person after only seeing them on Twitter throughout the rest of the year. There were lots of new faces this year, too, including (from what I could tell) a whole lot more women than in previous years. 

And, this year's conference also felt more diverse in job descriptions. More and more librarians are dealing intimately with software development, data, and day-to-day scripting, which means Code4Lib is not just "programmers" anymore. Job titles of some folks I met: scholarly communications librarian, cataloger, project manager, metadata specialist, digital archivist.

I continue to be grateful for the community's ongoing commitment to creating an inclusive culture. Our keynote speakers [Sumana Harihareswara](http://www.harihareswara.net/) and [Valerie Aurora](http://valerieaurora.org) didn't talk specifically about code, but about code culture and how we can make it better for everybody.

## UX is a social justice problem

[Sumana Harihareswara's keynote](http://wiki.code4lib.org/index.php/2014_Keynote_by_Sumana_Harihareswara) was an excellent start to the conference. Her thesis: usability impacts use. It's why we go to docs-in-a-box instead of seeing a general practitioner, for example, and why scholars are going to academia.edu instead of navigating our byzantine library systems. But at what long-term cost?

How do we make the right things, and make them usable? Empathy. It's a "feminine" trait, while IT is traditionally masculine, and thus the idea has been slow to catch on in the tech industry. But, "we need to be able to see from many different users' points of view, even when it's uncomfortable or shows us that we have failed." 

## Discomfort = growth

This was a nice tying thread between [2013's Fail4Lib preconference](http://lanyrd.com/2013/c4l13/scbpdt/) and this year's keynotes. We learn by failing, and that includes not just bugs in code, but our own personal shortcomings. [Valerie Aurora's](https://github.com/erinrwhite/c4l2014-notes/blob/master/day3-keynote.md) quote was, "Notice when you feel discomfort or guilt. It's a sign you are learning something."

## The web in 2014 and beyond

Beyond all this talk about community, growth, etc. - Code4Lib is also a deeply nerdy technology conference. Seeing the presentations and talking with folks at different libraries helped me understand the landscape of web technologies and where we're headed.

### Yep, Javascript.

A lot has changed since I started building websites in 1998, so I never thought I'd say in 2014 that Javascript is the future of the internet. Look around, though, and any web site or application that has an interactive component (anything in the Google Apps suite, Facebook, Wordpress...) is leveraging Javascript libraries to create a smoother, faster user experience. 

It took a while, but we finally have a robust suite of frameworks and testing tools for Javascript that have transformed it from the DHTML nightmare that it used to be to the powerful cross-browser scripting language it is today. 

And, if we're going to continue to think mobile-first with web development, we need to be looking at a universal browser language that can deal with complex interaction patterns like gestures; play nice with the new features of HTML5; and work well with real-time communication protocols like WebRTC. So, Javascript.

Related presentations:

- [Javascript MVC frameworks](http://go.ncsu.edu/js-mvc)
- [Automated testing for Javascript interfaces](https://github.com/mredar/code4lib-2014-PhantomJS-Selenium)
- [Web sockets for real-time communication](http://go.ncsu.edu/websocket)

### Making connections: linked data, schema.org, SEO

A couple years ago I could not have defined "linked data" for you, and I'll still probably not do it justice here, but the basic idea is: there are some types of things (i.e. people, events, citations) that could be output using the same formatting on the web. This standard format makes it easier for machines to understand the information and thus for humans to find and use it.

A few libraries talked about their work incorporating code markup from [schema.org](http://schema.org) in their catalogs and on their web pages to make information more easily searchable. It seems like a small thing that could make big impact especially as we see more and more traffic from search engines.

Related presentations:

- [Structured data NOW: seeding schema.org in library systems](http://lanyrd.com/2014/c4l14/scxyrq/)
- [Schema.org for digital collections at Duke](https://blogs.library.duke.edu/bitstreams/2014/03/27/schema-org-and-google-for-local-discovery-some-key-takeaways/)

## VCU Libraries' web team is unusual

VCU Libraries sent two of us to Code4Lib this year, which was great - both our developer Shariq and I had fun and learned a lot, including that VCU Libraries is unique in the size and structure of the web team. Many organizations at Code4Lib were either represented by one person or by 12. We're a three-person shop, and as Shariq has noted, we are not building enterprise systems from scratch. We do, however, work closely with the Enterprise Systems team to modify interfaces for systems like Primo and ContentDM. And we are responsible for high-use web systems like the study room reservation system and “invisible” but essential systems that connect users to resources or display today’s hours on the website.

So, looking forward, we should continue to be thoughtful but bold about the types and scope of projects that the team takes on. I see us focusing on improving user experience for existing systems and keeping an eye out for innovative but sustainable projects that can support scholarship at VCU, while finding more ways to use existing systems at VCU and beyond where we can.