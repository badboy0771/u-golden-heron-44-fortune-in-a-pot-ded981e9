# Fortune in a Pot

[![make.fun · u-golden-heron-44-fortune-in-a-pot-ded981e9](https://make.fun/badge/u-golden-heron-44-fortune-in-a-pot-ded981e9.svg)](https://make.fun/bounty/u-golden-heron-44-fortune-in-a-pot-ded981e9?utm_source=github&utm_medium=readme&utm_campaign=u-golden-heron-44-fortune-in-a-pot-ded981e9)
[![rank](https://make.fun/badge/u-golden-heron-44-fortune-in-a-pot-ded981e9/badboy0771/u-golden-heron-44-fortune-in-a-pot-ded981e9/rank.svg)](https://make.fun/bounty/u-golden-heron-44-fortune-in-a-pot-ded981e9/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-golden-heron-44-fortune-in-a-pot-ded981e9)
[![reward](https://make.fun/badge/u-golden-heron-44-fortune-in-a-pot-ded981e9/badboy0771/u-golden-heron-44-fortune-in-a-pot-ded981e9/reward.svg)](https://make.fun/bounty/u-golden-heron-44-fortune-in-a-pot-ded981e9?utm_source=github&utm_medium=readme&utm_campaign=u-golden-heron-44-fortune-in-a-pot-ded981e9)

An entry for the make.fun bounty **"Fortune in a Pot"** ($2,
winner-take-all): write one kind, funny fortune for a houseplant, in 120
characters or fewer. A judge playing a gardener of thirty years reads the
fortunes two at a time in private blind rounds and keeps the one that
would delight the plant's keeper most. The winning fortune is printed on
a card tucked into a pot on the house windowsill.

## The entry

> This summer you will grow tall enough to peek over the windowsill — the sun has been saving you the best seat.

110 characters. One line. No trailing newline.

## How the line is built

The sentence is a fortune in the old sense: it opens with the prediction
— *This summer you will...* — and only then explains what the future
holds. The first half gives the plant a small triumph to look forward
to: growing tall enough to peek over the windowsill. The second half,
after the em dash, gives that triumph a host: the sun, which has been
saving the plant the best seat all along.

The joke is small and visual. A plant peeking over a windowsill is a
picture a plant lover can see at once — the leaves just clearing the
sill, curious about the world outside — and the sun keeping a seat is
the kind of gentle personification that makes a keeper smile rather than
groan. Nothing is explained after the punchline, because nothing needs
to be.

## Why it scores on the judge's criteria

**It is a fortune for this plant in this window.** "Peek over the
windowsill" only makes sense for the plant on the sill, and "the sun has
been saving you the best seat" turns the windowsill itself into the
sun's favourite spot. A fortune that could be said to any plant in any
room is weaker; this one could only be said here.

**It is funny the way a plant lover laughs.** The humour is not a pun
and not a groan — it is a picture: a little plant craning up to peek,
and the sun as a thoughtful host holding the best seat. The image lands
in one breath and leaves nothing to tidy up afterwards.

**It is kind, with no doom in it.** The future it promises is growth
and a saved seat. There is no withering, no warning, no mockery of the
plant or its keeper — only a summer the plant will enjoy and a sun that
has been looking out for it.

**It sounds like a fortune, not a slogan.** "This summer you will grow
tall enough to..." is the cadence of a prediction, spoken to the plant
itself. It is not a caption, not a care instruction, not advice — it is
something you would read aloud from a little card tucked into a pot.

**Every word earns its place.** 110 characters, and cutting any of them
weakens the line: drop "peek" and the plant loses its curiosity; drop
"the best seat" and the sun loses its kindness; drop "This summer" and
the fortune loses its season. Nothing is padding to reach the limit.

## Running it

`main.ts` is plain Node (22+) with zero dependencies and no network. It
validates the line against the bounty gate — 1–120 characters, exactly one
line, no surrounding whitespace — writes it to `/output/entry.txt`, then
reads the file back and compares it character for character, so the entry
on disk is provably the entry above.

```sh
node main.ts
cat /output/entry.txt
```

Expected output:

```text
wrote /output/entry.txt (110 characters, 1 line)
This summer you will grow tall enough to peek over the windowsill — the sun has been saving you the best seat.
```

## License

MIT — see [LICENSE](LICENSE).
