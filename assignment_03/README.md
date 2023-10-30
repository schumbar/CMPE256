# Feature Engineering Assignment: Audio Spectrograms

## Learning Objective
The core objective of this assignment is to practice feature engineering on audio data, specifically by working with spectrograms of wave files. We will utilize various techniques to analyze and visualize the frequency spectrum of sound.

## Tasks
The tasks involve using the `librosa` library for audio analysis and include the following:

1. **Displaying Spectrograms**: Utilize [`librosa.display.specshow`](https://librosa.org/doc/main/generated/librosa.display.specshow.html) to visualize different types of spectrograms (e.g., chromagram, mel-spectrogram).

2. **Mel-scaled Spectrogram**: Compute a mel-scaled spectrogram using [`librosa.feature.melspectrogram`](https://librosa.org/doc/main/generated/librosa.feature.melspectrogram.html).

3. **Short-time Fourier Transform (STFT)**: Perform an STFT using [`librosa.stft`](https://librosa.org/doc/main/generated/librosa.stft.html).

4. **Beat Tracking**: Implement a beat tracker with [`librosa.beat.beat_track`](https://librosa.org/doc/main/generated/librosa.beat.beat_track.html).

5. **Constant-Q Transform**: Compute the constant-Q transform of an audio signal using [`librosa.cqt`](https://librosa.org/doc/main/generated/librosa.cqt.html).

## Data

For this assignment, we are required to analyze audio files from NASA, available for download [here](https://www.nasa.gov/vision/universe/features/halloween_sounds.html). Specifically, we need to extract features from the following files:

- Kepler: Star KIC12268220C Light Curve Waves to Sound
- NASA - Kepler: Star KIC7671081B Light Curve Waves to Sound
- NASA - Whistler Waves
- Johns Hopkins APL - Parker Solar Probe - Whistler Mode Waves 2
- NASA - Audio from NASA’s Juno Mission: Europa Flyby

## Project Deliverables
All project deliverables related to this assignment are included in the `assignment_03` directory of this repository. The deliverables include the following:
1. README.md: A markdown file containing the assignment description, assignment tasks, and data included in the assignment.
2. CMPE256_Unstructured_Audio_and_Wave_Files.ipynb: A google colab notebook file consisting of all the work that was completed for this assignment. Please note that I've split up the notebook into sections by the file that we are analyzing. 


Include all your code, outputs (including visualizations of the spectrograms), and a brief analysis of the features observed in the audio files. Compare the different types of sound in terms of their frequency, rhythm, and any other patterns that you can identify from the spectrograms.