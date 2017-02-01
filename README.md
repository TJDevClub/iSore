# iSore: how not to make one

As developers, an oft-overlooked aspect of our work is design. After all, isn't
that the job of, well, designers?

Yes. Yes, it is.

However, it's a good idea to take a look at what you can do to instantly go from
a zero to a... more than zero!

Warning: this will be pretty opinionated at some points; after all, design is a
very subjective field. However, I hope the basic information will help you
regardless.

## Why is design important?

Whether you like it or not, people judge the quality of your work by how good it
looks. While you may not need to make it into the next
[Awwwards](http://www.awwwards.com/) winner, there are some simple things to
make your project look nicer.

In addition, design isn't just about making things look good. It's about the
conscious decision on how to help your user do what they want to do with minimal
friction.

## Here is an anti-example:

[http://www.hscitrus.com/](http://www.hscitrus.com/)

I think we all immediately see that this is poorly designed, but what are some
specific problem areas?

Part of knowing how to make something look good is figuring out what doesn't
look good. For example:

   - The solid background color is jarring.
   - The navigation isn't obviously a navigation bar.
   - The Facebook logo isn't consistent with the rest of the text
   - The marquee is just wrong. On so many levels. [Just...
       don't](https://www.w3.org/wiki/HTML/Elements/marquee)
   - No clear hierarchy of information. What should we be looking at?

Ok. That was kind of a trivial example, since a lot of the flaws were pretty
obvious. 

What about this one?

[https://erictseng611.github.io/](https://erictseng611.github.io/)

This is definitely better than H&S Citrus, that's for sure! But it still doesn't
look amazing. It's at this point that you begin to really have to think about
why... After all, you think, it's pretty good...

Well here are a couple of things that Eric maybe could have done better.

   - his name on the top bar is a bit big, which kind of crowds the bar
   - in addition, there are 3 different stroke sizes now in the nav bar...
       always try to foster consistency and minimalism
   - the body text in the about section is cramped. Cranking the line-height up
       to 1.5 would fix this.
   - the prev button displays when there is no previous, and nothing happens
       when it is clicked

## Wow... You're such a harsh grader

Eh... yeah. The thing is, we don't usually think about design. When you see
something that looks nice, take the time to really analyze why. What do you like
about it? Do you like the colors? The font choice? The way the animation plays?
What do you like about the colors? The fact that they contrast or the fact that
they complement each other?

## Ok, well I'm impatient, so I need some tips pronto

Aight. Here are a couple of things you could do to instantly improve the way
your project looks.

   - **Have a padding.** It always looks weird when something is stuck to the very
       edge (unless you do this intentionally... then it's cool). I recommend
       20px as a starter value, and you can tweak it as you go.
   - **Use a line-height of 1.5 (no units).** This will drastically increase
       readability and make your content look less cramped.
   - **Don't use pure black or pure white.** They don't exist in real life, and they
       shouldn't exist in your website. Instead, choose a dark gray for your
       black and a light gray for your white.
   - **Limit your font / color / font-size / etc choices.** More than 2 or 3 looks
       cluttered and chaotic. Instead, use **bold** or *italics* to add some
       variety (but only when you really need to)

## Can't I just use a CSS library like Materialize?

Well, I cannot physically stop you... So, I guess? The thing is, many people
take this as the easy way out, an in doing so, don't put nearly enough thought
into the design, so while Material Design is a wonderful concept, a lot of the
projects that use Materialize or another Material CSS library (and there are a
lotttt) don't look good at all. In fact, I (in my opinion) find the whole cards
with lots of drop shadow and other things with lots of drop shadow theme
becoming a huge faux pas.

So my advice is to not use the libraries, and if you do, read the
[documentation](https://material.io/guidelines/) so that you will understand how
to *actually* use it.
