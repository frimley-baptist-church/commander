# Commander
Commander is a web UI that provides touch control of an Blackmagic Design ATEM Extreme 8-channel switcher, and 5 x PTZ cameras.

![Commander-interface](https://user-images.githubusercontent.com/5892030/138604234-88bc1c92-c3af-41c1-80ce-8b9ceb9067d8.png)

![PTZ-overlay](https://user-images.githubusercontent.com/5892030/138604237-bc59f501-82a9-4cff-9a07-2a8f29c2a25e.png)

It was built to support easy control of the switcher and cameras used during Sunday services streamed to our [YouTube channel](https://www.youtube.com/channel/UCPb62fbC7uBtisUjU__I47g).

There are a number of design objectives:

* Easy to learn interface for non-technical operators
* Integrated PTZ camera preset shot section and management
* Independent control of the switcher Preview and Program busses
* Flexible touch control positioning
* Control of our upstream keyer
* Bi-directional control reflecting switcher routing status at all times
* Touch-screen friendly design
* Interlock to prevent PTZ camera changes if that PTZ camera is on-air

The software also supports the 4-channel ATEM Mini, and subject to additional changes, should support all other BMD ATEM switchers. Please note that none of the wider BMD switcher range have been tested as we [FBC] don't have access to any other BMD devices besides those mentioned already.
