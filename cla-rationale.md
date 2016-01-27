# CLA Rationale

## Why do this at all?

The point of the CLA signing process is to have a credible record of
a developer stating that they really intend to contribute to an open
source project. Technically speaking, the thing I am aiming for is a
statement from a contributor that _cannot be repudiated_, that is, a statement
that would be a blatant falsehood to later deny.

This is an important step in assuring that an open source project
truly is open source. More specifically, it helps guard against bad actors who contribute to a
project only _apparently_ in good faith, and then later make trouble
by claiming they weren't really contributing under the project's open
source license. For some projects "trouble" has historically come, for
example, in the form of patent lawsuits.

[I want](https://github.com/Sciss) to do my part to guard against this
potential trouble, and I believe so should you. I am trying to
make the agreement and process nearly-transparent,
natural to do for people already active in open source, and (I hope)
extremely understandable.

Here are some relevant links:

* [Wikipedia](https://en.wikipedia.org/wiki/Contributor_License_Agreement)
* [Why CLAs?](https://www.clahub.com/pages/why_cla)

## Why do it this way?

In the pre-digital era, this sort of agreement might have been collected in
paper form. You might have been asked to sign a piece of paper and
then send it into an organisation (perhaps physically or as a fax),
which would in turn keep it in a real filing cabinet.

One wonderful thing about the digital world is that we can
achieve the necessary verification without having to have a
physical document. In the case of the CLA, I bootstrap this ability
off of the infrastructure provided by GitHub: More specifically, I
treat GitHub as a neutral third party to witness the transactions
between a would-be contributor and myself. GitHub
ends up acting sort of like a notary, in that its records of the
actions&mdash;such as in particular the pull requests&mdash;of
people using it can be taken as authoritative and unbiased.

So, when a contributor forks this project, commits a change indicating
agreement to the CLA, and files a pull request back with this project,
GitHub knows that all that happened, knows when it happened, and knows
the identity of the entity taking all that action. Should there ever
be a dispute about whether any of that took place, it's not just
he-said she-said, because GitHub has unbiased information which it can
use to shed light on the situation.

In addition to what's in the pull request, I need to have a little
bit of extra information, which can help verify that you are who you
say you are, should the need arise. In particular, I need to have
some information that can link you to your contributions, even if you
later delete your GitHub account. Since people rightly desire privacy
about their addresses and phone numbers, I don't ask for this
information to be made public in the pull request, instead going for a
traditional email. I promise never to use this information for
any purpose other than resolving authorship disputes.

The upshot is that filing a pull request containing a statement of
agreement to the CLA, along with the supplementary email, is close
enough to having submitted a signed physical document saying the same
things. That is, this tactic is a workable solution to the problem. And
since fits in naturally with how actual contributions get made, what
we do here ends up being the least-intrusive way of getting the
assurance that we all need to operate in safety.
