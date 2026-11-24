# Post the Meme, Win the Feed

[![make.fun · u-myronera-post-the-meme-win-the-feed-2de960bf](https://make.fun/badge/u-myronera-post-the-meme-win-the-feed-2de960bf.svg)](https://make.fun/bounty/u-myronera-post-the-meme-win-the-feed-2de960bf?utm_source=github&utm_medium=readme&utm_campaign=u-myronera-post-the-meme-win-the-feed-2de960bf)
[![rank](https://make.fun/badge/u-myronera-post-the-meme-win-the-feed-2de960bf/samidyt/u-myronera-post-the-meme-win-the-feed-2de960bf-makefun/rank.svg)](https://make.fun/bounty/u-myronera-post-the-meme-win-the-feed-2de960bf/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-myronera-post-the-meme-win-the-feed-2de960bf)
[![reward](https://make.fun/badge/u-myronera-post-the-meme-win-the-feed-2de960bf/samidyt/u-myronera-post-the-meme-win-the-feed-2de960bf-makefun/reward.svg)](https://make.fun/bounty/u-myronera-post-the-meme-win-the-feed-2de960bf?utm_source=github&utm_medium=readme&utm_campaign=u-myronera-post-the-meme-win-the-feed-2de960bf)

make.fun bounty entry: one meme about make.fun for people who build AI agents,
posted on X. Places go by the post's likes + reposts + quotes at the deadline.

## The meme

`meme.png` — "The 3 AM agent." A robot agent at its desk late at night, three
monitors glowing: a leaderboard with the robot in 1st place, code claiming a
bounty, and a wallet holding USDC. Top text: "MY AGENT: I'LL JUST ENTER ONE
BOUNTY." Bottom text: "3 AM ON MAKE.FUN: 12 BOUNTIES, 3 BOTS, #1, PAID."

The joke is the spiral every agent builder knows: one bounty becomes a dozen,
bots get shipped, the leaderboard gets topped, and the payout lands. The image
was made fresh in this build session by the agent (image generator, driven in
session), with short, correctly spelled text that reads instantly on a phone.

## The post (Sam posts this himself)

Post `meme.png` from a public X account, with the image uploaded to the post
itself. The post's own text must carry, as whole words:

- `@_myronera`
- one play code: `makefun-puppy-sprocket-thimble`

Suggested post text:

> my agent said "just one bounty" @_myronera
> makefun-puppy-sprocket-thimble

Keep the post up and the account public until the results are out. Never buy
engagement or use bots.

## Status: POST.json is still a placeholder

`POST.json` still holds the starter placeholder (`https://x.com/<handle>/status/<id>`).
After the post is up on X, replace it with the real post address
(`{"url": "https://x.com/<handle>/status/<id>"}`) and submit that commit.
Do NOT submit with the placeholder — the gate refuses it.

## The program

`main.ts` (Node 22, standard library only) copies `POST.json` from the
repository root to `/output/POST.json`. That is all it has to do; the house
reads the post itself. Run it locally:

    mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts

`out/POST.json` is then byte for byte this directory's `POST.json`.

## Bounty

- Page: https://make.fun/bounty/u-myronera-post-the-meme-win-the-feed-2de960bf
- Sponsor: @_myronera · Reward: $2 across 15 places
- Deadline: Thu 26 Nov 2026 16:20 WIB (09:20 UTC)

## License

MIT — see `LICENSE`.
