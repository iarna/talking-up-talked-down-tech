# Talking up talked down technology!

![](wombat0.jpg)

* Speaker: Rebecca Turner
* Twitter: @ReBeccaOrg
* Github/IRC/etc: iarna
* Job: cli @ ![inline](npm-logo.png)

^ Hi! I'm Rebecca Turner and I'm your post lunch speaker. I hope everyone is happy and full.

---

![](pig0.jpg)

# Talking up talked down technology!

^ Today I'm gonna be talking up technologies that are often talked down.

^ I'm not gonna talk about where they are now, or their suitability to any purpose these days.

^ Some are still great, no matter what flack they get, some have their place in history.

^ Most are still widely used! I'm also not going to talk about why people like to talk them down.

^ No, we're gonna be POSITIVE!! How did they get the point where they were popular enough to be popularly unpopular?

---

![](pig0.jpg)

# Talking up talked down technology!

^ To do this we're going to be traveling back in time to when the web was young and everyone was writing templating libraries…

---

![](cat0.jpg)

# MySQL 3

## What is it?

^ SQL based network accessible database.

^ No transactions.

^ Limited subset of SQL.

^ Originally built to be ideal for storing things like logs and datasets with lots of new rows.

---

![](cat1.jpg)

# MySQL 3

## Time & Place

^ 1998. Netscape had just been purchased by AOL.

^ 256 kilobit was considered broadband.

^ PHP 3 is brand new. Hooking a database up to a website is cutting edge– books extolling the virtues of this are still being published.

---

![](cat2.jpg)

# MySQL 3

## You are…

^ …a self taught web developer because that's the only kind.

^ You need a database for your CGI scripts to talk to.

^ You've used berkley db previously, which is an indexed local-file key-value store.

^ But locking means that your sites are pretty limited speed-wise and you can't scale to more than one web server.

---

![](cat3.jpg)

# MySQL 3

## Why you need it!

^ MySQL is ideal in many ways.

^ It's freely available to download and try out, although not free software (yet), but buying a license is inexpensive.

^ By contrast Oracle licensing is prohibitively expensive can still cost between tens of thousands and hundreds of thousands of dollars.

---

![](cat3.jpg)

# MySQL 3

## Why you need it!

^ Installation is incredibly easy–no setup needed.

^ And drivers are widely available for ALL the popular web technologies.

^ Setting it up is something any sysadmin can handle and doesn't require a DBA.

^It basically just works out-of-the-box.

^ By contrast Oracle at best takes hours to setup and at worst requires a DBA on staff to tune it.

^ PostgreSQL exists, but requires some setup to be useful.

^ Even this little friction matters when "setting up database software" isn't your job.

---

![](cat3.jpg)

# MySQL 3

## Why you need it!

^ Of course, you still need to learn SQL, but that's not so bad because they have _extensive_ documentation, on the web.

^ And even though it's sometimes dry reference material, the user provided comments fill in those gaps with example usage and suggestions on how to solve specific problems.

---

![](cat3.jpg)

# MySQL 3

## Why you need it!

^ Also surprisingly important is that it's incredibly fast while accepting new connections.

^ This is critical when your applications are CGI or PHP scripts as both have to reconnect on every request.

^ The overhead of competing products makes them much harder to work with.

---

![](dog0.jpg)

# PHP 3

## What is it?

^ PHP 3 is a procedural web focused scripting language that was primarily found embedded in web servers.

^ It was the first version of PHP to gain widespread popularity.

---

![](dog1.jpg)

# PHP 3

## Time & Place

^ 1998. Again. Uh, that may end up being a bit of a theme. =D

^ Servers are super expensive. Smaller websites can't afford their own servers and virtual servers aren't a thing.

^ The "cloud" is nothing more than a blob on your network diagrams.

^ So you settle for "shared hosting" where your web pages are served by the same webserver as other folks.

^ This is very inexpensive, but running software on them is limited.

^ Most hosting providers don't allow this, and even when you can, CGI scripts are often uncomfortably slow.

---

![](dog2.jpg)

# PHP 3

## You are…
### _working for a webhosting company_

^ Your users want "dynamic" websites. You've grudgingly let your users use CGI scripts, but they use a lot of system resources as they have to be run all over again for every web request.

^ Most of those are written in Perl, though other languages get some use. You'd really like something more performant…

---

![](dog3.jpg)

# PHP 3
### _working for a webhosting company_
## Why you need it!

^ Popular scripting languages are available as plugins for Apache (such as mod\_perl & mod\_python), but none of them are suited to shared hosting.

^ They all provide a persistent interpreter across requests, which is great for speed but also means that different websites will end up sharing an interpreter and memory and can interfere with each other.

^ They're also finicky to get setup right and as a rule require a cache in front of them because of memory consumption.

^ Folks coming from CGI regularly write software that leaks memory and when they come to something like mod_perl they're lost as to how to track that down.

---

![](dog3.jpg)

# PHP 3
### _working for a webhosting company_
## Why you need it!


^ Enter: PHP–it's easy to setup and because it ditches all of its memory between requests it has the same security profile as CGI scripts and the same memory management.

