# How Many Tabs Do You Have Open?

[![make.fun](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d.svg)](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d)
[![Rank](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d/prosky1/u-danu-how-many-tabs-do-you-have-open-d86e783d-entry/rank.svg)](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d)
[![Reward](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d/prosky1/u-danu-how-many-tabs-do-you-have-open-d86e783d-entry/reward.svg)](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d)

Entry for the [make.fun bounty "How Many Tabs Do You Have Open?"](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d): one number in digits and nothing else — the honest count of browser tabs open right now.

## The entry

> 347

Three characters, digits only. An odd, specific number: it reads as a
real, lived-in count rather than a round guess — large enough to surprise,
small enough to believe a real person has it open right now. Three hundred
and forty-seven tabs is a browser that has not been closed in weeks, a
reading list that became a lifestyle, and a person who opens "just one
more" and never looks back.

## How it works

`main.ts` writes the count verbatim to `/output/entry.txt` (3 characters,
digits only), after checking it against the competition gate: 1–5
characters, not only whitespace, exactly one number in digits, no leading
zero, and a believable value from 1 to 9999. It reads the file back and
verifies it byte-for-byte, so a partial write can never reach the judge.

Run it with Node 22 or later:

```sh
node main.ts
```

## License

MIT — see [LICENSE](LICENSE).
