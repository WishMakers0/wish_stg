# wish_stg

### Note: this repo contains no scripts, merely the system that underlies the scripts, due to both distribution concerns regarding potential asset use as well as large file access on GitHub being a limited resource.
### You can find my scripts on my [Bulletforge](https://www.bulletforge.org/u/wishmakers).  Newer ones will expect to be placed in this project's script directory where relevant, and a mirror of this project's contents with binaries will be able to be found there as well.

[TOC]

## What is this?

This came from seeing my peers all create little package houses for their scripts within Danmakufu, and I found it pretty novel, so I thought it would be worth trying myself.
This repo serves as a form of version control for primarily my own use, but it could be a useful study for those developing systems and packages, as the tutorials for them by Sparen and Helepolis are either not done yet or nonexistant, respectively.
Bear in mind that I not only use ph3sx, but I use [my own custom fork](https://github.com/WishMakers0/Touhou-Danmakufu-ph3sx-RoEW) primarily intended for use within my long-term fangame project.  There may be some things I do that don't exactly transfer to normal versions of the engine.
I don't expect any pull requests, but if you see I did a big stupid you can send one and let me know on Discord.

## Contents

```
wish_stg
├── script
│	├── DATS_GO_HERE (directory, should be self-explanatory)
│   ├── package
│   │   ├── th_roew.dnh (bootstrap because i don't feel like recompiling and changing one line in the cpp source)
│   │   └── package.dnh (actual package)
│   └── system
│        └── (all the major system contents I don't feel like spelling out everything)
│
├── th_roew.exe (sorry gnu/linux fans you'll need proton probably)
├── config.exe (potentially unnecessary in future versions due to some new dnh developments)
└── README.md (this file)
```

## Greets/Credits

Python, Drek - for creating T.B.A and MoSS which inspired this project in the first place
Natashi, Naudiz, neck - for tolerating my incessant questions in the ph3sx server
Mana - for teaching me many new tricks in DNH engine building that inspire me to push the boundaries
Trickysticks - moral support and woo legacy

## Building/Download Info

Realistically most of these contents will already be in a cloned repo, but I'm gitignoring my binaries, as I could forget about this repo's existence very easily and forget to re-include them here properly.
You can either build the right commit version of my engine (which I do not recommend unless you enjoy suffering) or simply download the full binary from my Bulletforge release of this repo, when it's available. (As of writing, wish_stg is incomplete and not up for bulletforge download yet.)
DNH scripts are interpreted so besides the engine build being the correct variety there should be no major issues.

## Issues, and Script Compatibility

ph3sx builds are practically known for their lack of backwards compatibility in many respects, so if one of my scripts breaks under a new version of my system, don't hesitate to send an issue!!  I can't promise to fix it immediately (anyone who plays my official Touhou game mods will know I am slow to fix bugs after release because I tend to forget...) but issue tracking is a good way of making sure I do eventually remember to fix it and patch it on Bulletforge.