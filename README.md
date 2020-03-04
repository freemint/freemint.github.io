## Welcome to the FreeMiNT Project website

This website is a frontend for the [freemint github repositories](https://github.com/freemint). If you would like to know more about FreeMiNT, the best place to start is [the wiki](https://github.com/freemint/freemint/wiki). Best place to download/try latest builds is [snapshots](#snapshots).

## FreeMiNT Project

FreeMiNT project is a community based hub for several more or less related projects:

- [FreeMiNT](https://github.com/freemint/freemint) (kernel)
- [XaAES](https://github.com/freemint/freemint/tree/master/xaaes) (multitasking GEM AES replacement, part of FreeMiNT now)
- [MiNTlib](https://github.com/freemint/mintlib) (libc for FreeMiNT and TOS, a C standard library)
- [FDlibm](https://github.com/freemint/fdlibm) (libm for FreeMiNT and TOS, a C math library)
- [GEMlib](https://github.com/freemint/gemlib/tree/master) (GEM bindings for writing GEM apps)
- [MiNTbin](https://github.com/freemint/mintbin) (set of, mostly deprecated, tools for manipulation of (Free)MiNT binaries)
- [git](https://github.com/freemint/git) (experimental fork for FreeMiNT of the popular version control system)
- [m68k-atari-mint-gcc](https://github.com/freemint/m68k-atari-mint-gcc) (gcc for FreeMiNT)
- [m68k-atari-mint-binutils-gdb](https://github.com/freemint/m68k-atari-mint-binutils-gdb) (binutils and gdb for FreeMiNT)
- [freemint.github.io](https://github.com/freemint/freemint.github.io) (project website sources, you're reading it)

Those are the main (and most important) projects. There are several affiliated repositories, either for historical reasons or because the former SpareMiNT CVS server hosted them (the first section belongs to projects which are still actively maintained):

- [CFLib](https://github.com/freemint/cflib/tree/master) (extension library for GEM programming)
- [gemma](https://github.com/freemint/gemma/tree/master) (SLB based GEM library)
- [QED](https://github.com/freemint/qed) (GEM text editor)
- [COPS](https://github.com/freemint/cops) (XCONTROL.ACC replacement)
- [HypView](https://github.com/freemint/hypview) (ST-Guide replacement)
- [tos.hyp](https://github.com/freemint/tos.hyp) (most complete programmer's reference for TOS/GEM programming)


- [HighWire](https://github.com/freemint/highwire) (GEM web browser)
- [Phoenix](https://github.com/freemint/phoenix) (database GEM app)
- [Smurf](https://github.com/freemint/smurf) (GEM painting app)
- [oVDI](https://github.com/freemint/ovdi) (Odd Skancke's VDI project)
- [vlogin](https://github.com/freemint/vlogin) (VDI login)
- [xg](https://github.com/freemint/xg) (X11 6.4 for GEM)
- [init](https://github.com/freemint/mintinit) (/sbin/init and related programs)
- [init scripts](https://github.com/freemint/initscripts) (basic shell scripts for system startup)
- [sparemint](https://github.com/freemint/sparemint) (SpareMiNT website and archive, predecessor of this hub; github mirror [here](https://freemint.github.io/sparemint/sparemint))

## Download
### Releases

Official releases (mostly source only):
- [FreeMiNT and XaAES](https://github.com/freemint/freemint/releases) (most complete release archive)
- [MiNTlib](https://github.com/freemint/mintlib/releases)
- [FDlibm](https://github.com/freemint/fdlibm/releases)
- [GEMlib](https://github.com/freemint/gemlib/releases)
- [CFLib](https://github.com/freemint/cflib/releases)
- [gemma](https://github.com/freemint/gemma/releases)
- [MiNTbin](https://github.com/freemint/mintbin/releases)
- [QED](https://github.com/freemint/qed/releases)

### Snapshots
Latest binary snapshots (built after each commit):
- FreeMiNT and XaAES: [ ![Download](https://api.bintray.com/packages/freemint/freemint/snapshots/images/download.svg) ](https://bintray.com/freemint/freemint/snapshots/_latestVersion) (bootable, preconfigured and maintained archives for the ST, 020+ machines, ARAnyM and the FireBee) and [ ![Download](https://api.bintray.com/packages/freemint/freemint/snapshots-cpu/images/download.svg) ](https://bintray.com/freemint/freemint/snapshots-cpu/_latestVersion) (per-CPU builds, if you prefer just upgrading an existing installation on your machine). For historical purposes, you can download the last "old school" builds done for all CPU combinations, with the original file tree structure as on [freemint.org](http://freemint.org):
  - trunk: [ ![Download](https://api.bintray.com/packages/freemint/freemint/snapshots-raw/images/download.svg) ](https://bintray.com/freemint/freemint/snapshots-raw/_latestVersion) (master branch)
  - helmut: [ ![Download](https://api.bintray.com/packages/freemint/freemint/snapshots-helmut-raw/images/download.svg) ](https://bintray.com/freemint/freemint/snapshots-helmut-raw/_latestVersion) (Helmut Karlowski's branch)
  - freemint-1_18: [ ![Download](https://api.bintray.com/packages/freemint/freemint/snapshots-1.18-raw/images/download.svg) ](https://bintray.com/freemint/freemint/snapshots-1.18-raw/_latestVersion) (FreeMiNT 1.18 branch)
- USB TOS drivers: [ ![Download](https://api.bintray.com/packages/freemint/freemint/snapshots-usb4tos/images/download.svg) ](https://bintray.com/freemint/freemint/snapshots-usb4tos/_latestVersion)
- [MiNTlib](https://github.com/freemint/freemint.github.io/tree/master/builds/mintlib/master)
- [FDlibm](https://github.com/freemint/freemint.github.io/tree/master/builds/fdlibm/master)
- [GEMlib](https://github.com/freemint/freemint.github.io/tree/master/builds/gemlib/master)
- [CFLib](https://github.com/freemint/freemint.github.io/tree/master/builds/cflib/master)
- [gemma](https://github.com/freemint/freemint.github.io/tree/master/builds/gemma/master)
- [MiNTbin](https://github.com/freemint/freemint.github.io/tree/master/builds/mintbin/master)
- [QED](https://github.com/freemint/freemint.github.io/tree/master/builds/qed/master)

## Get in touch

Right now, the best place to get in touch is the (new) [FreeMiNT Mailing List](https://sourceforge.net/p/freemint/mailman/freemint-discuss) where all (more or less) FreeMiNT related things are discussed. If you want to contribute or found a bug, check out [our wiki page](https://github.com/freemint/freemint/wiki/Newcomer%27s-corner#contributing) and/or [file an issue](https://github.com/freemint/freemint/issues).

The old mailing list can be found here: <http://mikro.atari.org/mint/index.html>, all the way back from 1993 to 2016/2017.

The archive above also contains the short-lived attempt to have an AtariForge-hosted mailing list (from 05/2016 to 10/2017).

## Acknowledgements
- Johann-Tobias Schäg, for kindly letting us have the `freemint` name on github
- Rob Mahlert, for keeping <http://sparemint.atariforge.net> alive for so long and offering his server and domain for Atari projects
