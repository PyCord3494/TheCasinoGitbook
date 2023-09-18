# Upgrades

<details>

<summary>Storage</summary>

Miners can only hold a certain amount of coins-worth of crypto. Default is 25,000

Upgrading storage increases this amount by 25,000 each time.&#x20;

Cost is defined as:

```
100000 + (currentstorage / 25000 - 1) * 25000)
```

In other words, first upgrade is 100,000. Every upgrade after that, the cost increases by 25,000.

Max storage allowed is 200,000.

</details>

<details>

<summary>Speed</summary>

By default, every hour, miners will get you one of these amounts:

150, 160, 170, 180, 190, 200

Each upgrade of Speed increases the amount given by 10%, with a max upgrades of 9 (meaning 90% increase).

</details>
