## About Me

Hey, welcome to my Github Profile, which you somehow found...
Well, since you are already here, I am Rain (he/them) and I write software in a [lot of different languages](#skills-by-comfortability-tier-list) with a [lot of different topics](#topics-i-dabbled-in). Besides coding, you might have noticed that I am a dragon on the internet and yeah, I am kinda deep into that [furry stuff](https://en.wikipedia.org/wiki/Furry_fandom), take a look at my [sona](#fursona) if ya want. Otherwise I have an interest in music and tried playing some piano and guitar, but no where near any playable level. If ya wanna know what I am currently working on, there is a small [Projects Overview](#projects-overview) at the bottom.

## Fursona

<img style="float: right; margin-left: 1rem" width="280" src="rain.gif" alt="GIF of a blue dragon standing in the rain with a green raincoat">

My sona is a blue very fluffy water dragon named Rain, he can breath under water using gills hidden under his fur, but otherwise he is just your regular fire-breathing dragon. That is all you need to know for now. Artwork by [maia](https://twitter.com/maiathoustra).

## Contact & Socials

- Discord: Rain336#5230
- Telegram: [@Rain336](https://t.me/rain336)
- Email: rain336 *at* live *dot* de
- Twitter: [@RainFire336](https://twitter.com/rainfire336)

## Skills By Comfortability Tier List

### Comfortable & Use regularly

![C#, Rust, TypeScript, JavaScript, CSS, HTML, Git, Powershell, Docker, Discord?](https://skillicons.dev/icons?i=cs,rust,ts,js,css,html,git,powershell,docker,discord&perline=7)

### Comfortable

![Linux, Bash, Python, Flutter, React, Tailwind, Deno, GraphQL, Go, Java, WebAssembly, C, C++](https://skillicons.dev/icons?i=linux,bash,py,flutter,react,tailwind,deno,graphql,go,java,wasm,c,cpp&perline=7)

### Would need some practice

![Figma, Bevy, SolidJS, Svelte, Swift, Ansible](https://skillicons.dev/icons?i=figma,bevy,solidjs,svelte,swift,ansible)

### No idea

![haskell](https://skillicons.dev/icons?i=haskell)

### PHP

![PHP, Plan9 from Bell Labs](https://skillicons.dev/icons?i=php,plan9)

## Topics I Dabbled In

- Web development (React, HTML, CSS)
- Backend development (ASP.NET, Rust Axum, GraphQL)
- Operating System Development (Paging, Virtual Memory, ACPI, UEFI)
- Programming Language Compilers (Parsing, Type Checking, Code Generation)
- Databases (Postgres, Redis, SQLite, RocksDB)
- Server Administration (Linux & Windows, Powershell, Docker)
- CI/CD Pipelines (Azure Pipelines)

## Projects Overview

**DISCLAIMER**: Most of my projects are *incomplete* and are mostly me learning a certain topic or language.

- [Microdragon](https://github.com/Rain336/Microdragon) (Rust) *HIGH*
	- A microkernel written in Rust, trying to bridge the gap between embedded and general purpose operating systems
	- It is still in it's early days, trying to make a good framework for an OS
	- I will work on this every now and then, the work is can be quite draining for me, so I sometimes need to take a break from it.
- [DragonScript](https://github.com/Rain336/DragonScript) (Rust) *HIGH*
	- A JavaScript (and TypeScript) Engine, inspired by JavaScript Core's Architecture
	- Currently still in it's infancy, dunno how far I'll get with this, but it's a very interesting topic for me right now
- [Sparky](https://github.com/Rain336/Sparky) (C#) *MID*
	- A Flutter-inspired MVU UI Framework for Mobile Devices
	- A UI Tree can be built, but no layouting or interactivity is implemented yet
	- I should work on this more...
- HCS (Rust) *LOW*
	- Rust Bindings to Microsoft's Host Compute Service (Windows Container)
	- hcs-sys is usable, but it's high level wrapper needs more work, mapping the json structures to Rust is a bit of challenge and needs a better approach 
	- I will continue working on it, if I find a good use for Windows Containers
- KNX (Rust) *STALE*
	- A Nintendo Switch Emulator running on Mac OS' Hypervisor.framework for ARM
	- Mostly stopped after I found out that Mac OS uses a 16K gauntlet sizes and I would need to write EL1 Page Tables into the guest
	- It was mostly a learning experience for me in using Hypervisors and Emulation
- registered_io (Rust) *LOW*
	- Rust Bindings to Windows Registered IO
	- Incomplete, should be updated to windows-rs maybe, too occupied with other projects
- smb (Rust) *LOW*
	- Rust Implementation of the SMB protocol
	- Incomplete, barely started, I should work more on this, but too occupied with other projects
- [JSystem](https://github.com/Rain336/JSystem) (Rust) *LOW*
	- A Parser for Revolution (Nintendo Wii) file formats
	- I still work on this every now and then, especially when the nostalgia for Wii games hits
- ILCompiler (C#) *STALE*
	- Compiles MSIL (CIL) to native code using GccJit (essentially another AOT compiler)
	- I started writing Bindings for libGccJit that could be reused, and that's all, I most likely won't continue working on it
	- I was interested in GccJit as a library, especially since it's small API surface in comparison with it's big contender LLVM
- go-rs (Rust) *LOW*
	- Allows calling rust form go without using cgo
	- I started writing the macro for it, but never finished, might pick it up again at some point
- [lsusb](https://github.com/Rain336/lsusb) (Rust) *DONE*
	- Very simple tool that lists connected USB devices
	- Done, it does what it should
- DragonGraph (Python) *STALE*
	- An implementation of a distributed merkle-dag for a Database
	- I honestly don't know how far developed this is... Has stopped working on this for a while
