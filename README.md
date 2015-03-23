# OpenHantek (aka openhantek)
"OpenHantek is a free software for Hantek (Voltcraft/Darkwire/Protek/Acetech)
USB DSOs based on HantekDSO. The UI is written in C++/Qt 4 and uses OpenGL to
draw the graphs. It was tested with the DSO-2090." @ http://www.openhantek.org/


# Building:
Building procedure the same as for https://github.com/schlagenhauf/openhantek
- Required: QT4, libusb 0.1.x or 1.0.x, fftw 3, OpenGL
- 1. Check if you build with qt4: qmake --version. If not, use qmake-qt4
- 2. make. If you run into errors, setting the environment variable QT_SELECT=4
     might help. If you use libusb 0.1.x, set LIBUSB_VERSION=0
     After an unsuccessful build, delete the bin and build folder before
     building.
- 3. Done


# Status:
- This repository (at least 'initial commit') is full copy of SVN revision #69
  taken from SourceForge (http://sourceforge.net/p/openhantek/code/HEAD/tree/).
- Last changes to those SVN repository #69 was done by Oliver Haag at 2013.04.11,
  and nothing changed so far (this is true as for now -- 23.03.2015).


# Authors
1. The OpenHantek project was ported from HantekDSO and futher developed (and
   maintained) by Oliver Haag <oliver.haag@gmail.com>.

2. Primary project HantekDSO (avaliable on SourceForge at 23.03.2015, on page
   http://sourceforge.net/p/hantekdso/code/HEAD/tree/) is produced by authors
   Oleg Khudyakov <prcoder@gmail.com>
   Thomas Gerner <thomas.gerner@muenchen-mail.de>
   as it mentioned in AUTHORS file of HantekDSO project.
