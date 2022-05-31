# Music-Player

It is GUI based application built using TKinter (Python) and other Python libraries. It contains some
basic features of a music app like add or delete a song, play, pause, next and previous song. Most of these
things were done using TKinter widgets but I had to use mutagen library to play the song and time library to
show the progress of the song and even time it.

**Imports** 

from tkinter import *

from tkinter.ttk import *

from tkinter import filedialog

import time

import pygame

from mutagen.mp3 import MP3

import tkinter.ttk as ttk


**Pygame**
The pygame library is an open-source module for the Python programming language specifically intended to help you make games and other multimedia applications. Built on top of the highly portable SDL (Simple DirectMedia Layer) development library, pygame can run across many platforms and operating systems.

**Mutagen**
Mutagen is a Python module to handle audio metadata. It supports ASF, FLAC, MP4, Monkey’s Audio, MP3, Musepack, Ogg Opus, Ogg FLAC, Ogg Speex, Ogg Theora, Ogg Vorbis,
True Audio, WavPack, OptimFROG, and AIFF audio files.
