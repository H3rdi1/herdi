# Neural voice attribution

Speech generated with Piper high-quality VITS neural synthesis and the official
LibriTTS-high 904-speaker model, published by rhasspy/Piper.
Model: https://github.com/rhasspy/piper/releases/download/v0.0.2/voice-en-us-libritts-high.tar.gz
Training data: LibriTTS train-clean-360, https://www.openslr.org/60/
Dataset attribution: Heiga Zen, Viet Dang, Rob Clark, Yu Zhang, Ron J. Weiss,
Ye Jia, Zhifeng Chen, and Yonghui Wu. "LibriTTS: A Corpus Derived from LibriSpeech
for Text-to-Speech," Interspeech 2019.
License stated in the official MODEL_CARD: Creative Commons Attribution 4.0.
https://creativecommons.org/licenses/by/4.0/

Developer: LibriTTS speaker 4535, model index 2.
Codex: LibriTTS speaker 28, model index 26.
Both recordings are newly synthesized performances; no cloned user voices,
creator audio, or licensed music samples are used.
No pitch shifting, whisper effects, or synthetic eSpeak waveform is used.
Piper uses eSpeak solely for text phonemization before neural acoustic synthesis.

Piper TTS engine 1.8.0: GPL-3.0-or-later; ONNX Runtime inference.
Model binaries are kept as development dependencies outside this asset folder.
The delivered WAVs and timing manifest are self-contained for editing/rendering.
