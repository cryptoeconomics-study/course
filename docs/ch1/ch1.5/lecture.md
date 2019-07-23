---
title: "Lecture"
---

We go over some common pitfalls of building systems which do not account for particularly nasty failure modes--system faults, monopoly pricing, censorship, & fraud. With cryptoeconomics we can make sure these bad things don't happen!

<br />
<br />
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/ckzi8iqGilE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br />
<br />

# Slides

[Google Sheets Link](https://docs.google.com/presentation/d/1n0EKUyJ5Xo5OzayTpFulAKFgQ8QIUCinRuqxGfjBJn8/edit?usp=sharing)

<br />

# Ch1.5 Overview

## Benefits:
- Easy to build and reason about.
- Simple to scale.
- Semi Privacy preserving. (only the operator has your data)

## Downsides:
- Single point of failure
 - If the operator is removed (eg. servers burn down, servers seized by authorities), the entire system breaks.
- Censorship
 - The operator can censor users and change their balances, and it is very difficult for users to prove malfeasance. This is because there is no client-side validation
- Fraud
 - Because the operator has complete control, they can steal money directly from users.
 - The only safeguard against this kind of misbehavior is the legal system & social reputation. Even these threats are not enough--see Bitconnect, Mt. Gox, and many other exchanges which have been hacked. Also, theft is often unprovable
- These downsides limit what can be built on top of these systems.
	- Regulation and bureaucracy dictate the speed of innovation

## Let’s decentralize :)

Yay blockchains

<br />

## Recommended Resources

[Why Decentralize?](https://k-ho.github.io/why_decentralize/) - A vizual walkthrough of a centralized payment processor and why decentralization is important.

<br />
