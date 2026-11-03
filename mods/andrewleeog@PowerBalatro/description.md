# PowerBalatro

Track the current Balatro run with summaries, charts, card usage, and probability hit rates.

## Features

- **Summary:** run records and totals, purchases, Standard/Arcana/Celestial/Spectral/Buffoon pack counts, and average/median hand scores.
- **Trends:** cycle between Overview, Analysis, Economy, and Deck. Overview covers scoring, money, hand usage, and consumables; Analysis covers score consistency and spending categories.
- **Economy:** income sources by ante (blind rewards, unused hands, interest, sales, and Other) and poker-hand level progression. Inspect the top three used hands or choose an individual hand.
- **Deck:** per-ante composition snapshots and a detailed breakdown for suits, ranks, enhancements, seals, and editions. History groups less common categories; the detail chart shows all categories.
- **Prob:** recorded hits and rolls alongside current listed probabilities, including stacked Oops! All Sixes effects.
- **Cards:** rank/suit charts for played, discarded, drawn, and draw-to-play use rates.
- Shared ante filtering shows played antes, skips gaps, and supports endless runs beyond ante 8.
- PowerBalatro is available from the pause menu and win/game-over screens. Back returns to the result screen after reviewing a completed run.

Stats persist with the run save. New metrics start recording when installed; missing historical data is not reconstructed. The mod does not keep a separate archive after leaving a result screen or starting another run.

## Requirements

- [Lovely](https://github.com/ethangreen-dev/lovely-injector)
- [Steamodded](https://github.com/Steamodded/smods) is optional. Without it, the mod loads through Lovely and tracks Balatro's built-in chance effects. When installed, Steamodded's probability API is used for vanilla and supported modded effects.
- Talisman is not required.

## Installation and usage

Install into `Mods/PowerBalatro` and restart Balatro. For manual installation, extract the release ZIP into the Mods directory, keeping its `PowerBalatro` folder. Open **PowerBalatro** from the pause menu or result screen.

Released by **andrewleeog** under the [MIT license](https://github.com/andrewleeog/PowerBalatro/blob/main/LICENSE), which permits redistribution and mod-manager distribution.

Previously named Balatro Run Stats. When updating from the former name, replace or rename the old folder so only one copy is installed. The internal mod ID and saved run data remain compatible.

The Scoring tab shows contribution graphs for newly played hands, with ante and round selectors and raw score plus percentage for owned Jokers, base hand/planet levels, and card scoring. Attribution follows scoring order; multipliers receive their incremental gains, and setup/enabling effects may have zero direct share.
