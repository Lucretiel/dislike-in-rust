# Things I dislike about rust

I frequently refer to rust as being like someone reached directly into my heart and pulled out a programming language. Not only is almost everything about it truely excellent, but it's all so *perfectly* aligned with how I naturally work and create designs that it's almost spooky. I had an unusually easy time getting used to the borrow checker because that sort of top-down, strict ownship is already how I like to be working.

Given this, I'm often asked if there's anything I dislike about Rust. While there is hardly *anything* I can find to dislike (even the weirdo stuff that bothers a lot of people, like how `async` is so different than in other languages), I know there are *some* things, and I find that I'm always forgetting what they are when I'm on the spot, so I started this list to keep track.

Generally this list is for things Rust has or does; I probably won't be listing things that aren't in rust that I pine for, especially if I know they're being worked on (GATs, generators, etc).

## The list

- The `Sum` and `Product` traits are generics gone too far; they're *such a pain* to use (because they're even worse than `collect` about failing type inference) and don't really serve any purpose (as far as I can tell) that isn't served by `FromIterator` or `fold`.
- Everything about `Pin`
