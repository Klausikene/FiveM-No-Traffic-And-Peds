# FiveM No Traffic And Peds

A simple resource to remove all ped and vehicles.
>This resource disables all locals by setting ped and vehicle budgets to zero.

## Installation

1. Download the code from this repository.

2. Extract the contents of this repo into your server /resources/**NoTraffic**. If the /Notraffic folder does not exists, then create it.

You can also create the folder inside /resources/[traffic]/**NoTraffic**

*NoTraffic* is the name of the resource in this case, but you can rename it to something like *populationoff* or *fivem-notraffic*. It's your choice. Make sure the name of the folder matches the name you'll set in the *server.cfg*

3. Add the resource name in the server.cfg: 

    `
    ensure NoTraffic
    `
4. Start your server. You can write **stop NoTraffic** in your server console to enable locals again.


You are able to change the values in the 'traffic_density.lua' file. Simply change the values of 'pedFrequency' and 'trafficFrequency' to whatever you like. Keep in mind that it has to be between 0.0 and 1.0 Anything above 1.0 will not work and won't affect anything. It is simply what Rockstar has as a maximum value.

# Important sidenote
The values you enter HAVE to be FLOAT values. That means that they have to be decimal numbers. They have to be formatted like this: 0.0 or 1.0 or 0.6 You get what I mean right?

Have fun!
Discord: klaus#1337
