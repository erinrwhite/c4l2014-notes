# day 1 - morning

## sumana harihareswara - keynote

"Better user experience is the best force multiplier at our command."

Tech folks have a hard time thinking about usability/UX because often we align ourselves with systems/data (what we know) instead of other humans.

We spend a lot of time working on building arteries - but what about the capillaries? The ways and contexts in which users are actually touching our systems?

 - Jessamyn's response on metafilter re: Keurig
 - Payday loan companies more popular than banks because the customer service is so much better

### UX workarounds

Bad UX changes what choices people make.

Wikipedia moved the "edit" button a little more to the left and saw 8.6% more edits. "If we improve our UX, more people and more kinds of people will contribute."

The UX of booking an appointment and seeing a doctor. Minute clinic and docs in a box are workarounds but at what long-term cost to people's health?

Similarly: scholars are using academia.edu and other sites to self-serve for research and academic articles, going around libraries and potentially missing out on long-term library research help.

### exercising empathy and scaling hospitality

Thinking about people's lived experience is like unlocking the DRM of UX. Tech industry tends to value masculinity over "feminine" values like hospitality and empathy. 

We need to be able to see from others' points of view even if it makes us uncomfortable or makes us fail.

Interactions with users are our bug reports. Especially those interactions when we have to say "no" to them.

### resources 

How to build empathy: tailor to your learning style. A structured course, a novel written by someone very unlike you, observing users of your digital services.

 - Crystal Beasley article: "Code talks and designers don't speak the language"
 - Reidsma's work notes blog
 - Reidsma - the library with 1000 databases
 - usertesting.com
 - inflUX

## a book, a web browser and a tablet: how bibliotheca alexandrina's viewer framework makes it possible

[Book viewer](http://dar.bibalex.org/)

A viewer for e-books. Why not PDFs? Copyright, search issues.

Viewer allows you to copy/snip from book pages, create your own collections of pages and share. Depending on copyright you can download to your computer.

Flexible server architecture with components you can selectively enable/disable: personalization, search, metadata.

## data visualization with google data API and chart libraries

"Spreadsheets ain't databases." But sometimes we can't build web apps from scratch and spreadsheets have to do.

 - Instead of a database, use a spreadsheet.
 - Instead of SQL use Google Visualization API query language.
 - Instead of custom view you can output response from query as HTML table or as JSON.

### output with GET responses
Hacking the google spreadsheets URLs (spreadsheets.google.com):

- &tqx=out:html or JSON
- &tq= query - select statements
- &key=document id
- &gid=sheet number

### output using javascript

Similar methods using Visualization API.

Using Google charts: code demo! [Drawing dashboards with controls](http://developers.google.com/chart/gallery/controls).

### resources

- Google code playground
- Google public data explorer

## web sockets

[http://go.ncsu.edu/websocket](http://go.ncsu.edu/websocket)

How do you poll pretty much in real-time for updates? With web sockets there is a  persistent connection going both ways between client and server. Messages can be in JSON or plaintext. 

Websockets doesn't have caching or state management. Should use the right tool for the job. Should be used for real-time apps like games and collaborative editing, as well as real-time dashboarding - situations where you need low latency and fast syncing between devices.

Example: NCSU used real-time data from Google Analytics to show a list of items being currently viewed. App is called Now (node.js, socket.io, websocket.org and rails).

Another use case: staircase wall display and immersion lab. 

 - "Listen to wikipedia" app. Wikipedia broadcasts changes to IRC, wikimon takes IRC messages and sends to websockets
 - Visualization wall controller - showing images from digital collections

"There's a place for vanity metrics."

## personalize your google analytics data with custom events and variables

Out of the box, Google Analytics gives you the who, how and what. Also allows for customization/custom data for who/how/what data.

**Custom variables/dimensions** give you additional data about who's doing the stuff on your site. Similar to audience segments. Examples:

- logged in users
- people with items in shopping cart

**Events** give you more info about stuff that's happening beyond basic pageviews, i.e. download, facet flick, video play.

 - Built into contentdm. Enable it in website config tool, works with universal analytics
 - Custom analytics on CDM collections whenever a metadata field is present, report it as an event

You need to be comfortable with JS because custom event tracking requires a little more coding than the out of the box code. Be wary of timing/page loading issues. If DOM isn't ready, events won't be recorded.

[https://github.com/joshwilsonnc/ga_cdm](https://github.com/joshwilsonnc/ga_cdm)

## discovering your discovery system in real-time

Academic libraries in 2014: increasingly electronic resources, physical spaces for collaboration and visualization, librarians becoming active partners throughout the research process. And, discovery.

New challenge: make the discovery process and resource use more visible.

We have COUNTER stats through our publishers. Summon and discovery vendors provide some analytics but it's not real-time. Google analytics can record data but there's no API to see real-time access.

Project at Virginia Tech, Discovering Discovery, shows what items people are clicking in real-time. 

From summon, custom JS that records onclick events, then calls Summon API for item info. Using D3 library for some visualizations.

[Live demo](http://libx.lib.vt.edu/services/summonvis/recordscroll-only.html)