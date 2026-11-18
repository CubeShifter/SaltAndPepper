
---
title: "Duck?"
author: "Kian Desh"
description: "A fidget toy that lets you press a keyboard switch and play a noise"
created_at: "2026-05-3"
---


# Started designing pcb
So I first of all wanted to decide what micrcontroller to use. I was planning to go with a pi pico for ease of use, but after doing some research i heard about a nice nano. Nice nano is specifically designed to be great for keyboards, and it would open up wireless capibilties later. I also wasnt fully sure what layout i wanted to do. I was thinking to do 75% but i think 65 percent is better. Either way it will be split and i kinda thought it would be cool to make it ergo, but i decided not to. I did start a bit on the pcb and got the left matrix working

<img src="https://cdn.hackclub.com/01a0f4d7-50a1-7bb3-b031-03e522f248b1/Screenshot%202026-09-30%20at%205.22.23%E2%80%AFPM.jpg">



**Total Time spent: 75 mins**

# Laid out

i did a bit of research onto how le sk6812 mini es work and they consume a LOT of power so im a bit scared to use them. i started laying out the keyboard and im gonna have to change it to use sockets cause i like hotswap. im still a bit confused on how to layout my keyboard but with the help of google and a dream im slowly getting there. i will need to add sk6812s tho :sob:
<img src="https://cdn.hackclub.com/01a0f4e6-1a51-7c9c-b5de-3a509e80de81/Screenshot%202026-09-30%20at%205.38.31%E2%80%AFPM.jpg">
**Total Time spent: 30 mins**


# lots of stuff

SO i did a lot of stuffv :sob: i first of all actually finished my schematic and wired up the columns and rows. I also had to get nice nano footprints and keyboard socket footprints. i then had to wire everything, undo it because my footprints changed to sockets. i also had to layout the footprints for the diodes and everythings. ts was not fun. i also really didnt like wiring everything it was very boring...

<img src="https://cdn.hackclub.com/01a10432-58b7-7a47-b338-9cfa9e071a50/Screenshot%202026-10-03%20at%204.56.09%E2%80%AFPM.jpg">
<img src"https://cdn.hackclub.com/01a10433-a551-770f-9654-5c1fdb3db2c7/Screenshot%202026-10-03%20at%204.57.31%E2%80%AFPM.jpg">

**Total Time spent: 120 mins**


# basically everything

so well i was on a plen and lowk finished my pcb. i started off with polishing the left side and making it better, then started on the right side. it was mostly the same, besides it being a row or two longer, and me also wanting to put an ec11 on it. i had to redo it once or twice so they would be in order like sw40, sw41 sw42. i layed out the keyboard and proceeded to fail a few times because for some reason one of the rows only had even numbers and one only had odd. i added all my diodes which let me just say that it was not fun. you have to try to make every single diode semi precise, and then realize that you need to flip all of your keyboard switches and therefore move the diodes to the other side. routing wasnt as bad as it couldve been, it was mainly just connect diodes, do rows and colums and wire up to nice nano. i tried to make wiring up to the nice nano pretty clean, but kinda failed. i mean it doesnt have to look pretty i guess so its fineeee. i then worked on adding an edge.cuts layer, which was pretty simple. it was mainly just trying to make it the same height as the left side and then making sure it fit my nano and stuff. i normally just forget to do drc, but i actually did it this time and it was helpful. i forgot to wire up a few diodes and also a few other things, but my goat drc got those and i fixed them. also silkscreen violations r so stupid. oh yeah i also added in mounting holes which was mainly just trying to make them precise and i had to redo a bit of wiring that was in the way. oh yeah i had to add in mousebites cause my friend told me to just do one pcb with mousebites on it so i did that. lemme see what screenshots i can get.

<img src="https://cdn.hackclub.com/01a12a60-de79-7054-8ef1-361109c30774/Screenshot%202026-10-11%20at%2011.52.31%E2%80%AFAM.jpg">
<img src="https://cdn.hackclub.com/01a12a61-0e79-743d-916d-43b4a46608d9/Screenshot%202026-10-11%20at%2011.52.43%E2%80%AFAM.jpg">
<img src="https://cdn.hackclub.com/01a12a61-52e1-7173-9db9-ab08c9da3f6e/Screenshot%202026-10-11%20at%2011.53.01%E2%80%AFAM.jpg">
<img src="https://cdn.hackclub.com/01a12a61-80a4-7c85-8379-e3f8412c9b49/Screenshot%202026-10-11%20at%2011.53.13%E2%80%AFAM.jpg">
<img src="https://cdn.hackclub.com/01a12a61-e40d-7327-b24c-27a1777bc7e8/Screenshot%202026-10-11%20at%2011.53.38%E2%80%AFAM.jpg">


**Total Time spent: 270 mins**

# added on and off switch and bomed

so basically there comes a time in life when ur not on ur keyboard, then you lowk have to turn the power off so i had to make my thing do that. i found a good right angle switch on lcsc and spent far to long not wanting to use a cli to get the footprint. i look for alternatives but wasnt really awake enough to do any of those so i just used the easyeda2kicad cli. i also made a bom, which was pretty easy since i alr had all the parts. no bom photo for u cause its literally in the repo.

<img src="https://cdn.hackclub.com/01a13524-6273-758f-be2c-ab987a13e956/Screenshot%202026-10-13%20at%202.02.15%E2%80%AFPM.jpg">

**Total Time spent: 60 mins**


