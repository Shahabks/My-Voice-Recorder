# My-Voice-Recorder
### Capturing Microphone Data into an Audio File

**My-Voice-Recorder** is a convenient and simple python package that can
be used right in your machine. It allows you to record your voice using a microphone 
and save it as a wav file. 

My-Voice-Recorder was originally designed as a voice recorder for acoustic and language 
research or creative endeavors. It was tested for our Automatic language identification 
package and has a **flexible adjustable and simple features** for manual control which make 
it more **adaptable for specific needs**. 
These features not only make the device easier to use in an original environment, they 
also help for optimum file storage opportunities.

My-Voice-Recorder records in **a wide range of quality** such as CD-quality 16 or 24-bit 
linear PCM or other formats and automatically detect your machine's microphones. 
These are adjustable for varied stereo depth depending on your recording needs. It 
could support multi-track recording, all of which are great features for creative 
projects, as they allow for more control over the audio layers. 
The main **downside** to My-Voice-Recorder is that it does not include voice activation or 
dead air removal.

Adding an **external microphone** is the single most significant way to improve the quality
of the sound your machine captures. To give the voice recordings top-level audio, you'll 
need to get a standard mic.

MY-Voice-Recorder works with USB better though it is not a must. While the microphone quality 
usually serves as a good indicator of recorded voice quality, a few mic factors have an 
impact. Checking the mic frequency response (the range of sounds it can hear) and sampling rate.

## Installation

My-Voice-Recorder can be installed like any other Python library, using (a recent version of) the
Python package manager pip, on Linux, macOS, and Windows:

            pip install myVOCRec

or, to update your installed version to the latest release:

            pip install -u myVOCRec	

Recording files must be 25 sec. or longer of audio and in *.wav PCM/LPCM format, recorded at 48 kHz 
sample frame and 24-32 bits of resolution or AIFF, AIFF-C, FLAC: must be native FLAC format; 
OGG-FLAC is not supported.

## How it works

Import in the Windows Command-Line or a notebook page:

           [in 1] import myVOCRec as mc
           [in 2] mc 

and click run

            [in 3] Enter the path to the datasets/audio files directory: 
                   C:\Users\ta\Desktop\myLanguageIdentification\dataset\audioFiles
            [in 4] what is your name?    sandy  # your audio file name in fact
            [in 5] Your desired Recording time in seconds:    26                    # in sec. you can set for hours or few seconds.
            [in 6] sampling rate; 16000 or 42000 or 48000 or 96000 Hz:    48000
            [in 7] bit depth; 8 or 16 or 24 or 32 bit:    24
          
 and run.
 
             [Out 1] ===========================================
                        HOLD ON!! get ready, 5 seconds to go! 
                     =========================================== 
                     00:05  to 00:00            # get ready 5 sec.
                     Recording start!
                     00 : 26                    # set recording timer 
                     00 : 00                    #press any key to exit

please check out https://github.com/Shahabks/my-voice-recorder 

myVOCRec was developed by MYOLUTION Lab in Japan. It is being used internally where the quality of 
utterances is crucial for our Voice Recognition and Acoustic & Language modeling Project in the Lab. 
We plan to enrich the quality of myVOCRec by adding more advanced functions.
