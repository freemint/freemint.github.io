## Welcome to the FreeMiNT Project website

This website is a frontend for the [freemint github repositories](https://github.com/freemint). If you would like to know more about FreeMiNT, the best place to start is [the wiki](https://github.com/freemint/freemint/wiki). Best place to download/try latest builds is [snapshots](#snapshots).

## FreeMiNT Project

FreeMiNT project is a community based hub for several more or less related projects:

- [FreeMiNT](https://github.com/freemint/freemint) (kernel)
- [XaAES](https://github.com/freemint/freemint/tree/master/xaaes) (multitasking GEM AES replacement, part of FreeMiNT now)
- [MiNTlib](https://github.com/freemint/mintlib) (libc for FreeMiNT and TOS, a C standard library)
- [FDlibm](https://github.com/freemint/fdlibm) (libm for FreeMiNT and TOS, a C math library)
- [GEMlib](https://github.com/freemint/gemlib) (GEM bindings for writing GEM apps)
- [MiNTbin](https://github.com/freemint/mintbin) (set of, mostly deprecated, tools for manipulation of (Free)MiNT binaries)
- [git](https://github.com/freemint/git) (experimental fork for FreeMiNT of the popular version control system)
- [m68k-atari-mint-gcc](https://github.com/freemint/m68k-atari-mint-gcc) (gcc for FreeMiNT)
- [m68k-atari-mint-binutils-gdb](https://github.com/freemint/m68k-atari-mint-binutils-gdb) (binutils and gdb for FreeMiNT)
- [freemint.github.io](https://github.com/freemint/freemint.github.io) (project website sources, you're reading it)

Those are the main (and most important) projects. There are several affiliated repositories, either for historical reasons or because the former SpareMiNT CVS server hosted them (the first section belongs to projects which are still actively maintained):

- [libcmini](https://github.com/freemint/libcmini) (minimalistic C library)
- [CFLib](https://github.com/freemint/cflib) (extension library for GEM programming)
- [gemma](https://github.com/freemint/gemma) (SLB based GEM library)
- [TosWin2](https://github.com/freemint/toswin2) (GEM terminal emulator)
- [QED](https://github.com/freemint/qed) (GEM text editor)
- [COPS](https://github.com/freemint/cops) (XCONTROL.ACC replacement)
- [HypView](https://github.com/freemint/hypview) (ST-Guide replacement)
- [fVDI](https://github.com/freemint/fvdi) (Fenix VDI, a free (N)VDI replacement)
- [TeraDesk](https://github.com/freemint/teradesk) (Tera Desktop, an open-source alternative desktop)
- [tos.hyp](https://github.com/freemint/tos.hyp) (most complete programmer's reference for TOS/GEM programming, generated [here](https://freemint.github.io/tos.hyp))

- [HighWire](https://github.com/freemint/highwire) (GEM web browser)
- [Phoenix](https://github.com/freemint/phoenix) (database GEM app)
- [Smurf](https://github.com/freemint/smurf) (GEM painting app)
- [oVDI](https://github.com/freemint/ovdi) (Odd Skancke's VDI project)
- [vlogin](https://github.com/freemint/vlogin) (VDI login)
- [xg](https://github.com/freemint/xg) (X11 6.4 for GEM)
- [init](https://github.com/freemint/mintinit) (/sbin/init and related programs)
- [init scripts](https://github.com/freemint/initscripts) (basic shell scripts for system startup)
- [wiki tools](https://github.com/freemint/wikitools) (a couple of scripts to convert between UDO and old sparemint wiki)
- [sparemint](https://github.com/freemint/sparemint) (SpareMiNT website and archive, predecessor of this hub; github mirror [here](https://freemint.github.io/sparemint/sparemint))

## Download
### Releases

Official releases (mostly source only):
- [FreeMiNT and XaAES](https://github.com/freemint/freemint/releases) (most complete release archive)
- [MiNTlib](https://github.com/freemint/mintlib/releases)
- [FDlibm](https://github.com/freemint/fdlibm/releases)
- [GEMlib](https://github.com/freemint/gemlib/releases)
- [MiNTbin](https://github.com/freemint/mintbin/releases)
- [git](https://github.com/freemint/git/releases)
- [m68k-atari-mint-gcc](https://github.com/freemint/m68k-atari-mint-gcc/releases)
- [m68k-atari-mint-binutils-gdb](https://github.com/freemint/m68k-atari-mint-binutils-gdb/releases)

- [libcmini](https://github.com/freemint/libcmini/releases)
- [CFLib](https://github.com/freemint/cflib/releases)
- [gemma](https://github.com/freemint/gemma/releases)
- [TosWin2](https://github.com/freemint/toswin2/releases)
- [QED](https://github.com/freemint/qed/releases)
- [COPS](https://github.com/freemint/cops/releases)
- [HypView](https://github.com/freemint/hypview/releases)
- [fVDI](https://github.com/freemint/fvdi/releases)
- [TeraDesk](https://github.com/freemint/teradesk/releases)

### Snapshots

FreeMiNT hasn't got a proper release since the 1.18.0 version in 2013 due to lack of dedicated maintainer(s). Therefore if you want to try FreeMiNT, download one of the binary snapshots (built after each commit):
- FreeMiNT and XaAES [ ![Download](download.png) ](https://tho-otto.de/snapshots/freemint/bootable/) - bootable, preconfigured and maintained FreeMiNT/XaAES archives for the ST, 020+ machines with the FPU, ARAnyM and the FireBee
- FreeMiNT and XaAES [ ![Download](download.png) ](https://tho-otto.de/snapshots/freemint/cpu/) - per-CPU builds, if you prefer just upgrading an existing installation on your machine, do not include a desktop nor other non-freemint applications
- USB drivers for TOS [ ![Download](download.png) ](https://tho-otto.de/snapshots/freemint/usb4tos/)
- MiNTlib [ ![Download](download.png) ](https://tho-otto.de/snapshots/mintlib)
- FDlibm [ ![Download](download.png) ](https://tho-otto.de/snapshots/fdlibm)
- GEMlib [ ![Download](download.png) ](https://tho-otto.de/snapshots/gemlib/)
- MiNTbin [ ![Download](download.png) ](https://tho-otto.de/snapshots/mintbin/)
- CFLib [ ![Download](download.png) ](https://tho-otto.de/snapshots/cflib/)
- gemma [ ![Download](download.png) ](https://tho-otto.de/snapshots/gemma/)
- TosWin2 [ ![Download](download.png) ](https://tho-otto.de/snapshots/toswin2/)
- QED [ ![Download](download.png) ](https://tho-otto.de/snapshots/qed/)
- COPS [ ![Download](download.png) ](https://tho-otto.de/snapshots/cops/)
- HypView [ ![Download](download.png) ](https://tho-otto.de/snapshots/hypview/)
- fVDI [ ![Download](download.png) ](https://tho-otto.de/snapshots/fvdi/)
- TeraDesk [ ![Download](download.png) ](https://tho-otto.de/snapshots/teradesk/)

## Get in touch

Right now, the best place to get in touch is the (new) [FreeMiNT Mailing List](https://sourceforge.net/p/freemint/mailman/freemint-discuss) where all (more or less) FreeMiNT related things are discussed. If you want to contribute or found a bug, check out [our wiki page](https://github.com/freemint/freemint/wiki/Newcomer%27s-corner#contributing) and/or [file an issue](https://github.com/freemint/freemint/issues).

However if you have a more generic question or you would like to simply reach as many users as possible, feel free to use [FreeMiNT support section](https://www.atari-forum.com/viewforum.php?f=126) on Atari Forum.

The old mailing list can be found here: <http://mikro.atari.org/mint/index.html>, all the way back from 1993 to 2016/2017.

The archive above also contains the short-lived attempt to have an AtariForge-hosted mailing list (from 05/2016 to 10/2017).

## Acknowledgements
- Johann-Tobias Schäg, for kindly letting us have the `freemint` name on github
- Rob Mahlert, for keeping <http://sparemint.atariforge.net> alive for so long and offering his server and domain for Atari projects
