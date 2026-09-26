# my-ai-models

Public model files for my apps. One folder per app; each folder has a `manifest.json` (file list with size
and SHA-256) and a README with the licences of its models.

| Folder | App | Contents |
|---|---|---|
| [`khana-model/`](khana-model/) | Khana (offline Persian audiobook maker) | G2P (Homo-GE2PE, ONNX int8) + Piper voice `amir` — testing only |

Files are downloaded by the apps from `https://raw.githubusercontent.com/BazaiHassan/my-ai-models/main/<folder>/<path>`.
