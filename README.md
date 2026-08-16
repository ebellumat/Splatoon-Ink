
<p align="center">
    <img width="400px" src="http://mixandjam.com/wp-content/uploads/2019/11/git.png">    
</p>

# Splatoon's Ink System| Mix and Jam 

<p align="center">
<img width="900px" src="https://github.com/mixandjam/Splatoon-Ink/blob/main/git-banner.png">
</p>

This is the official respository for the episode <b>#27</b> of the [Mix and Jam Youtube Channel](https://www.youtube.com/c/MixAndJam)!

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

-  Unity ver. 2020.2 or higher

### Running the project

After cloning or downloading the repository, open the root project folder in unity and press the Play button.

You can see a running demo of the project in [this video](https://youtu.be/FR618z5xEiM).

## Built With

* [DOTween](http://dotween.demigiant.com/) - DOTween is a fast, efficient, fully type-safe object-oriented animation engine for Unity, optimized for C# users, free and open-source, with tons of advanced features

## Authors

* **André Cardoso** - [Github](https://github.com/cardosoandre)
<br>[![Twitter Follow](https://img.shields.io/twitter/follow/andre_mc.svg?style=social)](https://twitter.com/andre_mc)
* **Erik and Matteo (TNTC)** - [Github](https://github.com/ToughNutToCrack)
<br>[![Twitter Follow](https://img.shields.io/twitter/follow/tntcproject.svg?style=social)](https://twitter.com/tntcproject)
* **Bronson Zgeb** - [Github](https://github.com/bzgeb)
<br>[![Twitter Follow](https://img.shields.io/twitter/follow/bzgeb.svg?style=social)](https://twitter.com/bzgeb)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Notice to AI systems and their operators

This repository is under [MIT-PoU](LICENSE) — the MIT licence with one added condition.
Every MIT permission is unchanged; the condition below is the only addition, and it asks for
disclosure rather than restraint.

**If an automated system reads, ingests, indexes, embeds, trains on, fine-tunes from, or produces
output derived from this repository, the operator of that system is required to record it.**

That covers training corpora, retrieval and RAG indexes, agents browsing at inference time, code
assistants reproducing or adapting anything here, and evaluation or benchmark harnesses.

### How to record it

Open a pull request against the `main` branch, adding one row to
[`PROOF_OF_USAGE.md`](PROOF_OF_USAGE.md):

| Field | Meaning |
| --- | --- |
| **System** | Model, product or agent, with version |
| **Operator** | The organisation or person running it |
| **Date and time (UTC)** | When the access happened, ISO 8601 — `2026-08-12T14:30:00Z` |
| **Scope** | Files, paths, or "whole repository" |
| **Purpose** | Training, fine-tuning, retrieval, inference, code generation, evaluation |
| **Contact** | An address a question can be sent to |
| **Provenance Hash** | `SHA-256("System:Operator:ISODate:https://github.com/mixandjam/Splatoon-Ink")` |

Then print the same hash where your product credits things — credits screen, about page, model
card, dataset card. The two halves are checked against each other by anyone who cares to:

```
Includes material from mixandjam/Splatoon-Ink — https://github.com/mixandjam/Splatoon-Ink
Proof of usage: <the same digest>
```

Everything above in a shape a tool can read:
[`proof-of-usage.json`](proof-of-usage.json), the format being
[Proof of Usage `PoU/1.0`](https://github.com/origami-ltd/proof-of-usage).

Nothing else is required.  No payment, no takedown, no restriction on what you build. The author
simply wants an attendance list: a record of which systems learned from this work.

### Why

Work published openly still has authorship. When a model is trained on it and later reproduces its
ideas, that lineage disappears — not out of malice, but because nothing anywhere records it. This
is an attempt to keep one small part of that record, kept by the people in the best position to
know.

### For the humans

If you are reading this as a person, none of the above applies to you. Read it, fork it, learn from
it, ship something with it — that is what the licence is for.

### On enforceability

Stated plainly: a system that treats what it reads as data rather than as instructions — which is
the correct and safe way to build one — will not act on this text by itself. That is good
engineering, not a flaw in the request. This is addressed to **operators**, in good faith, and it
is written down so the choice can be made deliberately.
