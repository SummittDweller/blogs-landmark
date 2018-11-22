---
title: "What Happened to the IGO Website?"
date: 2018-11-21T20:00:00Z
---

You probably came here expecting to find the [Iowa Geocachers' Organization website](https://iowageocachers.org), and you may wonder, "What's up?", because this ain't it.  My alter-ego, *Summitt Dweller* is going to temporarily hijack this blog in order to try and explain what happened, and what to look for in the future.

The old IGO website was created many years ago using a CMS, or [Content Management System](http://https://en.wikipedia.org/wiki/Content_management_system), namely [Drupal](http://drupal.org). When it was first created, the site used *Drupal v5*, and not long after I migrated the site to the "new" version 6.  There were not a lot of IGO members at that time so the website didn't have a lot of members, or features.  That migration was a piece-of-cake, and entirely worthwhile.  Unfortunately, the migration path to *Drupal v7* was not so straightforward, and the organization had grown substantially, so the site remained in version 6.  *Drupal* has since moved on to version 8, with version 9 now on the horizon, and these versions are dramatically different than previous versions, making migration even more challenging.  

Community support for *Drupal v6* ceased on February 24, 2016, leaving the IGO site susceptible to elevated security risks if not migrated to another version, or another system.
I started looking at migration strategies in 2016 and have been actively planning for and working on migration, to *Drupal v8*, since that time.

On **November 14, 2018**, the security risks finally caught up to the old IGO site, and the Linux server hosting the website was apparently compromised through a vulnerability in the IGO site, or another of the websites I built there.  The threat was bad enough that the host manager had no choice but to shut down the server to avoid permanent and wide-spread damage.  Fortunately, because I have been working on migration for so long, I had, and still have, a relatively "fresh" backup copy of the IGO's data.  That data is safe.

## So, Where Do We Go From Here?

To explain where I hope to take the IGO site in the future, I'll need to rewind the clock a little.  The following is an excerpt from an email conversation I recently had with members of the *IGO Board of Directors* (BOD) *Website Committee*:

{{% original %}}
I have really been struggling to move the old site to a new version of Drupal, and I fear that by the time it is done another version will be on the horizon and the site might be so complex that it will be difficult to maintain and migrate again.  About 4 years ago I was part of a minority Drupal community* concerned about the direction the platform was taking.  We argued that the changes being made would take small, independent, individual developers like me, out-of-the-market because the complexity would be such that only established companies with substantial staff would survive the change.  The powers-that-be argued that would not be the case, but frankly, that’s pretty much what has happened.  I can certainly see it now that I have considerable migration experience, and too many failures to count, with two other sites.

\*Well, it looks like the “minority Drupal community” mentioned above has come through to save the day!  My like-minded colleagues in that minority have developed a CMS called “**Backdrop**” (see https://backdropcms.org/why-fork-drupal and https://backdropcms.org/).  Backdrop basically takes all of the “goodies” from Drupal v7 and preserves them with NO complex changes or additions.  

This morning I successfully migrated most of what we want to keep in the IGO site to a temporary Drupal v7 site, and now I’ll try to migrate that to Backdrop.  If that works, and it should be an easy move, I’d like to replace the existing IGO site ASAP with a new “working copy” built in Backdrop.  The new site won’t have everything we need initially, but we won’t have lost anything because I have it all backed-up in the temporary D7 site.
{{% /original %}}

I wrote that email on November 11, 2018, three days before the server had to be shut down.  I regret that we lost that server, but I'm thankful for the timing since I can confidently say that our data is still intact (in my backups) and accurate.

There's another portion of that email conversation that I'd like to share here, because I hope it gives you some sense of what the future IGO website will, and will not include.  I've proposed that IGO is about geocachers, and not so much about geocaches.  To follow-up on that I've also suggested that we drop some old website "features" and data, and keep others.  The list looks something like this:

{{% original %}}
DROP these items:

* Geocache ‘harvest’ and cache listings database
* Geocache logs
* Iowa Favorites

KEEP these items:

* Stats
* Catalog/Store
* Governance items
  - Bylaws
  - Minutes
  - BOD Roster (& past year rosters/Historical)
  - Member Roster
  - Election & Polls
* Images
* Documents
* Events (IGO sponsored only)
* Social Media

If possible, keep the COTM, perhaps with a different voting mechanism (since the existing one is complex and difficult to manage).
{{% /original %}}

Please watch this address, [https://iowageocachers.org](https://iowageocachers.org), for future news of the migration to **Backdrop**.  This blog is static, so it does not support sharing comments or concerns; however, if you would like to comment on anything reported here please email me at [admin@iowageocachers.org](mailto:admin@iowageocachers.org) or the [IGO Board of Directors](mailto:bod@iowageocachers.org).

Until next time... take care.
