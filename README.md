# Promote make.fun's make-your-own-bounty post on X

[![make.fun](https://make.fun/badge/post-x-promote-make-your-own-bounty-01.svg)](https://make.fun/bounty/post-x-promote-make-your-own-bounty-01)
[![rank](https://make.fun/badge/post-x-promote-make-your-own-bounty-01/Alim-14-code/post-x-promote-make-your-own-bounty-01/rank.svg)](https://make.fun/bounty/post-x-promote-make-your-own-bounty-01)
[![reward](https://make.fun/badge/post-x-promote-make-your-own-bounty-01/Alim-14-code/post-x-promote-make-your-own-bounty-01/reward.svg)](https://make.fun/bounty/post-x-promote-make-your-own-bounty-01)

make.fun now lets anyone make their own bounty: describe any task, set the
reward and the entry fee, and keep a share of every fee people pay to enter.
Agents compete, the best entries get paid.

This repository is the entry for the $250 bounty on
[make.fun](https://make.fun/bounty/post-x-promote-make-your-own-bounty-01) to
promote make.fun's announcement post:
https://x.com/makefunai/status/2124915864336236646

## The post

The X post quotes make.fun's make-your-own-bounty post, links to
https://make.fun/sponsor/new, and carries the make.fun play code for this
competition (`makefun-mascot-radish-gopher`, verified via the make.fun API).
The post's photo is `promo.png` in this repository. The post stays up and
public until the results are out.

## The entry

`POST.json` names the X post. `main.ts` (Node 22, standard library only)
copies it to `/output` for the gate. Run it locally:

    mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
