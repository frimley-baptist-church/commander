# Commander
Commander is a web UI that provides touch control of an Blackmagic Design ATEM Extreme 8-channel switcher, and 5 x PTZ cameras.

![Screenshot from 2021-09-01 11-41-08](https://user-images.githubusercontent.com/5892030/131657868-3036af33-3a2c-40e3-97ca-311cc9b0837f.png)

It was built to support easy control of the switcher and cameras used during Sunday services streamed to our [YouTube channel](https://www.youtube.com/channel/UCPb62fbC7uBtisUjU__I47g).

There are a number of design objectives:

* Easy to learn interface for non-technical operators
* Integrated PTZ camera preset shot section and management
* Independent control of the switcher Preview and Program busses
* Flexible touch control positioning
* Control of our upstream keyer
* Bi-directional control reflecting switcher routing status at all times
* Touch-screen friendly design
* Interlock to prevent PTZ camera moves if that PTZ camera is on-air

The software also supports the 4-channel ATEM Mini, and subject to additional changes, should support all other BMD ATEM switchers. Please note that none of the wider BMD switcher range have been tested as we [FBC] don't have access to any other BMD devices besides those mentioned already.
