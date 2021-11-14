PowerUP-Cpu,Net资源自动租赁脚本。无须额外手续费。因为EOSIO的新资源模型powerup 的cpu,net只能租24h，为了实现高频量化套利账户一直有资源可交易，基于eosjs实现了一个自动续租资源的脚本。当cpu或net低于某个值时，该脚本可以自动帮你续租一份24h的cpu或net。 这样可以提高套利账户的cpu,net的利用率，避免了频繁资源租赁操作和资源的大量闲置。

Powerup-- CPU, Net resource auto lease script. No additional handling charge. The CPU and Net can only be rented for 24h in the new resource model powerup. In order to realize the high-frequency quantitative arbitrage account has resources to trade all the time, a script for automatically renewing resources is implemented based on eosjs. When the CPU or net is lower than a certain value, the script can automatically help you renew some 24-hour CPU or Net. This can improve the utilization of CPU and net of the arbitrage account, and avoid frequent resource leasing operations and a large number of idle resources.

-----------------------------------------------------------------------
node autocpu.js
