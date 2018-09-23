# The Collected (Mostly) Written Works of Stuart P. Bentley

On GitHub, in no particularly well-chosen order:

## [stuartpb.plan](https://github.com/stuartpb/stuartpb.plan)

A document in the tradition of [plan files](http://www.catb.org/jargon/html/P/plan-file.html), where I describe describes what I'm currently up to at a glance.

### Status

The beautiful thing about this, as described in the README there, is that there's no notion of "progress" as there is with all these other projects, as I'm constantly just updating the same brief document to reflect my current situation.

As of 2018-09-18, I'd stalled on this for months, because I hadn't been working on things I was happy to tell the world about: I'm getting back into the swing of things, so I'm probably going to start revisiting this again soon.

## [github.com/stuartpb/help-wanted](https://github.com/stuartpb/help-wanted)

A list of unfinished projects (not including writing projects, which are listed here), which I'd like somebody (anybody) to work with me toward completing (or at least getting to somewhere reasonably stable and useful).

### Progress

This never ended up catching on: I've got a new idea which I'm currently readying in https://github.com/unusualstudio/unusualstudio-projects.

That said, for the projects that it describes, this document is generally the best reference for explaining what the project is in about a paragraph, and describing the current status of that project. As I deprecate it, I'm going to look toward migrating such content somewhere within each project (where the project files in unusualstudio-projects will then link to, instead of the subsections of that document, as they do now).

## [Lean Notes](https://github.com/stuartpb/leannotes)

This is an umbrella project to cover all my documentation on how I approach developing other projects. It originally started as a series of Trello boards, plus a number of GitHub repositories I'd started (and, in a few cases, used) to gather more content I'd originally considered "out of scope" with the original project (which was originally meant to only cover web-service-style apps, for the most part).

Many of the pages there contain synopses that were originally written *here*, to describe the aspirations of some of these abortive side-repositories that have now been merged into this project.

Among the other merged-in content, one of the files that is now included within Lean Notes is [an obsolete synopsis of my writing process before many of my broad-scope incubator projects were established][how-i-roll/writing.md], the original incarnation of which having been where I had [my first real inkling of putting together a collection of writing-repos like this Collected Writings page](https://github.com/stuartpb/how-i-roll/commit/1a5d35abce6dba87bbcbd0e705aa710468149ddb).

[how-i-roll/writing.md]: https://github.com/stuartpb/leannotes/blob/master/content/8801d68b-a815-4c92-b9af-503aa47b1848.md

### Progress

As of 2018-09-21, I've just merged about a dozen other projects I had previously been writing in (or *not* writing in, as it were) to this repository: the plan going forward is that these projects will grow to feed and interconnect with each other, like a cluster of sunken boats forming a coral reef.

## Miscellaneous Assorted Specifications and Proposals

Maybe there should be a repo just for collecting these:

### [Static Page Application Specification](https://github.com/spaspec/spaspec-standard)

A standard for specifying rules for hosting a site consisting of static resources, beyond 1:1 filename mappings. I've actually started a whole organization for this, as I'd like to see this adopted as a cause by the SPA development community as a whole.

### [HTML Parts and Walls](https://github.com/stuartpb/pwalls-spec)

This is a really awesome concept that I've actually been using, polyfilled, in all my web development projects in the last two years: the trouble is, I haven't found the words to explain what my proposal *actually is* to people who don't get it.

Of all the proposals I've come up with, this is probably the one I want to see furthered soonest and most, as it is a siginifcantly simpler solution to a widespread problem than a lot of emerging complex standards in the web sphere today.

### [sane-icons-spec](https://github.com/stuartpb/sane-icons-spec)

A proposal to make adding icons to an HTML page a *lot* less stupid than it is right now, by introducing rules for *actually scaling* the thing instead of demanding a thousand different rendered sizes (and maybe even going as far as letting sites specify variants to fit into different aesthetics!)

After talking with Nolan Lawson, I've been thinking I'd rewrite this to put manifest.json at the fore instead.

### [CSS Plaintext Conversion](https://github.com/stuartpb/css-plaintext)

A proposal for some new CSS properties for defining how to present / convert HTML to plaintext, as well as some DOM methods to utilize them.

I put this forward in the service of a [flexible, interoperable standard for the `innerText` property](https://discourse.wicg.io/t/standardizing-innertext/799): its fate is probably to get buried in favor of Robert O'Callahan's way-narrower definition, which is disappointing.

### [MinDOM](https://github.com/stuartpb/mindom-spec)

A dumb idea for an instantiable, pre-minified version of the DOM's long method names. I basically just wrote this as a thought experiment, and to satisfy my yearning for somebody, *somewhere*, at *some point*, to have noted aloud that it would maybe be nice if `document.getElementById` were shorter.

## [The Biggest Mistakes I See People Make on GitHub](https://github.com/stuartpb/github-mistakes)

A guide to using GitHub right, starting from the position of the one thing I always know how to talk about: people doing things *wrong*.

### Progress

I spent a lot of time with this repo completely empty. I was originally calling this "Best Practices for Software Development on GitHub", thinking that I'd write "basically a synopsis of the process I've followed for all those projects listed in stuartpb/help-wanted", seemingly forgetting that I already have both stuartpb/how-i-roll *and* Lean Notes for this.

On top of that, I have things to say on the *periphery* of development with GitHub, but the *core* of what matters is something I think is covered well enough by articles like the existing [GitHub Guides][]. (Many of the things I'd have to say would be starting from a place of assuming the reader already [understands the GitHub Flow][flow].)

[GitHub Guides]: https://guides.github.com/
[flow]: https://guides.github.com/introduction/flow/

However, when I started putting together stuartpb.plan (described above), I had the thought that [I should really fill in one of the things I most wanted to talk about](https://github.com/stuartpb/stuartpb.plan/commit/5d844af92395333b4eb2beb02900ac5c5083fd5d), which led to me revisiting the project and filing issues for a few things I *would* be able to write about. *That* led to me revisiting the project again later, after re-discovering the GitHub Flow guide, thinking about what I'd be *adding* to that, and reframing the project in that light. From there, several sections started to easily fall into place.

## [petlogs](https://github.com/stuartpb/petlogs)

Journals of the customizations I've made to every persistent machine I use, so I can track down what changes might have screwed something else up, and so I can selectively re-make those changes if I have to re-roll the system.

### Progress

I've posted the merged repository of all the different gists that originally encapsulated each log. The next thing I want to do is make some command line tools that make it easier to push new log entries.

## [barfspace](https://github.com/stuartpb/barfspace)

As described in [how-i-roll/writing.md][], I'm constantly trying to find space to incubate things I want to say; this was the goal of the above "meditations" repo, initially, but I still had *some* standards and aims around what I did and didn't feel comfortable putting in that repo.

It led to a lot of tension; where I initially was putting well-considered passages that well expressed a single idea on its own for each file, the writing started getting more personal, and hairier - the writing was supposed to be the *result of* meditations, but I started using the *writing itself* to work out things, meaning that I was just writing *way* too much stuff, and, well, see [the introduction to the aforementioned synopsis on my writing][how-i-roll/writing.md] about how I don't like the idea of blog posts.

Basically, I was starting to write blog posts, and that made me uncomfortable. I don't like having persistent uncomitted files in a Cloud9 workspace, as I intend to treat C9 workspaces like cattle and not pets - ready to blow any of them away at a moment's notice.

In response, I started this project, where I would break that rule: I'd *only* keep posts in the Cloud9 workspace, and *never* commit files to the repository itself. This way, I at least have *somewhere* to put, in theory, *everything* (or, at least, everything that won't fit on Twitter).

### Progress

The open-ended nature of the barfspace project makes "progress" a bit of a nebulous concept; instead of talking about the *content*, I can talk about my progress in developing a *workflow* in publishing it.

I let this repo languish for nearly a year after I first created it (I came back the next day to create an autocommitting script, wrote a little bit about how weird writing without clear commit boundaries was, then basically wrote the project off as a novelty), in part because I didn't have [git-slum][] to summarize the commits, and I knew it could be done: after finally writing the code for git-slum in November 2017, I came back to barfspace a couple months later to integrate it, and now I'm using it again.

There are better musings in the repository itself on its current status: you should probably look there (at time of writing, the introspective docs are in the `docs` directory).

[git-slum]: https://github.com/stuartpb/git-slum

## [Pitches and Scripts](https://github.com/stuartpb/pitches-and-scripts)

This is a repo where I'm collecting my pitches for stuff I'd want to write for TV and film (and the stage, but that's kind of a one-off). The circumstantial description I originally had here around the repo's inception has been moved to the body of the README in that repo itself.

### Progress

I've got a few paragraphs on a few different TV pitches I've had in mind, and a couple lines gesturing at a couple movie ideas I've had.


## [The SACRED Tenets of Foundational Architecture](https://github.com/stuartpb/sacred-tenets)

Motivated by my frustrations finding 3D printable designs, but also inspired by my approach to software stuff, I'm trying to boil the criteria that drive my general approach to design down to some kind of rubric.

### Progress

I've refined the acronym to something I'm happy with, and polished up a few elucidatory notes on each tenet; the document is still not as comprehensive as I'd like it to be. I want to have something that, without fail, people who come up to it will walk away with their priorities forever changed.

## [Valley of Lost Careers](https://github.com/stuartpb/valley-of-lost-careers)

A series of short stories extrapolating from various online artifacts to describe the likely misadventures that would have led up to them.

These are sort of like [The Daily WTF's Feature Articles](http://thedailywtf.com/series/feature-articles), but without the pretense of being first-person accounts of things that actually happened. Instead, these stories are explicitly fabrications inspired by [working backwards from a few telling details](http://m.achewood.com/index.php?date=11262008).

### Progress

I've proposed a few scenarios in this vein in Slack, but I've yet to actually write any of them up. I just added *half* a story I'd wrtten a while back and had yet to commit, but it really isn't all that great without all the rest of the scenes in-between.

## [At Least Three Ways to Do Anything in Three.js](https://github.com/stuartpb/threejs-ways-to-do-it)

A wiki collecting all the vastly-different-approaches to solving problems in graphics programming (described in terms simple enough to implement with Three.js).

### Progress

I had a tab open for a few days where I had been typing up a list of a few topics for the index page: that tab was inadvertently closed for some reason that I don't remember, around which time I lost interest in writing this.

I've forgotten most of the things I was going to write here, but I've filed issues for [the one or two that I remember right now](https://github.com/stuartpb/threejs-ways-to-do-it/issues), and will add more if they ever come back to me.

## [CouchDB in a Hurry](https://github.com/stuartpb/couchdb-in-a-hurry)

A guide to using CouchDB (and other compatible systems like PouchDB) that skips over the obvious fundamentals you don't need to waste timeon explanations for, to jump directly to the weird, complex bits you actually need to understand before you can implement anything remotely meaningful.

### Progress

There's actually a few pages written toward this, enough to accomplish the mission statement (though more work on stuff like examples and techniques wouldn't hurt). I think I actually had somebody acknowledge that I wrote this via Twitter at one point, which is quite the milestone for me.

## [Gullibot](https://github.com/stuartpb/gullibot)

The rules to a story game about a robot that believes everything it hears, where each player takes turns "evaluating" the Laws of the Universe the robot has collected, similar to *[My Daughter the Queen of France](http://www.lamemage.com/friends/My_Daughter_The_Queen_of_France.pdf)*, *[Everyone Is John](http://jesterraiin.dropmark.com/167650/2976489)*, or the brainlike organ that operates Donald Trump.

### Progress

I have the general concept and gags that the game revolves around settled, but the mechanics are kind of up in the air right now, and haven't been playtested to make sure they're sensible, compelling, and orthogonal.

## [The Chatroom of Requirement](https://github.com/stuartpb/chatroom-of-requirement)

This was originally going to be an article on AirPair's blog thing - I was writing it for a competition they were doing. It describes how to implement a pretty-dang-simple realtime chat room (with no user accounts... but persistence!) using Node and RethinkDB.

### Progress

I didn't get it finished in time for the end of the competition, IIRC (which is why it's not available via AirPair), due to mandated editing requirements that I couldn't meet or something like that (like I had to show it to fifteen other people or something first), but the article is essentially complete, as far as I remember. (I think the layout didn't meet AirPair's manual of style or some such bullshit, and I was too tuckered out to revise it myself.)

## [If I Ran TF2](https://github.com/stuartpb/if-i-ran-tf2)

A collection of changes I want to see happen in Team Fortress 2.

### Progress

It's okay: some of it's not as well-described as I'd like (and one or two aren't even all that well thought out). I also don't track all the changes that actually *are* happening to the game all that well, and to be honest, I'm not all that engaged with the community any more (to the extent that I ever was).

## [FLOC Estimation](https://github.com/stuartpb/floc-estimation)

A less-subjective approach to agile development's "t-shirt sizing", but less prohibitive than estimating *rough* line-of-code-counts: describing features in terms of the number of *digits* need to express the number of lines required.

### Progress

Seeing as how I pretty much just described everything there is to the idea, I haven't really found the energy to flesh this out into even a blog-post-length amount of content. What this would need would be some case studies, and I've only used this in [the issue labels for Tabalanche](https://github.com/tabalanche/tabalanche-extension/labels), with myself, so I'm not really qualified to speak to that.

## [Guidelines for Human-Oriented Asset Retrieval and Deposition](https://github.com/stuartpb/hoard-guidelines)

Basically just a writeup of the system of bins, labels, and shelves I use to store stuff in my apartment, what procedures I follow to keep it operational, how it's designed, the rationale behind the decisions of it, things like that.

### Progress

I've written nothing on the subject (the biggest material contribution so far has been that title). Jeez, you'd think I could at least commit the label templates.

## [opws-testaccounts](https://github.com/stuartpb/opws-testaccounts)

Logs of what I've done when testing account systems of a site for the [OPWS](https://github.com/opws).

### Progress

Ironically, there *is* stuff in here, even though it's pretty much useless.

## [Mad Max Tarot Design](https://github.com/stuartpb/mad-max-tarot-design)

For some reason, the idea of doing a set of tarot cards for the first three Mad Max movies excites me, as well as a set of cards for the game. Other people've done ones just for Fury Road, and it's missing some of the *best material in the series*! (Thunderdome has a *literal Wheel of Fortune*, FFS!) I *can't* overlook that.

### Progress

I have *bare* descriptions committed for each card, but I only have *good* descriptions for a couple. Still, that's more than half the repos on this page have, and that's kind of embarrassing.

## [date-rosetta](https://github.com/stuartpb/date-rosetta)

A Rosetta Stone document for how different date formatting facilities specify date formats.

### Progress

I got all geared up to write this, then I felt like I should be writing it in code instead of a table (due to the vagaries and complexities of different date formatting specs), then I realized that I didn't care *that* much about date formatting. At time of writing, the document mostly lists several different date formatting libraries, then several different ways of formatting dates, and draws about three connections between the two.
