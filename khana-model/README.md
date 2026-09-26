# khana-model

Model pack for the Khana app (testing only). `manifest.json` lists every file with its size and SHA-256;
the app downloads `https://raw.githubusercontent.com/BazaiHassan/my-ai-models/main/khana-model/<path>`.

| Path | What | Licence |
|---|---|---|
| g2p/ | Homo-GE2PE (MahtaFetrat/Homo-GE2PE-Persian), exported to ONNX, int8 | MIT, © 2025 Elnaz Rahmati |
| voices/amir/ | Piper `fa_IR-amir-medium` (rhasspy/piper-voices), graph extended with a `durations` output | MIT |

The amir voice was fine-tuned from the research-only lessac voice; it is used here for development only.
