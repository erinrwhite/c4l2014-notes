# day 2 - morning

## using d3 to visualize search results

Showed up late for this. Cool work visualizing subject headings for search results at Grinnell College: 

## visualizing library resources as networks

Matt Miller at NYPL Labs. Networks scale well - from hundreds to hundreds of thousands. Can see larger patterns and find outliers. And, can discover new things and make connections you had not thought about.

Demo: [http://archives.nypl.org/mss/2993](http://archives.nypl.org/mss/2993)

Example, search for Jack Kerouac and see visualization of his papers, the people and places he mentions. Using D3.js to visualize relationships.

Other connections: add institutional data like donors, or connect similar web visits.

### subject headings networks

Networks in the catalog: see each subject heading as a node in the network. Size of the node is determined by the number of occurrences.

Demo of NYPL subject headings network: [http://bit.ly/nyplnetwork](http://bit.ly/nyplnetwork)

Tech stack: using the Gephi tolkit to analyze a huge XML file to render the network. Used the Force Atlas 2 layout algorithm.

[Code up on Github](http://github.com/thisismattmiller/catalog-network)

## [we are all disabled! universal web design](http://bit.ly/c4l14-arty)

The number of people with disabilities is greater than the number of people who are visible minorities. Not a small number. 

**All technology is assistive technology.** Assistive technology is not just screen reader users. It can also include people who are using zoom features, magnifiers, just keyboards, just touchscreens. 

### universal design

Design of products to be usable by all people: i.e. ramps for wheelchairs aka ramps.

### universal web design

Implementing universal design in your code:

 - Haveconsistent nav, ordered content, conform to common patterns
 - Key strategies: mobile first, progressive enhancement, responsive web design
 - Use ALT text
 - DON'T use autoplay for media, blinking or flashing text
 - [death to the carousel](http://shouldiuseacarousel.com) - no keyboard accessibility there
 - Check the tabindexes on your site. Can you navigate by keyboard?
 - Use skip links to skip to content
 - ARIA i.e. `<nav role="navigation">`

Tools:

 - W3C Validator
 - HTML sniffer
 - WCAG contrast checker
 - Screen reader emulators

### universal content

How to train humans to add content:

 - use headers
 - use descriptive links
 - be clear and concise
 - add alt text and links to original videos

## dead simple video content management using the filesystem

Managing instructional/tutorial videos for the reference department. Lots of content management problems, repetition, cruft, etc. Lots o files, lots of code repetition.

"Replace self with small script"

One script for video playback, videos/metadata stored in a separate folder (together). Super-rudimentary MVC. The model is the file system. Using apache rewrites to redirect requests.