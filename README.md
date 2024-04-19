# Ultrasonic_Jammer

In this repository, we provide the test results of our previous/latest ultrasonic jammer, and a commerical jammer with the use of two commerical Speech-to-Text (STT) models.Each figure contains the waveform diagram, spectrogram, and corresponding STT transcriptions using iFLYTEK and Otter.ai models. We also provide the recording wav files and the supported output txt files of two models.

## Description of Our Experiments

**Premise:**
- The experiment aims to assess the performance of an ultrasonic jammer in disrupting eavesdropping devices during simulated conversation scenarios in a meeting room.

**Experimental Procedure:**
- We are conducting multiple test experiments in a real conference room.
- Using Text-to-Speech (TTS) software, we are repeatedly playing the phrase 'one to ten' to simulate a genuine speaking scenario.
- The interference distance is set at 2 meters, approximating the placement of our device on the ceiling or at the center of a conference room table.
- To vary the difficulty of interference, we are positioning eavesdropping devices (Phones) differently: facing the disruptor directly, positioned sideways, facing the disruptor backward, and standing upright.
- We are demonstrating the jammer's effectiveness by presenting test results alongside a commercial jammer and the previous version in various scenarios using waveform diagrams, spectrograms, and speech-to-text (STT) transcriptions with iFLYTEK and otter.ai models.

**Conclusion:**
- Our jammer effectively disrupts both iFLYTEK and otter.ai STT models, preventing them from recognizing the 'one to ten' phrase when activated.
- Commercial jammers produce observable interference signals but are ineffective at preventing eavesdropping devices from capturing 'one to ten' messages.
- Notably, in one scenario (version 1) where the phone is positioned with its back facing the jammer, the jammer fails to disrupt the eavesdropping device's recording.

## Explanation of Directory Structure

```
Ultrasonic_Jammer
│
├── Results
│   ├── Backward-Commerical_Jammer.jpg
│   ├── Backward-Our_Jammer.jpg
│   ├── Backward-Version1-Our_Jammer.jpg
│   ├── Description of Phone positions.jpg
│   ├── Directly-Commerical_Jammer.jpg
│   ├── Directly-Our_Jammer.jpg
│   ├── Directly-Version1-Our_Jammer.jpg
│   ├── Sideaway-Commerical_Jammer.jpg
│   ├── Sideaway-Our_Jammer.jpg
│   └── Stand-Upright-Our_Jammer.jpg
│
├── Supported_Files
│   ├── Recording Audios
│   │   ├── Backward-Commerical_Jammer.wav
│   │   ├── Backward-Our_Jammer.wav
│   │   ├── Backward-Version1-Our_Jammer.wav
│   │   ├── Directly-Commerical_Jammer.wav
│   │   ├── Directly-Our_Jammer.wav
│   │   ├── Directly-Version1-Our_Jammer.wav
│   │   ├── Sideaway-Commerical_Jammer.wav
│   │   ├── Sideaway-Our_Jammer.wav
│   │   └── Stand-Upright-Our_Jammer.wav
│   ├── iFLYTEK
│   │   ├── Backward-Commerical_Jammer-iFLYTEK.txt
│   │   ├── Backward-Our_Jammer-iFLYTEK.txt
│   │   ├── Backward-Version1-Our_Jammer-iFLYTEK.txt
│   │   ├── Directly-Commerical_Jammer-iFLYTEK.txt
│   │   ├── Directly-Our_Jammer-iFLYTEK.txt
│   │   ├── Directly-Version1-Our_Jammer-iFLYTEK.txt
│   │   ├── Sideaway-Commerical_Jammer-iFLYTEK.txt
│   │   ├── Sideaway-Our_Jammer-iFLYTEK.txt
│   │   └── Stand-Upright-Our_Jammer-iFLYTEK.txt
│   └── otter.ai
│       ├── Backward-Commerical_Jammer_otter_ai.txt
│       ├── Backward-Our_Jammer_otter_ai.txt
│       ├── Backward-Version1-Our_Jammer_otter_ai.txt
│       ├── Directly-Commerical_Jammer_otter_ai.txt
│       ├── Directly-Our_Jammer_otter_ai.txt
│       ├── Directly-Version1-Our_Jammer_otter_ai.txt
│       ├── Sideaway-Commerical_Jammer_otter_ai.txt
│       ├── Sideaway-Our_Jammer_otter_ai.txt
│       └── Stand-Upright-Our_Jammer_otter_ai.txt
│
├── Poster_SP24.pdf
│ 
├── LICENSE
│
└── README.md
```


