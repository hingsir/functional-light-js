# Functional-Light JavaScript
# Preface

A monad is just a monoid in the category of endofunctors.

Did I just lose you? Don't worry, I'd be lost, too! All those terms that only mean something to the already-initiated in Functional Programming&trade; (FP) are just jumbled nonsense to many of the rest of us.

This book is not going to teach you what those words mean. If that's what you're looking for, keep looking. In fact, there's already plenty of great books that teach FP the *right way*, from the top-down. Those words have important meanings and if you formally study FP in-depth, you'll absolutely want to get familiar with them.

But this book is going to approach the topic quite differently. I'm going to present fundamental FP concepts from the ground-up, with as few special or non-intuitive terms as possible. We'll try to take a practical approach to each principle rather than a purely academic angle.

Sadly, I am not a card-carrying member of the FP cool kids club. I've never been formally taught anything about FP. And though I have a CS academic background and I was decent at math, mathematical notation is not how my brain understands programming. I have never written a line of Scheme, Clojure, or Haskell. I'm not an old-school Lisp'r.

I *have* attended countless conference talks about FP, each one with the desperate clinging hope that finally, *this time*, would be the time I understood what this whole functional programming mysticism is all about. And each time, I came away frustrated and reminded that those terms got all mixed up in my head and I had no idea if or what I learned. Maybe I learned things. But I couldn't figure out what those things were, for the longest time.

But little by little, across those various exposures, I teased out bits and pieces of important concepts that seem to come all too naturally to the formal FPer. I learned them slowly and I learned them pragmatically and experientially, not academically with appropriate terminology.

Maybe you're like me; I heard terms like "map-reduce" around "big data" for years with no real idea what they were. And eventually I learned what the `map(..)` function did -- all long before I had any idea that list operations were a cornerstone of the FPer path and what makes them so important.

## Mission

Speaking of importance, why is it so important for you to learn functional programming?

I've come to believe something very deeply in recent years, so much so you could *almost* call it a religious belief. I believe that programming is fundamentally about humans, not about code. I believe that code is first and foremost a means of human communication, and only as a *side effect* (self-referential chuckle) does it instruct the computer.

The way I see it, functional programming is at its heart about using patterns in your code that are well-known, understandable, *and* proven to drive away the mistakes that make code harder to understand. In that view, FP -- or, ahem, FlP! -- might be one of the most important collections of tools any developer could acquire.

The formal FPer will often assert that the *real value* of FP is in using it essentially 100%; that it's an all-or-nothing proposition. The notion is that if you use FP in one part of your program but not in another, the whole program is polluted by the non-FP stuff and therefore suffers enough that the FP was probably not worth it.

I'll say unequivocally: I think that's nonsense. That's as silly to me as suggesting that this book is only good if I use perfect active voice throughout, but if I use any passive voice, it brings down the entire book's quality. Nonsense.

The better I am at writing in a clear, consistent voice, the better this book experience will be for you. But I'm not a perfect 100% author. Some parts will be better written than others. The parts where I can improve are not going to invalidate the other parts of this book which are already good.

And so it goes with our code, I assert. I believe the more you can apply these principles to more parts of your code, the better your code will be. Use them well 25% of the time, and you'll get 25% benefit. Use them 80% of the time, and you'll see even more benefit.

With perhaps a few exceptions, I don't think you'll find many absolutes in this text. We'll instead talk about aspirations, goals, principles to strive for. We'll talk about balance and pragmatism and trade-offs.

Welcome to this journey into the most useful and practical foundations of FP. We have plenty to learn!
