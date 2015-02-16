# dash-dev

A personal safety measure to stop someone else creating a malicious package in this space...


## Why

I am a terrible at typing. I make all sorts of stupid mistakes.

I add spaces where they shouldn't be and leavethem out in places they should be.

The one that I see as dangerous is:

    npm i --save -dev someModule

If someone created a malicious package called -dev I would will destroy my machine.

This module just makes the command fail and tells me I am a Jackass...