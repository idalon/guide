# Shrine Cycles & Bus

The Shrine activates on a fixed 2 second interval, known as the Shrine Cycle. Your Bus is the combined time of your Last Limb Break Time (LLBT) and Capshot Time (CT). Bus = LLBT + CT

If you miss a bus, you’ll be forced to wait for the next Shrine Cycle, potentially losing up to 2 seconds.

* Garry Shrine: Earliest bus is 1:23.300. Miss it, and you'll hit 1:25.300, 1:27.300, etc.
* Harry Shrine: Earliest bus is 4:03.700, followed by 4:05.700, 4:07.700, etc.

Important Notes:

* These buses are based on a stable 144 FPS, your mileage may vary.
* The bulk of the bus metric is just LLBT; if you have fast Capshots you don't have to pay attention to them.
* The 4:03.700 bus is hard to hit in most cases. In speedruns, 4:05.700 is more typical.
* The first set of each hunt (preload set) follows different earliest buses: 1:19.400 for the first Shrine and 3:59.800 for the second (and every 2s from there).
* Why we call it a bus: it can be thought of as a bus stop — we wait for predetermined shrine cycles in the same way one waits for a bus to arrive.

How to Find Your Own Bus

You can extract them from your idalon logs using Lead’s ShrineCatBot on Discord. This bot is already integrated with the Eidolon Server.

* idalon: http://idalon.com/
* ShrineCatBot: https://discord.com/oauth2/authorize?client\_id=1462504868383031500

Discord command:

![](<../../.gitbook/assets/image (3)>)

Output:

![](<../../.gitbook/assets/image (5)>)

From that output you can interpret that the Garry bus is around 1.XX.300 (XX = 23, 25, 27…) and the Harry Bus around 4:XX.700 (XX = 03, 04, 05…). Since XX is always an odd number, you can focus on the decimal part (.000) exclusively. If you analyze your own runs, you may find your buses to be different from XX.300 and XX.700.

Example — Terry’s Vulnerability Times and Buses for Garry and Harry

144 FPS Cap Comparison

* IG: In-game
* RTSS: RivaTuner Statistics Server
* NVPC: NVIDIA Control Panel
* NVPC RTSS ONLY: only external software used, in-game framerate set to unlimited

![](<../../.gitbook/assets/image (6)>)

Only decimals, average ± standard deviation

* RTSS+IG: High bus, most consistent
* IG only: Low bus, fastest (hard to bus)
* NVCP+IG: Low bus, fast but inconsistent
* NVCP only: High bus, slow but consistent (easier to bus)
* RTSS only: High bus, slow (easy Terry, easy to bus)

Related links

* https://fenomeral.gitbook.io/eidolon-guide/advanced/shrine-cycles-and-bus#how-to-find-your-own-bus
* https://fenomeral.gitbook.io/eidolon-guide/advanced/shrine-cycles-and-bus#example-terrys-vulnerability-times-and-buses-for-garry-and-harry
