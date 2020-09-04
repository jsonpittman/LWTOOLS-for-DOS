# LWTOOLS-for-DOS
A fork of LWTOOLS 4.17 (a set of cross-development tools for the Motorola 6809 and Hitachi 6309 microprocessors) - but for DOS!

Main project page: http://lwtools.projects.l-w.ca/

### Download
[Download binaries](https://github.com/jsonpittman/LWTOOLS-for-DOS/raw/master/EXTRA/LW-BIN.zip) (16-bit, DOS-ready, compiled using DJGPP gcc)

### Compilation
To compile using FreeDOS 1.3RC3, the following are needed:

fdimples packages:
- Development
  - DJGPP (All Packages)
- Unix Like Tools
  - GNUSED

glib126b.zip (glib) is also needed for compilation. (Available from a [DJGPP mirror](https://mirror.koddos.net/djgpp/current/v2tk/), also provided in the EXTRAS directory for convenience). Extract to C:\DEVEL\DJGPP.

To Compile:

- make
- make install

(Copies EXEs to C:\LW by default.)

No extensive testing has been done to this fork. Use at your own risk.


### License

LWTools is licensed GPL. All modifications here are dual-licensed under the [BSD 3 Clause license](http://opensource.org/licenses/BSD-3-Clause).
