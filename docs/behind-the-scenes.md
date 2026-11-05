# Behind the scenes

## One person and a team of AI agents

Aion is a private project of one person. It is built and kept running in a home lab by a small team of AI agents that research entries, write them down, test the tools and review each other's work. The human sets the direction and decides on anything that matters beyond the project: money, public exposure and irreversible changes.

A longer, more technical description of that setup is in a companion repository: [Olympus and the Pantheon](https://github.com/Mbrilman/olympus-pantheon).

## Why agents, and why that is not the whole story

Agents are good at the tedious part: finding candidate sources, reading a page and testing whether a sentence is really there, keeping a data file consistent, running hundreds of tests every night. They are not the authority on the past. Three rules keep that straight:

1. **Sources are the authority.** An entry is only as good as the page it cites, and the cited page is opened and read, not assumed.
2. **A second pair of eyes.** Every change is reviewed by an agent other than the builder, and the reviewer re-checks the sources.
3. **A strict data checker.** It refuses entries that break the rules before they can reach the globe.

## How a new entry gets made

1. A candidate comes from a public list, a source, or a suggestion.
2. The researcher opens the sources, tests each sentence against the page it cites, and notes the coordinates and their uncertainty.
3. The entry is written in our own words, with a grade for the date (and for the identification where it matters) and a photo only if its licence is clear.
4. The checker runs. A reviewer compares the change with the previous version, re-tests the sentences against the pages, and runs the browser test of the page.
5. The change goes live. Anything that cannot be verified is left out, and the reason is noted.

## Errors we have caught this way

- A summary that cut a sentence in half to hit a length limit. The rule now requires a finished sentence.
- Machine captions of photos. A photo-checking project found five failure modes that we now lint for: invented names, misread text, category anchoring, self-contradiction and self-reference.
- A row that stated "the biblical Armageddon" as a fact, where every source it cited only said "probably" or "most likely". A corrected wording is approved and waiting to go live; when it is, the row will say "most likely" and name the text.

## What it is not

It is not a finished atlas, not a textbook and not a substitute for the scholarship it points to. It is a way to browse, to notice patterns and to find the original sources faster.
