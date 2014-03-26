# day 2 - afternoon

##  Sustaining your Open Source project through training

[tweets from this talk](https://twitter.com/search?q=%23c4l14%20%40eosadler&src=typd&f=realtime) Nutshell: training model now (on-your-own learning) is unsustainable. Need to train up and offer trainings for others, not forgetting mid-level coders. 

Many training workshops reveal other gaps in tech training opportunities.

And, many "non-coders" especially catalogers need and want training!

## Behold Fedora 4: The Incredible Shrinking Repository!

Improvements in Fedora 4: support for huge files, millions of objects, increased performance. Flexibility for hierarchy, storage backends (i.e. Amazon Glacier), pluggable authentication

## A reusable application to enable self deposit of complex objects into a digital preservation environment

UNC repository backed by Fedora. Developed an application to let users create forms that accept user submitted content for digital repository. Works include master's theses and other digital objects. 

Case study: Studio Art MFA program files. Multipart, multiformat works with descriptions for each file/part of the work.

[github.com/UNC-Libraries/deposit-forms](http://github.com/UNC-Libraries/deposit-forms)

## Organic Free-Range API Development - Making Web Services That You Will Actually Want to Consume

Usability and API's. Goal of API's is to let people use and innovate with your data. API is an opportunity to give the aspirational view of your data to the world.

### Standards

Tradeoff means stability but less ability to be agile with change. 

REST and SQL have a lot in common: CRUD functions, queries, requests.

### Security

Need to balance security with access. Be wary of PII (personally identifiable information). Never give someone access to do something they don't need to do.

### Documentation

Document your stuff and fail gracefully. Don't expect users to get requests perfect.

## Towards Pasta Code Nirvana: Using Javascript MVC to Fill Your Programming Ravioli

[go.ncsu.edu/js-mvc](http://go.ncsu.edu/js-mvc)

Metaphors for describing software architectures: spaghetti code, lasagna (nicely done MVC well-structured). With ravioli we can fill our pasta with whatever we want. None are dependent on the other and it helps us create an interesting dish. Code is more modular and easier to maintain.

Principles we're going for: modular, reusable, testable code.

Tao of programming: the master said "A well-written is its own heaven. A poorly-written program is its own hell."

### so...javascript?

JS is everywhere now. Quite the evolution since the mid-1990s. It's fast. And it's the lingua franca of developers.

### js mvc?

Approximate architecture: model, view, controller and **data binding**.

Benefits:

- abstracts DOM interaction
- encourages code reuse, modularity and testing
- strong community
- cognitive load is greatly reduced

## PhantomJS+Selenium: Easy Automated Testing of AJAX-y UIs

[SeleniumIDE - browser add-on+desktop software](http://t.co/OQum0rYu1n) for testing JS interfaces. Selenium records your actions into a test script. Export scripts as a test case for Python, Ruby, C#...

[Code on Github](https://github.com/mredar/code4lib-2014-PhantomJS-Selenium)

## Queue Programming -- how using job queues can make the Library coding world a better place 

Job queues for Python using RQ library. Very technical talk at the end of the day so not a lot of notes from me.