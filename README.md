# FiveM nolocals

A simple resource to remove all ped and vehicles.

>This resource disables all locals by setting ped and vehicle budgets to zero.

## Installation

1. Download the code from this repository.

2. Extract the contents of this repo into your server /resources/**nolocals**. If the /nolocals folder does not exists, then create it.

You can also create the folder inside /resources/[local]/**nolocals**

*nolocals* is the name of the resource in this case, but you can rename it to something like *populationoff* or *fivem-nolocals*. It's your choice. Make sure the name of the folder matches the name you'll set in the *server.cfg*

3. Add the resource name in the server.cfg: 

    `
    ensure nolocals
    `
4. Start your server. You can write **stop nolocals** in your server console to enable locals again.

License: MIT