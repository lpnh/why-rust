# Ecosystem

One thing that new Rust developers will face sooner rather than later is
the absence of some common utilities typically found in other languages'
standard libraries. There are [very good
reasons](https://internals.rust-lang.org/t/what-should-go-into-the-standard-library/2158)
fore Rust to be this way. This "batteries included" approach, although seemingly
ergonomic at first glance, can have some
[downsides](https://lwn.net/Articles/790677/) in the long run.

The fact is, the lean std library is supported by a rich ecosystem that can be
easily accessed and incorporated with *Cargo*. This shifts the problem from "why
isn't *x* available" to "which of all these *x* options should I choose?!".

This was a real challenge for me in the beginning. I spent a considerable amount
of time searching and comparing. To be honest, I think this additional step,
where we are expected to pick and choose our own tools, contributed
significantly to my learning journey and personal development. I see it as an
opportunity to discover more about the ecosystem and to delve deeper into the
tools we use.

However, the goal here is to make things easier for you. So, I will share two
unofficial "curators" that have explored the vast sea of <crates.io> and offer
us some good starting points.

The first one, and perhaps the more beginner-friendly, is the [Blessed
guide](https://blessed.rs/crates).

The second, which lacks the "handmade" aspect but offers far more options and
criteria, is [Lib.rs](https://lib.rs/).

Enjoy!
