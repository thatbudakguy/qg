# Old Audio Settings

## Discord

- Input: MOTU Mix 1 Return
- Output: MOTU Phones 1
- Input mode: Voice Activity
- Input sensitivity: manual, about -72 db: set based on ambient level
- Turn off all noise canceling/reduction/etc so that music sounds normal
- Automatic Gain Control must be on or input is too quiet
- QoS and attenuation are off

## Windows

- Main audio device (taskbar): MOTU Analog
- Set windows media player to play through default audio device

## CueMix DSP

- Load "default" preset:
    - Bus 1 routes Analog in 1/2 and Mic in 1, both at -18db, to Main Outs
    - Bus 2 routes Analog in 1/2 only at -18db to Phones
- Set Phones to "Phones"
- All Analog ins are stereo pairs
- Analog out 1/2 (PC audio) are routed via cable to Analog in 1/2

## MOTU Console

- Sample Rate: 44.1k (it seems to switch back to this on its own?)
- Samples per buffer: 512
- UNcheck "use stereo pairs for windows audio"; otherwise can't send to Analog
- Check "use WaveRT for windows audio" (newer driver?)
- Phones assignment: Phones 1-2