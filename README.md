# 121. Vent Then Burn

Part of [AppADay](https://augustineiacopelli.github.io/appaday/) — one app, every day.

## What it does

Type out whatever you need to let go of, then press Release It. Your text is sampled into thousands of tiny particle seed points and rendered on a canvas that swaps in for the textarea. The particles drift upward, wobble, shrink, and shift color from pale ash through ember orange to red as they fade, timed against a synthesized crackle and low ambient tone from the Web Audio API. A short affirming line fades in once the burn settles, then the page resets to a blank textarea a couple seconds later.

## Privacy

Nothing typed here is stored in localStorage, written to a file, or sent to any server. The text only ever exists in memory for the length of the burn animation. Closing or refreshing the tab clears it immediately, same as burning it does.

## Category

Health & Wellness (H)

## Tech

Single self-contained `index.html`. Vanilla HTML, CSS, and JavaScript. Canvas 2D for sampling and particle rendering, Web Audio API for the crackle and drone, no frameworks, no build step, no external assets or network calls.

## Try it

https://augustineiacopelli.github.io/appaday-121-vent-then-burn/
