# Toroid Money

How Toroid makes money. The company plan is `REVENUE.md` in the Code root; the ledger is `GTM.md`.

## Price and rail

$0.99 upfront on the App Store (ASC 6806324937), iPhone and Mac. Apple keeps 15%, so each sale pays about $0.84. The web version at toroid.jaybulb.com stays free.

## What is actually sold

The Game of Life on a wrapping grid, in the native app and the watch companion. The rules are Conway's and free to use. Nothing sold is someone else's content.

## Who pays and why

A curious person who wants a finished toy for the Game of Life, bought once. There is no account and no network, and the app is small and done.

## Cost to serve

No paid API, no accounts, no network and no storage. Hosting is Cloudflare Pages, and the `/api` and `/mcp` functions make no paid call.

## Where we are

- 2026-09-20: price set to $0.99.
- Repo notes: renamed from Conway to Toroid. The bundle ID and the Pages project keep the old name.
- Revenue: no verified number (the App Store Connect key cannot read sales yet).

## Role in the company plan

Catalogue. GTM.md lists it that way. It serves Stage 0 as one more dollar app that tests whether strangers pay. Under Stage 2 it earns a place on the grid or is retired.

## Next

Once the Sales role is on the App Store Connect key, read the first month of Toroid sales. No change until then.

## Million, billion, trillion

**A million.** Toroid is the finished toy people buy once for the Game of Life, and it sells on the strength of its one job.

**A billion.** Toroid is one of the small games that come with every Jaybulb device.

**A trillion.** Toroid is one line on a long app list, which is the right size for a toy.

## Change it

`asc pricing schedule create --app 6806324937 --price 0.99 --base-territory USA --start-date YYYY-MM-DD`. Swap `--price 0.99` for `--free` to revert. No build, no review. Only with Joshua's yes in chat.

Anyone who got Toroid while it was free keeps it free.

*ASC 6806324937. Verified 2026-11-02.*
