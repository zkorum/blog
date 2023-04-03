# What is identity?

## A philosophical question

Trying to find ways to prove you're unique on the web is a daunting task.
It may look easy from the outside, but if you dive into it you'll quickly be deceived.
You'll get into the rabbit hole of wondering: what is defining who we are?

After thinking long enough about it, I realized it's not obvious that our identity can be totally _self-owned_.

I can hear you saying: "I think so I am I!" Yes, but are you sure you are unique? Are you the same person as you were 6 months ago? And how do you prove it? And I can hear you reply: "That's an absurd question! I have the same body and mind!"

The body:
- every 6 months, most cells in your body regenerates entirely. Technically, you're an entirely new being.
- what about biometrics? Let's say your iris or your fingerprint. That's unique! OK that's a fair point, it identifies your body uniquely. But what if you lose your hands and your eyes? Do you not exist anymore? What about your DNA? Isn't that unique? Well, yeah it is - though it mutates too, it is just slow to do so. What if you have a clone, or simply a twin? Does that mean you're not unique anymore?

The mind:
- I'll leave aside the question as to whether or not your mind can be distinguished from your body
- "hey! but I have memories of myself in the past! that guy was me!" Really? Do you have many? Do you remember you as a baby or do you even remember many things about you just 3 months ago? How can you be sure that those memories were correct and it's not your body that's tricking you? What if you have Alzheimer's disease? Does that mean you are no longer the same person? 
- "No of course! It is the objective reality. Others can keep track of me. There are photos, videos, proofs". OK so that's not self-sovereign anymore. Your identity is conditioned to what others, and the world around you show you about yourself! 

My conclusion to these thoughts is that:
- identity is a fundamentally social construct
- it cannot be totally self-defined
- this is one of the traditional role of governments

To go further (French language): https://www.youtube.com/watch?v=EZmvdkNjev8

## So what's the solution for digital identity?

### Biometrics

Biometrics data should not be used for digital identification because:
- it is a huge privacy hole. Whenever someone can associate biometrics with photos/videos and other private info, it's done. You can't change your biometrics.
- people can use it to impersonate you. Biometrics data, once stolen can be used to authenticate instead of you. Again, you can't change the biometrics - so you're done.
- what about twins?
- biometrics data CAN change. What if I lose my hands, or my eyes? Or to I get back access to my accounts? (Though I suppose that's gonna be the least of my concern if it happens)

Some background: https://twitter.com/Snowden/status/1451990496537088000

### Proof-of-humanity - an interesting experiment

[Proof of humanity](https://proofofhumanity.id/) is probably the most interesting of all the experiments that try to get rid of the problems with the "traditional" human organizations.

It is an idealistic but legitimate goal.

The solution is not yet battle-tested and currently limited by the price it takes to create a new profile, among other reasons.

### Traditional human organizations: the Issuer-Holder-Verifier pattern

Typically governments, or companies, private clubs, human organizations in general (the "Issuer"), identify their members themselves, physically, then give them some sort of credentials with a unique number to each members ("the Holder"), and keep the info in a database.

The problem with human organizations is that they can easily be flawed.

Though crypto-economics and financial incentive can help (ex: Proof-of-humanity experiment), I think the problem of trust and governance can never be entirely solved using technology. It is a fundamental part of our humanity. The only way to solve it would be to transform us physically - but we would not be humans anymore.

### What does it have to do with Privency?

At Privency, I try to redefine digital identity on the web:
- find ways to uniquely identify humans is a daunting task
- doing so in a privacy-preserving and decentralized way is even more difficult

While projects such as Proof-of-humanity are very interesting, they are also very ambitious and idealistic. With Privency, I want to stay pragmatic. My goal is not to solve the governance problem in the world. My goal is to provide tools to existing organizations for them to allow their users and only their users to uniquely register and login, in an anonymous way.

That is why Privency focuses on the Issuer-Holder-Verifier pattern.
