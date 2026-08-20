# Usable Items

Usable items are consumed when their effect succeeds. Use `/use <item> [quantity]` for ordinary usable items and `/activebuffs` to review active effects.

## Multipliers

| Item | Effect | Duration |
| --- | ---: | ---: |
| Voter Chip | 1.3× multiplier | 2.5 hours |
| High Card | 1.1× | 2 hours |
| One Pair | 1.1× | 2 hours |
| Two Pair | 1.15× | 2 hours |
| Straight | 1.2× | 2 hours |
| Flush | 1.3× | 2 hours |
| Full House | 1.4× | 1.5 hours |
| Four of a Kind | 1.5× | 1 hour |
| Straight Flush | 1.6× | 30 minutes |
| Royal Flush | 1.75× | 15 minutes |

An incompatible multiplier cannot replace another active multiplier. The bot will explain the conflict without consuming the item.

## Game-specific items

* **Ace of Spades** — influences the opening Blackjack hand.
* **Dealer Chip** — changes the Blackjack opening flow.
* **Big Blind Chip** — provides Blackjack card-count information.
* **Deck of Cards** — activates its supported Blackjack effect.
* **Three of a Kind** — activates its supported Roulette effect.
* **Small Blind Chip** — activates its timed buff.
* **Magic 8 Ball** — consumes the item and reveals its credit reward.

## Crates

Standard, Silver, Gold, Diamond, and Platinum crates use the dedicated `/crate open` flow and each require one Key. See [Crates](../crates.md).