^ Plus it's a kitchen-sink-included language so your users aren't bugging you install modules for them.

^ Because it's so easy to setup–with most Linux distributions you can just install the package and be done–you and your competitors adopt it as the easy choice.

---

![](dog4.jpg)

# PHP 3

## You are…
### _a web developer_

^ …working for a web-design firm or a small business.

^ You need someone to host your "dynamic" website without having to invest a large amount of money up front.

---

![](dog5.jpg)

# PHP 3
### _a web developer_
## Why you need it!

^ It runs so much faster than CGI because it's built into the webserver.

^ Your web hosting company is happy to provide access to it too.

---

![](dog5.jpg)

# PHP 3
### _a web developer_
## Why you need it!

^ Many CGI based sites didn't use any templating and just printed HTML. While that's been changing quickly, PHP has embedded code right from the start!

^ It's default mode of interaction is code embedded in HTML.

^ This approach makes it super easy to start with a static layout and extend that.

^ It also makes the language feel web-native.

^ And because it encourages this incremental approach, it is much easier to get designers up to speed with it.

^ You can see it creating an entirely new generation of web developers all around you.

---

![](dog5.jpg)

# PHP 3
### _a web developer_
## Why you need it!


^ It comes with libraries built in to do almost anything you could want to do, from custom graphics, to email, to database access.

---

![](dog5.jpg)

# PHP 3
### _a web developer_
## Why you need it!


^ It has extensive web-based documentation that's obviously available from their website.

^ What's more, because they distribute all of their own libraries the documentation for those is searchable in the same place as the language reference.

^ You don't have to worry about which version of a module to use, because it's all just there.

^ **Aside on comments being useful.**

---

![](crab0.jpg)

# XML

## What is it?

^ * Extensible Markup Language

^ * A set of rules for creating markup languages like HTML.

---

![](crab1.jpg)

# XML

## Time And Place

^ 1998. Again. 1998 is a transformative year for the web.

^ The web and HTML are well and truly taking over the world.

^ Everyone wants to hook their legacy datasources up to the Internet.

---

![](crab2.jpg)

# XML

## You are…

^ … writing software that integrates disparate computer systems. You need an interchange format of some kind.

^ Traditionally either you or the folks you're integrating with would have made up a new file format and then written a custom parser or importer, but times are changing…

---

![](crab3.jpg)

# XML

## Why you need it!

^ There's this new thing, made by the same folks who behind things like HTML.

^ It _looks_ a lot like HTML, but you can make up your own tags.

^ It's also way more regular, so writing parsers is a snap. As a bonus they reject bad inputs entirely, which means you won't need to write a parser that can handle sloppy inputs.

---

![](crab3.jpg)

# XML

## Why you need it!

^ It was only just finalized in January, but because it's so easy to parse there are already full featured parsers available for all the popular languages.

^ Having this, well, meta-fileformat that you can plug a standard parser and emitter into saves a huge amount of work that would previously have been required.

^ Plus maybe you can finally convince those mainframe folks to stop giving you fixed width text exports.

---

![](crab3.jpg)

# XML

## Why you need it!

^ It's even common to have both document and stream based parsers available.

^ The former makes working with smaller documents easy as pie, and the latter makes loading even gigantic datasets possible.

---

![](crab3.jpg)

# XML

## Why you need it!

^ What's more, because of how it was designed, with little effort you can extend your file formats in backwards compatible ways.

^ This let's you finally decouple the different parts of the systems you integrate, which in turn makes working with outside teams so much easier.

---

![](duck0.jpg)

# Perl

## What is it?

---

![](duck1.jpg)

# Perl
### _(for the web)_
## Time And Place

^ 1996. The web is young and folks with dynamic websites are few and far between.

^ While there are some proprietary solutions available, most folks are using CGI scripts to power their websites, usually in small ways as form processors, but larger sites are built to.

^ CGI scripts are simple, they're just executable programs that get a known set of environment variables with information about the request and print out what they want sent back to the user.

---

![](duck1.jpg)

# Perl
### _(for the web)_
## Time And Place

^ Perl got its start as a sysadmin language.

^ It's widely adopted and while it isn't part of the stock install on major flavors of Unix, it is almost always added later.

^ It's already a key part of every Linux distribution and the ascension of Linux is starting to become obvious to most folks.

---

![](duck2.jpg)

# Perl
### _(for the web)_
## You are…

^ … a sysadmin or systems programmer who's been asked to put together a website for your organization. You need to pick a language for your CGI scripts…

---

![](duck3.jpg)

# Perl
### _(for the web)_
## Why you need it!

^ Well, everyone knows Perl. You could write your CGI scripts in C, and some folks do, but writing and maintaining a C program is substantially more time consuming.

^ This is doubly so given that most of what CGI scripts are doing is reading strings from users and printing strings back to them. Perl is excellent with text processing.

---

![](duck3.jpg)

# Perl
### _(for the web)_
## Why you need it!

^ What's more, it's trivial to write Perl programs that are portable across Unix versions, which can't be said for C or even for shell scripts.

---

![](duck3.jpg)

