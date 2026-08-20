# 🕹️ Games

Casino games use wallet credits. Enter positive whole-number wagers and read the interactive controls before confirming an action.

## Core games

| Game | Command | How it plays |
| --- | --- | --- |
| Blackjack | `/blackjack <bet>` | Hit, stand, double, split eligible pairs, and take insurance when offered. |
| Baccarat | `/baccarat <bet>` | Bet on the player, banker, or tie. |
| Poker | `/poker <bet>` | Play a complete poker hand against the house. |
| Roulette | `/roulette <bet>` | Choose a supported number or table characteristic. |
| Slots | `/slots <bet>` | Spin for matching symbols and a chance at the growing Big Win. |
| Coinflip | `/coinflip <bet> <heads-or-tails>` | A correct choice returns 2× the wager. |
| Rock Paper Scissors | `/rockpaperscissors <bet> <choice>` | A win returns 2×; a tie returns the wager. |
| Dice | `/dice <bet>` | A roll of 6 returns 5.8×; other results lose. |
| Crash | `/crash <bet>` | Manually cash out before the round crashes. |
| Mines | `/mines start <bet> <mines>` | Reveal safe tiles, build a multiplier, and cash out before hitting a mine. |
| Plinko | `/plinko <bet>` | Watch the ball travel through pins to a payout slot. |
| Scratch | `/scratch <bet>` | Reveal the scratch card and match its prize conditions. |
| Horse | `/horse <bet>` | Choose a horse and watch the race. |
| High Low | `/highlow <bet>` | Predict whether the next card is higher or lower. |
| Deal or No Deal | `/dond <bet>` | Open cases, evaluate banker offers, and decide when to deal. |
| Get the Ace | `/gettheace <bet>` | Try to beat the dealer's card. |
| Card Flipper | `/cardflipper <bet>` | Make card predictions across an interactive round. |

Additional casual games include `/ttt`, `/hangman`, and `/minesweeper`.

## Multiplayer

The Casino supports shared tables for Blackjack, Poker, Roulette, Horse Racing, and Crash. Multiplayer commands begin with `/multiplayer`, such as `/multiplayerbj` and `/multiplayercrash`. The host creates the lobby, other players join, and the round begins when the table is ready.

{% hint style="info" %}
Displayed payouts are total returns unless a game explicitly labels a number as profit. A 2× win on a 1,000-credit wager returns 2,000 credits total.
{% endhint %}

## Fair-play controls

Outcomes are generated and settled by the bot. Visuals and animations present the result; they do not choose it.
