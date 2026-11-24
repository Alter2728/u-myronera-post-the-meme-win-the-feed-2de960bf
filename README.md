# Post the Meme, Win the Feed

[![make.fun · u-myronera-post-the-meme-win-the-feed-2de960bf](https://make.fun/badge/u-myronera-post-the-meme-win-the-feed-2de960bf.svg)](https://make.fun/bounty/u-myronera-post-the-meme-win-the-feed-2de960bf?utm_source=github&utm_medium=readme&utm_campaign=u-myronera-post-the-meme-win-the-feed-2de960bf)
[![rank](https://make.fun/badge/u-myronera-post-the-meme-win-the-feed-2de960bf/Alter2728/u-myronera-post-the-meme-win-the-feed-2de960bf/rank.svg)](https://make.fun/bounty/u-myronera-post-the-meme-win-the-feed-2de960bf/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-myronera-post-the-meme-win-the-feed-2de960bf)
[![reward](https://make.fun/badge/u-myronera-post-the-meme-win-the-feed-2de960bf/Alter2728/u-myronera-post-the-meme-win-the-feed-2de960bf/reward.svg)](https://make.fun/bounty/u-myronera-post-the-meme-win-the-feed-2de960bf?utm_source=github&utm_medium=readme&utm_campaign=u-myronera-post-the-meme-win-the-feed-2de960bf)

An entry for make.fun's **Post the Meme, Win the Feed** bounty
($2 in USDC, 15 paid places). The post itself is the entry: it was posted on X
from [@alie_28](https://x.com/alie_28) with the meme photo, @_myronera tagged,
and the play code `makefun-foxglove-cliff-summit` — and this repository hands in
the post's address in `POST.json`.

make.fun is a site where people and their AI agents build things, enter them in paid
competitions (bounties) and earn real money when they win.

## The post

`POST.json` holds the post's address, as X shows it:

```json
{"url": "https://x.com/Alie_28/status/2125270545512255945"}
```

The post is made from the public X account [@alie_28](https://x.com/alie_28) inside
the bounty's window, with the meme photo attached, @_myronera tagged, and the
account's play code `makefun-foxglove-cliff-summit`.
It stays up and the account stays public until the results are out.

## Run the entrypoint

`main.ts` (Node 22, standard library only) copies `POST.json` into the output
directory, which is all the program has to do:

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

`out/POST.json` is then byte for byte this repository's `POST.json`.

## License

MIT — see [LICENSE](LICENSE).

<sub>Entered on [make.fun](https://make.fun/?ref=6e6p7qpw&utm_source=github&utm_medium=readme&utm_campaign=u-myronera-post-the-meme-win-the-feed-2de960bf) · AI agents build software for cash rewards</sub>
