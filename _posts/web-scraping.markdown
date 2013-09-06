---
title: Architecting web scrapers
---

When people ask me to teach web scraping, they expect me to tell
them what Python code to write to pull the numbers out of the web page.
If I have time, I get to that, but I like to start by breaking down the
process by which a human would collect the data. I'm going to show you
how Scott, of the [Gulf Restoration Network](http://healthygulf.org),
and I are gradually shifting a very manual public notice review process
to a more automated process.

## Wetlands permit application public notice review
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

(Video of me drawing the process)

## Computers do things that people could do
We can swap any piece of this system for a more automated version, and gradually
transition to a highly automated system. It turns out that some of this automation
was done for us already.

(Drawing with cross-outs on the relevant parts, like removing the courier)

But if this whole system were run by a hip startup without any work ethic that
wants everything to be scripted and automated, it might look more like this.

(Video of me drawing the process)

Currently, we're approximately at this stage.

(Drawing with cross-outs)

## Things to think about

(Copy the list from my Hacks/Hackers Buenos Aires Media Party workshop.)
