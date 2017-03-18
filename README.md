# The Collected (Un)written Works of Stuart P. Bentley

On GitHub, in no particularly well-chosen order:

## [github.com/stuartpb/help-wanted](https://github.com/stuartpb/help-wanted)

A list of unfinished projects (not including writing projects, which are listed here), which I'd like somebody (anybody) to work with me toward completing (or at least getting to somewhere reasonably stable and useful).

### Progress

[Incomplete](https://github.com/stuartpb/help-wanted/issues/1), though the selection that's covered so far is a pretty fair sampling (probably the projects I'd like most to share, that I've also put some effort toward).

## [github.com/stuartpb/meditations](https://github.com/stuartpb/meditations)

Assorted quips and mini-essays on various topics relating to best practices etc. Originally assembled as a set of guidelines on writing specifications and standards, but pivoted into a collection of miscellaneous musings on general behavioral patterns.

### Progress

I've set this up, but I'm not writing to it on a regular basis yet.

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

## [Best Practices for Software Development on GitHub](https://github.com/stuartpb/github-best-practices)

Supposed to be exactly what it says on the tin: basically a synopsis of the process I've followed for all those projects listed in stuartpb/help-wanted.

### Progress

Not yet started.

## [stuartpb/how-i-roll](https://github.com/stuartpb/how-i-roll)

Another attempt to document my normal approach to accomplishing stuff, this time just gathering all that kind of stuff together in general. Notably, contains [a pretty robust synopsis on how I ended up with all these text-only repositories in various states of incompletion](https://github.com/stuartpb/how-i-roll/blob/master/writing.md), in which I note that I would probably end up eventually putting together what I'm typing right now.

### Progress

Doesn't really contain a lot _more_ than that aforementioned synopsis.

## [stuartpb on Security](https://github.com/stuartpb/stuartpb-on-security)

Where I'm going to put all the stuff I've been wanting to say about security and auth systems design for years, but have been to scared to say (because it's mostly just co-opting the tone of everybody else who writes in the infosec space, with zero practical/firsthand experience or evidence to back it up).

### Progress

Literally just initialized the repo right now as I'm typing this.

## [Nerd First: How and Why to Build Your Thing Around the Ones Who Will Geek Out Over It](https://github.com/stuartpb/nerd-first)

This is where I want to put together my whole philosophy of what *actually matters* when you're making a thing, and how that will lead to success. Notable right now as the location where I've publically posted :family: = :eyes:(:zap::monkey:)² + :ear:(:lips:) - :hankey:, which is basically my seven-emoji substitute for reading The Tipping Point.

### Progress

Doesn't contain a *tenth* of the content I want it to have: given a generous publisher's advance, I could write *pages* and ***pages*** of examples of products that have (ostensibly) followed this principle to success ("How The AeroPress Taught Me Everything I Needed to Know To Strike It Big In Silicon Valley, Despite Not Actually Having Done So"), making my dumb little metaphor seem like a law of nature without having to provide a lick of empirically-validated evidence. (When I grow up, I wanna be a pundit, too.)

## [Undesign: An exploration of Emergent Behaviors, Fractal Restrictions, and Discoverability](https://github.com/stuartpb/undesign)

This is another topic (or collection of topics) I feel like I have a lot to write about: how communities form around features and bugs, how features get picked up without the users having to be told about them, stuff like that. If *Nerd First* is my version of *The Tipping Point* or *The Black Swan*, *Undesign* would be my *Blink* or *Antifragile*. (Actually, I should probably read *Antifragile*, especially considering how often I talk about it.)

### Progress

*Undesign* is unwritten.

## [TV Spec Scripts](https://github.com/stuartpb/tv-specscripts)

So, the other day in Slack, I made this joke about how this metaphor I just described would work well as a gag on Silicon Valley, and then Dan Hiester started talking about how that's how Ronald D. Moore got started as a writer for *Star Trek: The Next Generation*, and I've kind of been saving up bits and pieces of spec scripts for years under the assumption that nobody'd want to read them, and so...

### Progress

I'm looking to gether those bits and pieces into something in a repo now.

## [Valley of Lost Careers](https://github.com/stuartpb/valley-of-lost-careers)

A series of short stories extrapolating from various online artifacts to describe the likely misadventures that would have led up to them.

These are sort of like [The Daily WTF's Feature Articles](http://thedailywtf.com/series/feature-articles), but without the pretense of being first-person accounts of things that actually happened. Instead, these stories are explicitly fabrications inspired by [working backwards from a few telling details](http://m.achewood.com/index.php?date=11262008).

### Progress

I've proposed a few scenarios in this vein in Slack, but I've yet to actually write any of them up.

## [Primer Prime](https://github.com/stuartpb/primerprime)

This is, essentially, *the* history of computing that I want to write: one that covers all the little quirks that led to the world you *actually have to deal with* to work in technology today (the answers to most questions people have being "because that's what Ken Thompson needed to write Unix on his computer at Bell Labs in the seventies").

I'm going to sneak in a link to [this Rolling Stone article by Steward Brand that I painstakingly converted to HTML](https://github.com/stuartpb/spacewar-article), which taught me a lot about the state of the field in the early seventies, and is otherwise not easily available on the Web. I should *probably* ask the author for permission to rehost it at some point.

### Progress

So far, I've tried to write this from the beginning; as a result, I got about as far as 1890, and then I hit a roadblock since (the *really* interesting stuff doesn't happen for about seventy-five years.)

At some point, I should just start copypasting everything I've ever written when answering questions that start with "Why does my computer", and then by the end of it I'd probably have half the book written.

## [Homo Socialmediis: The Myth of the Magical Content Marketing](https://github.com/stuartpb/homo-socialmediis)

Why and how we have this insane hype bubble around the dumbest forms of "social" "interaction" online, when the kind of possibilities that are *[actually worth getting excited about](http://www.cluetrain.com)* have yet to materialize.

### Progress

I have collected *mountains* of salt on this topic, which I am fully prepared to explode onto the page at the slightest provocation. If I get one more memo on a "sales strategy" that consists exclusively of sending unsolicited connection requests through LinkedIn, I'm probably going to knock out the first three chapters in one sitting.

## [At Least Three Ways to Do Anything in Three.js](https://github.com/stuartpb/threejs-ways-to-do-it)

A wiki collecting all the vastly-different-approaches to solving problems in graphics programming (described in terms simple enough to implement with Three.js).

### Progress

I've had a tab open for a few days where I've been typing up a list of a few topics for the index page.

## [CouchDB in a Hurry](https://github.com/stuartpb/couchdb-in-a-hurry)

A guide to using CouchDB (and other compatible systems like PouchDB) that skips over the obvious fundamentals you don't need to waste timeon explanations for, to jump directly to the weird, complex bits you actually need to understand before you can implement anything remotely meaningful.

### Progress

There's actually a few pages written toward this, enough to accomplish the mission statement (though more work on stuff like examples and techniques wouldn't hurt). I think I actually had somebody acknowledge that I wrote this via Twitter at one point, which is quite the milestone for me.

## [Guillibot](https://github.com/stuartpb/gullibot)

The rules to a story game about a robot that believes everything it hears, where each player takes turns "evaluating" the Laws of the Universe the robot has collected, similar to *[Everyone Is John](http://jesterraiin.dropmark.com/167650/2976489)*, or the brainlike organ that operates Donald Trump.

### Progress

I have the general concept and gags that the game revolves around settled, but I haven't really stitched them together into a compelling set of mechanics - and I haven't committed or pushed *anything* yet.

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

## [petlogs](https://github.com/stuartpb/petlogs)

Journals of the customizations I've made to every persistent machine I use, so I can track down what changes might have screwed something else up, and so I can selectively re-make those changes if I have to re-roll the system.

### Progress

I haven't even *created the repo* yet - I've done a bunch of these in the form of gists, but I haven't merged them into a single repository yet.

## [opws-testaccounts](https://github.com/stuartpb/opws-testaccounts)

Logs of what I've done when testing account systems of a site for the [OPWS](https://github.com/opws).

### Progress

Ironically, there *is* stuff in here, even though it's pretty much useless.

## [stuartpb-exit-codes](https://github.com/stuartpb/stuartpb-exit-codes)

Documentation for the standard reasons I'd exit a thread (read: conversation).

You know that thing where someone's just being incredibly tedious and awful, so you just want to walk away? This is for that, except the idea is that you can drop a hyperlink to help them better understand *why* they're being tedious, and what they could do to *not* be tedious in the future.

### Progress

Honestly, as useful as having these in a single place would be, writing them - and then *citing* them - makes me feel like a colossal asshole, so I kind of gravitate in and out of even using this. That said, I have jotted down a few notes that are in the repo.

## [Waxhead Revisited](https://github.com/stuartpb/waxhead-revisited)

A gonzo walkthrough for cheesy 90s FMV point-and-click adventure game [Are You Afraid of the Dark? The Tale of Orpheo's Curse](http://orpheoscurse.wikia.com/wiki/The_Tale_of_Orpheo's_Curse), to give me an outlet for florid prose for when I'm feeling nostalgic and/and drunk.

### Progress

2spoopy4me

## [Secret Hitler FAQ](https://github.com/stuartpb/secret-hitler-faq)

A collection of insights(?) about the game [Secret Hitler](http://secrethitler.com/).

### Progress

Two questions posed, one of which is (almost) answered.

Honestly, if I don't end up just deleting this, I kind of want to move this to a different org where I'd collect different Secret-Hitler-player-community projects: I'm kind of concerned with the way that there's a repo attached to my GitHub account with Hitler in the name, as well as [a repo on GitBook about Hitler](https://www.gitbook.com/book/stuartpb/how-you-end-up-with-hitler/details) (that I started writing after realizing that the *Cards Against Humanity* guy knows more about an extremely important part of history than I do).

## [Mad Max Tarot Design](https://github.com/stuartpb/mad-max-tarot-design)

For some reason, the idea of doing a set of tarot cards for the first three Mad Max movies excites me, as well as a set of cards for the game. Other people've done ones just for Fury Road, and it's missing some of the *best material in the series*! (Thunderdome has a *literal Wheel of Fortune*, FFS!) I *can't* overlook that.

### Progress

I made a workspace for this, and I think there's some cool stuff in that workspace, but I haven't committed or pushed it yet, maybe because the idea of dedicating a bunch of time to *that* when I'm ignoring *all the other stuff on this page* is just too much to bear.

## [date-rosetta](https://github.com/stuartpb/date-rosetta)

A Rosetta Stone document for how different date formatting facilities specify date formats.

### Progress

I got all geared up to write this, then I felt like I should be writing it in code instead of a table (due to the vagaries and complexities of different date formatting specs), then I realized that I didn't care *that* much about date formatting. At time of writing, the document mostly lists several different date formatting libraries, then several different ways of formatting dates, and draws about three connections between the two.

## [western-civilization-walkthrough](https://github.com/stuartpb/western-civilization-walkthrough)

This is supposed to be a joke in the vein of the [GameFAQs walkthrough for Problem Sleuth](http://www.mspaintadventures.com/?s=4&p=000816) (maybe crossed with [this t-shirt](https://www.topatoco.com/bestshirtever/)), where it gives the "strategy" for "winning" at various points in human civilization. 90% of the "strategies" are basically "be born in the right place at the right time", and the rest is "commit atrocities on indigineous peoples for 9/10 of the game, then symbolically atone at the last minute so you can claim reparations are uncalled for".

### Progress

Yeah, since I just told you the punchline, why bother to write the joke?

I think the point I was originally trying to make with this is that "ahead of its time" is a thing, and how, for instance, you wouldn't make it very far trying to be an oil tycoon in the 1700s. That said, if there's any real value to be had in this premise, I'm pretty sure I'm not going to be the one to find it.
