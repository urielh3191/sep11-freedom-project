# vue.js Learning Log

## Tool: **vue.js**

## Project: **Digital Dashboard**

---

### 10/20/24, Entry 1:
* Since my tool is vue.js, obviously one has to start at the documentation. Combing over the documentation, I realize I might have picked such a complex and overpowered tool for my simple calendar project. Oops. But hopefully that means I can just use it in more flexible ways.

* Opening this [link](https://vuejs.org/examples/#hello-world) honestly showed me nothing 😭. Obviously, while different from vanilla JavaScript, the example doesn't really show much of what it can TRULY do, but this is a start, no?

* But the little template thing is really cool and I MIGHT have a use for it in my digital dashboard, where I will try and connect a live feed from a video camera (essentially working as a video doorbell), while also getting updates from the National Weather Service (to tell me if its raining, snowing, tornado, cat and dogs falling from the sky, or just plain sunny outside), which will also be displayed as a mini-window on the website.

### 10/26/24, Entry 2:
* I finally got around to installing vue.js. The website has a nice design and a good navbar, but I still got a bit lost. The “Quick Start” wasn’t quick for me—I kept mixing up instructions for other applications of vue.js, because that specific website is littered with instructions.

* Anyways, by adding
```<script src="https://unpkg.com/vue@3/dist/vue.global.js"></script>``` to my HTML, I now have access to vue.js within a little sandbox I made where I'm live-testing the UI of the dashboard. Now, using the Hello World demo from the previous entry, I start to envision how I can use this tool in my project. Since vue.js allows you to set a variable whose value can change later, it might come in clutch later when I need a whole bunch of placeholders to hold real information from NWS APIs or updating video feeds. So I tried it, and oh my god my brain hurts. I thought this whole ```var``` thing would be easy, but the [built-in playground](https://play.vuejs.org) doesn't even seem to want to run with it's own sample code, and just says "Vue is not defined." I give up. Next week, I'll try and troubleshoot it.

<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
