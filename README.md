# WhisperLab

目的：在同一条音频上对比 openai-whisper 和 faster-whisper，
分别测试不带 prompt、带 prompt、带 prompt + 热词三种情况，并记录模型、版本、设备、beam size。

- Python 3.12（虚拟环境在 .venv/）
- 音频和转写结果不入库（见 .gitignore）
