# Blade

> [!WARNING]
> This repository has now been archived. The code here is extremely primitive and slow compared to how I would currently structure it, and out of the box this systen will not compete with the latest available bots. I've made this repository public as a resource for beginners to get some ideas as to how bots like this function, and possibly use some concepts here in their own systems.

A [pump.fun](https://pump.fun/) sniper bot with an integrated realtime monitoring system built purposefully stateless to allow multiple instances with the same setup to be run and not interfere with each other.

Blade's purpose is to snipe certain pump.fun bonding curves at their time of creation based off user defined filters. It aims to land within the first few buy txs ( following any dev buy ) to get the best price possible and sell later on to make gains off of following buyers.
