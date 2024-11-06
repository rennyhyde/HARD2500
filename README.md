# HARD 250O
HARD 2500 is a matrix-style MIDI CC modulation patcher for Max/MSP. It can be used to modulate a DAW such as Ableton or any other MIDI device.

**H**enry
**A**ngela
**R**enny
**D**evon
**2
5
0**
**O**rlando

## Installing
1. Download `HARD_2500.maxproj` and `\patchers\`
2. Double click `HARD_2500.maxproj` to open in Max 8
3. Open `HARD_2500_ModMatrix.maxpat` from the project window


## Use with Ableton Live
1. With Ableton Live open, click the `MIDI` button in the top right corner to enter MIDI mapping mode.
2. Select a parameter to map. This can be any knob, button, or slider in a VST or Ableton itself.
3. In Max, select a MIDI device. For Windows, use [LoopMIDI](https://www.tobias-erichsen.de/software/loopmidi.html) as an internal MIDI loopback. I believe MacOS has its own built-in MIDI loopback.
4. Start DSP in Max
5. With the slider disabled, set it to the MIDI CC channel that you want to link to the parameter you selected in Ableton.
6. Enable the slider to create the MIDI mapping in Ableton.
7. Go through this process of selecting a parameter and enabling a slider on that channel to complete your desired mappings. You can unlock the Max patch and fill in the labels with the parameters each channel is mapped to.