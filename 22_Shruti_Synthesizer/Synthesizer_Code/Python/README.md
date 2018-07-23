- The code is built in Python 2.7 and tested on Ubuntu 16.04 and Ubuntu 17.04
- Development is in progress, however you can test the current version
- The code is MIDI based, thus you can use it with MIDI keyboard or Virtual MIDI events generater (E.g. VMPK)
- A guide to install dependencies:

  1).sudo apt-get install python-dev python-numpy python-setuptools libsndfile-dev   -> Python Libraries\\
  2).sudo apt-get install libasound2-dev                                             -> ALSA Header\\
  3).sudo pip install scikits.audiolab                                               -> For importing wav file\\
  4).sudo apt-get install libsamplerate0 libsamplerate0-dev                          -> Dependency for scikits.samplerate\\
  5).sudo pip install scikits.samplerate                                             -> For Re-Sampling the audio file\\
  6).sudo pip install pygame                                                         -> Main for Handler\\
  7).sudo apt-get install libjack-dev                                                -> Dependency for python-rtmidi\\
  8).sudo pip install python-rtmidi                                                  -> Dependency for MIDO\\
  9).sudo pip install mido                                                           -> For MIDI Keys detection\\
  10).sudo apt-get install python-pyqt5                                              -> PyQT-5 GUI Toolkit\\
  11).sudo pip install pyinstaller                                                   -> To make executable file\\