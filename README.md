# CJCNC-EX MIDI Note Counter Video Generator

Original program by Conjac Jelly Charlieyan.

CJCNC-EX is a mod by Pentagon-BeeHive-LoL.
- Fixed loading MIDIs that have an extreme lenght in ticks, no longer causing the OutOfMemoryException error.
- Fixed loading Tempo Tracks with an extreme amount of BPM Events. The original code used BubbleSort to sort the events which would take astronomical amounts of times with MIDIs that have an extreme amount of BPM Events. Now uses QuickSort which is much faster.

Mistake:
- Track size is showing total tracks amount value instead of actual track size values, I don't care enough to fix it.
