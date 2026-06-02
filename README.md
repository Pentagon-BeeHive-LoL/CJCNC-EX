# CJCNC-EX MIDI Note Counter Video Generator
CJC's MIDI Note Counter Generator, modified and optimized for MIDIs with extreme tick lenghts or extreme BPM events.

CJC's MIDI Note Counter (CJCNC) by Conjac Jelly Charlieyan.

CJCNC-EX is a mod by PentagonBee.
- Fixed loading MIDIs that have an extreme lenght in ticks, no longer causing the OutOfMemoryException error.
- Fixed loading Tempo Tracks with an extreme amount of BPM Events. The original code used BubbleSort to sort the events which would take astronomical amounts of times with MIDIs that have an extreme amount of BPM Events. Now uses QuickSort which is much faster.