# Perl
### _(for the web)_
## Why you need it!

^ Perl 5 is the new hotness, but Perl 4 is widely used. Some of the earliest web related libraries are available for it, from libwww to cgi-lib.pl.

---

![](duck3.jpg)

# Perl
### _(for the web)_
## Why you need it!

^ Perl 5 is even more exciting.

^ It has excellent libraries for dealing with the web, in both libwww and CGI.pm. And it has the CPAN, a grand new experiment in sharing modules for programming languages.

^ It started as a centralized FTP archive, but this is the year that the first version of its package manager is released. Since these are machines you admin, getting libraries installed is no problem.

^ And already, this new experiment in a largely uncurated module repository is proving to be popular, giving you premade tools for almost any job.

---

![](fern0.jpg)

# Visual Basic

## What is it?

---

![](fern1.jpg)

# Visual Basic

## Time and Place

^ 1993. Windows for Workgroups has been spreading like wildfire.

^ Many small departments in large companies have been setting up their own file and print servers. NCSA Mosaic exists, but you've probably never even heard of it.

^ If you're listening to tech hype you've maybe heard of the web but it's hardly a thing ordinary folks have heard of.

^ When you think software the only kind that matters is the kind that comes on a disk and you run on the desktop.

---

![](fern2.jpg)

# Visual Basic

## You are…

^ Working for a shop that previously has been writing DOS applications but wants to get into this Windows thing.

^ Or maybe an IT department worker who's finding they need greater flexibility then things like spreadsheet templates and macros can provide. An easy to use Windows application would be grand…

---

![](fern3.jpg)

# Visual Basic
## Why you need it!

^ Almost everyone knows some kind of Basic and Visual Basic provides some easy quality of life enhancements on that.

^ If you'd used qBasic or Turbo Basic in DOS then it's even easier.

^ C is finicky and it's always been hard to teach pointers, so it's always harder to find folks comfortable with C.

---

![](fern3.jpg)

# Visual Basic
## Why you need it!

^ And Visual Basic is an amazing experience. You start by designing your user interface, directly designing what you want your program to look like.

^ Then you can easily hook code up to bits you've designed.

^ While you can't see all your code at once, this approach does mean that you're never looking at more then a small readable chunk.

---

![](fern3.jpg)

# Visual Basic
## Why you need it!

^ What's more, while other programming language environments do come with "form designers" similar to the one in Visual Basic, once you start adding code to them you can't go back and edit the forms.

^ They generate C code to produce the form you designed. If you want to make further changes you have to go in and edit that C code directly.

^ And the generated code is often pretty opaque especially when you're first starting–after all, you've never seen any of these functions or variables before, you were just editing in a GUI up till this point.

---

![](fern3.jpg)

# Visual Basic
## Why you need it!

^ And because it's easy to teach, many of the more forward looking community colleges have started to teach it so finding new co-workers doesn't always mean teaching them an all new language.

---

![](bug0.jpg)

# TCL(/Tk)

## What is it?

^ You've probably never hard of TCL/Tk, unless you're of a certain age. I'm including it because if you _have_ heard of it, it's probably been grousing. I've done my share, I have to admit, so this is my penance.

^ TCL is a string centered scripting language that was specifically designed to be easy to embed in other software.

^ In its heyday this alone really set it apart from other scripting languages.

^ These days LUA has largely supplanted it in that role.

^ Tk is it's GUI library.

---

![](bug1.jpg)

# TCL(/Tk)

## Time and Place

^ Early to mid nineties.

---

![](bug2.jpg)

# TCL(/Tk)
## You are…

^ … in need of a cross-platform GUI development environment.

^ Or maybe you're a web developer looking to do best-in-class webserver integration in a time when dynamic websites were rare.

^ Or maybe your router can run TCL programs… stranger things have happened!

---

![](bug3.jpg)

# TCL(/Tk)

## Why you need it!

### cross platform GUI

^ With a much smaller runtime and faster startup times than that new upstart Java, TCL/Tk is one of the few good options for writing truly cross-platform GUI apps.

^ Programs written with TCL/Tk can run on fancy SGI workstations, Solaris desktops, Macintosh computers, and PCs with Linux and Windows.

^ While the user interface only looks at home on Unix & Linux machines, this kind of broad availability is largely unheard of.

---

![](bug3.jpg)

# TCL(/Tk)

## Why you need it!

### web developer

^ TCL as a web developer? Yes! You want a highly performant database backed website and you want the state of the art.

^ And that state of the art is NaviServer (later renamed AOLServer). It has multithreading and database connection pooling.

^ That later one is critical if your database is something like Oracle where new connections are extremely expensive. TCL's string focus also holds up well when working with web pages.

---

# Talking up talked down technology!

![](wombat1.jpg)

* Speaker: Rebecca Turner
* Twitter: @ReBeccaOrg
* Github/IRC/etc: iarna
* Job: cli @ ![inline](npm-logo.png)

^ Thank you all for joining me for my historical boosterism.

^ If you're curious what the genesis of this talk was, say hi the hall.

^ Or hit me up with your own favorite talked-down tech to talk-up!
