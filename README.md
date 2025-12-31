<img src="https://raw.githubusercontent.com/clover-moe/lilium-voyager/master/misc/lilium.png" width="64">

**Lilium Voyager** is an engine compatible with _Star Trek Voyager: Elite Force Holomatch_ (multiplayer).

The goal is to maintain the original _Star Trek Voyager: Elite Force: Holomatch_ gameplay, visuals, and audio experience while also providing a reliable code base for derivative projects and support for many platforms.


## About

Differences from ioEF 1.38-rc1 (2011):

  * Player origin rounding is compatible with the original QVMs (x86, x86_64).
  * Fixed "read past end of server message" error after downloading a pk3 using EF 1.2 protocol (24).
  * Network compatible with ioEF 1.37.
  * Dedicated servers are listed on official Raven master server.
  * Client and server use separate config files (from ioq3).
  * Better compatibility with newer operating systems (from ioq3).
  * VoIP uses Opus codec instead of Speex (from ioq3).
  * Support for ioquake3's OpenGL2 renderer.

Lilium Voyager is based on [Lilium Arena](https://github.com/clover-moe/lilium-arena).
Lilium Voyager code commits: [compare/upstream...master](https://github.com/clover-moe/lilium-voyager/compare/upstream...master)

The source code for the _Elite Force Holomatch_ game, cgame, and ui code is not included as it remains under a non-free license.


## History

Lilium Voyager is based Thilo Schulz' ioEF engine (also known as iostvoyHM) that reimplemented the _Star Trek Voyager: Elite Force: Holomatch_ engine on the Quake 3 GPL source code by id Software that was further developed in ioquake3. ioEF began development in 2005 and left off in 2011.

zturtleman picked up updating ioEF to newer ioquake3 in 2014 under the name Lilium Voyager. In 2025, Lilium Voyager moved to using Lilium Arena as it's based instead of ioquake3.

The ioEF code changes were distributed as diff patches for ioquake3's Subversion repository at the [ioEF website](http://thilo.tjps.eu/efport-progress/). These are available as complete source code at [zturtleman/ioef-archive](https://github.com/zturtleman/ioef-archive). Thilo Schulz updated ioEF in 2016 at [thiloschulz/ioef](https://github.com/thiloschulz/ioef); this did not see a formal release and it does not include the past ioEF source code.


## License

Lilium Voyager is licensed under [the GNU GPLv2](COPYING.txt) (or at your option, any later version). The _Elite Force Holomatch_ data files are not under a free license and must be purchased in order to play _Elite Force Holomatch_.


## Resources

  * [Website](https://clover.moe/lilium-voyager)
  * [Discussion / Technical support](https://clover.moe/open-source)


## Compiling

Lilium Voyager is compiled using GNU Make (`make`) and requires a C compiler. Most dependencies are included in the repository. Compiling for Linux requires installing SDL 2 library and headers.


## Contributing

High quality code contributions are more helpful than rushed contributions.

Reviewing pull requests is sometimes more work than a reviewer doing the work in the first place so pull requests may be disregarded.


## Credits

Lilium Voyager is maintained by Clover.moe.

### id Software

  * John Carmack
  * Robert A. Duffy
  * Jim Dose'
  * Jan Paul van Waveren

### ioquake3 contributors

  * Tim Angus
  * James Canete
  * Vincent Cojot
  * Ryan C. Gordon
  * Aaron Gyes
  * Zack Middleton
  * Ludwig Nussel
  * Julian Priestley
  * Scirocco Six
  * Thilo Schulz
  * Jack Slater
  * Tony J. White
  * ...and many, many others!

### ioEF

  * Thilo Schulz

### Clover.moe

  * Zack Middleton (zturtleman)


