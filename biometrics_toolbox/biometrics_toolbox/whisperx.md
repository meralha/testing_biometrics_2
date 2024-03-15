## <i class="fas fa-hammer"></i> Speech to Text 

To generate a transcript of your audio file, you can run the following commands in your terminal:

```bash

whisperx $audio --model large-v2 --align_model WAV2VEC2_ASR_LARGE_LV60K_960H --batch_size 16

```
# WhisperX: Automatic Speech Recognition

## Introduction

WhisperX is an automatic speech recognition system developed by OpenAI. It provides fast transcription (70x realtime with large-v2) with word-level timestamps and speaker diarization[^1^][4].

## Features

- **Multispeaker ASR**: WhisperX uses speaker diarization from pyannote-audio, which allows it to identify different speakers in an audio file[^1^][4].
- **VAD Preprocessing**: This feature reduces hallucination and batching with no WER degradation[^1^].

## Installation

You can install WhisperX by following these steps[^1^][4]:

1. Create a Python3.10 environment: 
    ```
    conda create --name whisperx python=3.10
    conda activate whisperx
    ```
2. Install PyTorch:
    ```
    conda install pytorch==2.0.0 torchaudio==2.0.0 pytorch-cuda=11.8 -c pytorch -c nvidia
    ```
3. Install WhisperX:
    ```
    pip install git+https://github.com/m-bain/whisperx.git
    ```

## Conclusion

WhisperX is a powerful tool for automatic speech recognition. Its ability to provide word-level timestamps and speaker diarization makes it a valuable resource for transcribing long audio files.
