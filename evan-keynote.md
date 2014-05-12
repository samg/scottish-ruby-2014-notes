# Why you should read code

Reading code helps you see how someone else thinks.

Write simple, non-clever code.
* Re-reading your metaprogrammed code months later will make you angry and
  confused.

Prefer repetition over abstraction
* Repetition is easy (you've done it once you can do it again)
* You pay dearly for the wrong abstraction
* resist abstraction until it's really proven necessary

Often it comes down to a feeling.  We call this wisdom.

Reasons to read code:
* Read for documentation
* Read for pleasure

The more code you read the better programmer you'll be.

### What should you read:

#### Start with something in context (e.g. Rails 1.2.4)

Rails 1.2.4
* 73,623 lines written 2004-2007
* Rails 4.1 169k of code (2x larger)
* The fact it's obsolete doesn't matter

#### Read something hard

* Read something outside of your level
* e.g. virtual box code

### How to Read

#### with a specific problem in mind

* it's easy to start with a specific problem you're trying to solve (e.g. why
  is virtual box so slow?)

#### without a specific problem in mind

* sort_by(&:interest)
* git log -p (shows you diffs for each commit with message)
* read old bug fixes (e.g. why did _that_ fix the bug).  A jumping off point to
  explore more.

#### pick an area of interest

* e.g. I wrote a web server so I'm curious how other webservers work.
* e.g. how did Rails 1 get a request
* git log -S WEBrick (-S searches commits for a string)
* git show deadbeef
* pt (is a search tool like grep, ack, etc.)
* Wow - Rail 1 had a option for concurrency.
* Rails 1 had "simple elegance", informs the decisions that were made later.

#### The "skim" map (term Evan made up to describe a process he did)

* Switch to Picture Mode
* See the structure not the details
* glance at a google map of Crieff for 1 second
* now look at code (look for the shape of the code)
* gives you "the feeling" for the code.  How does this code interact with other
  code?  What constants are used (e.g. syntax highlighting)

### Goals of this keynote

* Code reading is important
* Showing you waht to read

