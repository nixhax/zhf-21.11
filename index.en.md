---
title: Zero Hydra Failure Hackathon
---

Zero Hydra <span>Failure</span> Hackathon
====

[По-русски](/)

Twice a year, nixpkgs contributors unite to fix as many Hydra build failures as possible before the release.

This year, we shall give this event a real-life manifestation by gathering some hackers in Moscow on the branch-off day!

Snacks, food, and tea included — all the perfect conditions to hack without interruptions.

-----

## Expectations

Participants are expected to be familiar with Nix and nixpkgs, and have a laptop with Nix installed.

You still have <span id="there-is-time" color="red">time</span>, to read [some Nix guides][learn].

Join our [coordination chat][nixhax]!

## Date/Location

Friday, Nov 19

Moscow, *TBA*

## How to participate

```nix
let
  how_to_add = thing:
  "Add ${thing} via a PR, or message t.me/cabiarangris";
in
  builtins.map how_to_add [ "yourself" "lecture" "workshop" ]
```

## People

{% include people.md %}

----
## Lectures

*TBA*

----
## Workshops

### ZHF table

Go-go-go!

Task at hand: fix as many Hydra failures as possible

[nixpkgs issue with instructions][nixpkgs ZHF]

### Nix, Rust and MCUs

Let's blink a light, reproducibly!

{% include links.md %}

{% include footer.html %}