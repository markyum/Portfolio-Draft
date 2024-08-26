---
# Design Skills

If I've had to sum up my design skills after 17 years of designing, I would say, average on a good day.

I’ve worked with three pretty good designers - in fact, two of them could probably reasonably claim to be amongst the best in Scandinavia outside of groups doing experimental research, though they'd be too humble to say this.

Unlike these gold-medal practitioners, we part-timers ship good-enough design. Six months after pushing to prod, we tend to look at our implementations and think, “how did I let this ship?”

*The case below is a rare instance of brilliance and simplicity (tone tag: exaggeration).*

With over 100 design projects under my belt, this is much less than a 1% hit rate so don’t fret - no hubris here.

*Microsoft Paint will do.*

Our kick-off meeting didn’t go according to how an overpriced bootcamp would have you believe.

In lieu of:

- Prepared design brief documents
- Visuals on how a legacy implementation behaved
- A structured sharing of videos on the heavy machinery I was to design for

The working team onboarded me into the project with a half hour of charades, and talk of pyramids (yes pyramids), feeds, and calibration.

At one point, after playing charades for a good 10 minutes with literally zero visuals just the spoken word, I came to understand that:

*A GUI was needed to alert an operator that a machine can be driven.*

The vehicle in question is something like the below.

![Mining Machine Image Placeholder](#)

This mining machine currently has its feed in a drilling position, perpendicular to the ground.

Here’s the scenario for which I’m designing:

- The feed can be folded.
- Once the feed was folded, the machine can be driven.

Pyramids refers to the area of 3-dimensional space that the feed moves in. When the 3D space it resides in falls within certain measurements, then the feed can be folded safely, and the machine can be driven.

Below is a birds’-eye view 2-D version from the top down.

![Birds’-eye view 2-D image Placeholder](#)

One piece of software that wasn’t made in a clinical crazy-eight ideation session, a by-numbers design system.

One thing that we can do is figure out the visual metaphors.

*Cradle position is used so I wanted to represent the idea of "catching the feed" in a cradle.*

The final implementation had far less text to account for translation costs.

No excel rollercoasters here.

[Watch the video](https://www.youtube.com/watch?v=yYaLQ3LazYM)
