---
title: "Review of Patent Defense for FOSS Developers"
date: 2015-02-15 04:47 UTC
tags: BizLeg, Patents
summary: "This is a review of Chapter 4 of the *SFLC Legal Primer*, *Patent Defense for FOSS Developers*, inside it describes the anatomy of a patent, how to deal with claims brought against you, and why you, as a FOSS developer, should not bother with patenting your software, even as a protective measure."

---

# Review of Patent Defense for FOSS Developers

This is a review of Chapter 4 of the *SFLC Legal Primer*, *Patent Defense for FOSS Developers*, inside it describes the anatomy of a patent, how to deal with claims brought against you, and why you, as a FOSS developer, should not bother with patenting your software, even as a protective measure.

Anatomy of a Patent:

**1. Title,** which has no legal bearing.

**2. 7-digit uniquie identifier and an application identifier.**

**3. Abstract,** a short summary that rarely has any impact on the proceedings.

**4. Drawings,** in software these are usually just architecture diagrams or flowcharts.

**5. Related patent applications,** 'related' here can mean a number of things from continuation of old patents to patents that were originally filed jointly that are now separate.

**6. Background of the invention,** gives the applcants view of prior art, though often left out for fear it might limit the scope of the patent more than the applicant wants.

**7. Summary of the invention,** a summary of the patent (that again should not be considered in a vacuum).

**8. Detailed description,** the part of the patent that should give a "person having ordinary skill in the art" the ability to replicate the invention described above without "undue experimentation".

**9. Claims,** this is actually the most important part of the patent, the SFLC actually recommends one read a patent from back to front to make sure you understand what the patent wants before moving on.


> **Who:**,
>
> * [Richard Fontana](http://en.wikipedia.org/wiki/Richard_Fontana) (lawyer, worked on GPLv3, LGPLv3, AGPL, director of OSI),
>
> * [Bradley M. Kuhn](http://en.wikipedia.org/wiki/Bradley_M._Kuhn) (free software activist, president of Software Freedom Conservancy, previously worked for the SFLC and FSF),
>
> * [Eben Moglen](http://en.wikipedia.org/wiki/Eben_Moglen) (law and legal history professor at Columbia University and director-counsel and chairman of the SFLC),
>
> * [Matthew Norwood](https://www.linkedin.com/pub/matt-norwood/5/770/a39) (IP lawyer, previously was counsel at the SFLC),
>
> * [Daniel B. Ravicher](http://www.ravicher.com/) (lawyer and law professor),
>
> * [Karen Sandler](http://en.wikipedia.org/wiki/Karen_Sandler) (executive director of the SFC, former director of the GNOME Foundation, former general counsel at the SFLC),
>
> * [James Vasile](https://twitter.com/jamesvasile) (director of Open Internet Tools Project),
>
> * [Aaron Williamson](https://torekeland.com/about/aaron-williamson) (IP lawyer for Tor Ekeland).
>
> **What:** Chapter 4 of the book *A Legal Issues Primer for Open Source and Free Software Projects* put out by the [Software Freedom Law Center (SFLC).](https://www.softwarefreedom.org/)
>
> **Where:** [available for free on RIT's Business and Legal issues in FOSS course website](http://bizlegfoss-ritigm.rhcloud.com/static/books/foss-primer.pdf)
>
> **When:** Latest edition (1.5.2) published June 2008



## The Good

* There are three major ways to handle patent claims brought against you:

   * Show that you were given the rights to use the patent, probably through a FOSS license (especially the Apache license, which explicitly grants this) or royalty free agreement with the patent holder.

   * Show that you have not infringed on the claimed patent by working your way backwards through the patents claims.

   * Show that the patent is actually invalid and thus not enforcible.


* A good way to understand how to invalidate a patent claim is to understand how it is claimed to be valid in the first place.

> Under patent law, in order for a patent to be valid, the claimed invention must have been *useful*, *reducible to practice*, *novel*, and *non-obvious* to a “person having ordinary skill in the art” at the time that the invention was made.


## The Bad

* I've said this before about this book, but I think anything this theoretical needs to be tied down and motivated with some concrete examples, which I'm sure exist later in the book part III, but from what I see in the syllabus we will not be getting to that section in the near future if at all. Maybe I'll get a chance to review it on my own time and make a post about my findings here.

* The idea that while you are still liable if you didn't know of a patents existence, you are held under a stricter set of rules (up to 3 times the original punishment!) if they prove you violated the patent knowingly. That's completely messed up.

* The concept of patents as a whole is so messed up right now. I'm not a fan of copyright in general, but at least that is an inclusive IP, patents by their nature require a lot of money to back them and basically set up the playing field for corporations only.


## Questions

* I personally don't like some of the requirements brought forward by the Apache license (mainly the state changes clause), but it also seems like the only OSI license that includes a patent grant. If I was concerned about something in a code base being patentable, what are my best options besides the Apache license? Should I take out the parts of the Apache that I don't want (and notify the user that it is a modified license) or add a patent grant to or alongside another permissive license?

* The reason why the Creative Commons Zero dedication with license fallback was rejected by the OSI was because of this clause in the limitation's section:

  > 4. a. No trademark or patent rights held by Affirmer are waived, abandoned, surrendered, licensed or otherwise affected by this document.

  If deleted, this dedication/license seems like it would have been accepted by the OSI, based on the mailing list discussion, is that a good idea to do in practice? What if I added a patent grant like is in the Apache license? Would that fulfill the goals of the question I raised above?

* In the text it says:

  > A patent holder providing code under a FOSS license without an explicit patent license grant, such as GPLv2, would nonetheless probably be held to have granted a license implicitly to recipients of the code, though the scope and coverage of such an implied license would be difficult to establish.

  Has this ever been played out in court? How well has the Apache patent grant worked vs. this "implicit" grant from license without a patent grant (GPL, MIT, etc.)?


## Final Thoughts

Very informative on a topic I initially knew almost nothing about. It both scared and reassured me about the state of patent law in the US. In reality probably next to nothing I write as a developer will be patentable, but just that possibility scares me a lot all the same.

I give it **19/20th's**, just wish it included some examples inline and maybe touched on the international issue a little bit, but this is a big topic and they covered it well in as concise fashion and I respect that.
