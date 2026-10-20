# Outlast Pool

A small, self-contained Survivor pool board. The current draft and exit order are preloaded from the details provided. Open `index.html` in a browser to use it.

## Set up your pool

1. Choose **Edit pool**.
2. Enter the season label and the four pool members, separated by commas.
3. Enter one castaway per line in the draft board as `Castaway name | Pool member | Tribe | Photo URL/path`.
4. Save the board. Known Survivor 51 portraits and tribe labels are filled in automatically for matching castaway names.

The page stacks Pool Standings, The Island, and The Tribe Has Spoken. Pool standings list each member's picks still in the game. The Island lists living castaways alphabetically, with the drafter's “Name's Tribe” label beside the castaway's name. Any active advantage appears as a subtly animated icon beside their torch, with its short name directly below. Their torches flicker; eliminated castaways appear in exit order with a snuffed torch, portrait, drafter label, and Survivor tribe badge. Click any portrait to expand it. Use **Snuff Torch** to record a new vote-out and **Get Fire** beside an exit to restore that castaway and correct the exit order.

To record an existing exit history, add `| out 1`, `| out 2`, etc. after the owner on each exited castaway's line.

For the current board, Aaliyah Puglia is listed as a pre-draft exit. The board reflects Episode 4 (October 14, 2026): Jenna Doore is the fifth exit, Rob Antonson is marked as a quit, and the other exits are marked as voted out. Tribe labels reflect the Episode 4 swap: Toka (yellow), Savu (purple), and Dina (red). Existing Season 51 boards saved in a browser are updated with the Episode 4 tribe assignments and Jenna's elimination when the page loads. Standings show each pool member's remaining picks and exited picks.

The board is saved in the browser's local storage. Each device has its own copy, so edits do not sync between pool members.

Contestant portraits are stored locally in `assets/contestants/` and were sourced from [Parade's Survivor 51 cast gallery](https://parade.com/tv/survivor-51-cast-2026). The Parade gallery credits the cast photography to Robert Voets / CBS. The page background image is stored in `assets/backgrounds/`.

Advantage holders are currently listed through Episode 4: Carter Krull and Angelica “Jelly” Loblack hold Hidden Immunity Idols, while Devin Way and Maggie Nestor hold Secret Extra Votes. The holders were cross-checked against [Survivor Tribes' Season 51 advantage tracker](https://survivortribes.com/season/idols-advantages) and [Parade's Episode 4 recap](https://parade.com/tv/who-was-voted-off-survivor-tonight-week-4-recap-new-tribes-spoilers-2026). Hidden idols use a fishhook graphic; Secret Extra Votes use parchment, with subtle motion.

Click **Jeff Probst** in the footer disclaimer to reveal the hidden Jeff Probst easter egg. His image is stored in `assets/jeff-probst-easter-egg.jpg`.
