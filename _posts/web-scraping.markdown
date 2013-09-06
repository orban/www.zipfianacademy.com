---
title: Architecting web scrapers
---

When people ask me to teach web scraping, they expect me to tell
them what Python code to write to pull the numbers out of the web page.
If I have time, I get to that, but I like to start by breaking down the
process by which a human would collect the data.

## Wetlands permit application review
If you want to build something on a wetland in the United States, you probably
need to dredge or fill the wetland. In order to do that, you need a permit from
the Army Corps of Engineers. In order to get that permit, you submit an application.
The Army Corps announces to the public that they have received the application,
through a document called a "public notice". Then the Army Corps reviews the
application and approves or rejects it.

Some people worry that wetlands are being recklessly destroyed, so they form
advocacy groups to help prevent such destruction. Many of these groups watch
the public notices and then submit formal comments to the Army Corps if they
think a particular permit should not be approved.

## The analog version


## Computers do things that people could do
I wrote some reasonably convoluted [software](http://github.com/tlevine/scott)
to help review applications to dredge and fill wetlands.




If the students don't have a good example, I use
[Scott](http://scott.thomaslevine.com), my wetlands permit application
monitoring thing. The resulting diagram looks like this.
