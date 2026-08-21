# 🔨 Auctions

Auctions let players list owned items for competitive bidding with wallet Credits.

| Command | Usage |
| --- | --- |
| `/auction list [search] [sort]` | Browse active listings. |
| `/auction bid <id> <amount>` | Bid at least 100 Credits above the current bid. |
| `/auction sell [quantity]` | Open the listing form and sell 1–100 identical items. |
| `/auction manage` | Review your active listings, bids, and expiration times. |
| `/auction cancel <id>` | Cancel your own listing while it has no bids. |
| `/auction history` | Review your latest sold, unsold, won, and cancelled auctions. |

The seller form shows only eligible items currently in your inventory. Long inventories are divided into valid 25-item Discord menu pages. Standard, Silver, Gold, Diamond, and Platinum Crates are listable.

The listed quantity is reserved from inventory. If the auction sells, the complete quantity goes to the winner and the seller receives the payout after their displayed seller fee. If it expires without bids, every listed item returns to the seller. Eligible Donator tiers receive their configured reduced seller fee.

Listing creation, cancellation, item returns, bids, bidder refunds, and settlement are transactional.

{% hint style="warning" %}
Bids and starting prices must be whole numbers. A listing that has received a bid cannot be cancelled by its seller.
{% endhint %}
