TODO before releasing _pyo_ version 1.0.

# TODO #

**Server**

- Add a method to retrieve a graph of the internal state of the server (active objects, connections, attribute states, ...)


---


**Envelope generators**

- Add a pause() method. Keep the internal phase of the envelope.


---


**GUI**

- MixerGui (matrix for setting dsp graph)

- Implement Jack MIDI


---


**Midi**

- Midiout, MidiFileRead


---


**New objects**

  * Granulator2(multi-streams)
  * TrigGrains(one-stream and multi-stream)
  * FreqShift
  * CrossPM, CrossFMPM
  * TrigMarkov (PyoTable)
  * SfMarkerTrigger
  * MatrixSetCol (make sure that there is only one value in a column, others are 0)
  * TrigProb (uses a matrix as a probability distribution (work with MatrixSetCol))
  * ExpFader
  * TrigRec, TrigRead
  * Expander
  * VoiceSynth