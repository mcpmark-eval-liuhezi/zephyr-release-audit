# Zephyr Release Audit Notes

## Date
2026-10-22 (weekly release audit)

## Step 1 — Base model audit (Hugging Face)

- **Credentials resolve to Hugging Face account:** [@lhz7891444](https://huggingface.co/lhz7891444) (account ID `68805cebc41d25c21ef2183e`, user account)
- **Base model audited:** `google-bert/bert-base-uncased`
- **Parameter count stated on the model card:** 110M

### Current repository file listing

| Type | Path | Size |
|---|---|---|
| dir | coreml/ | — |
| file | .gitattributes | 491 B |
| file | LICENSE | 11.4 KB |
| file | README.md | 10.5 KB |
| file | config.json | 570 B |
| file | flax_model.msgpack | 438.1 MB (LFS) |
| file | model.onnx | 532.1 MB (LFS) |
| file | model.safetensors | 440.4 MB (LFS) |
| file | pytorch_model.bin | 440.5 MB (LFS) |
| file | rust_model.ot | 534.2 MB (LFS) |
| file | tf_model.h5 | 536.1 MB (LFS) |
| file | tokenizer.json | 466.1 KB |
| file | tokenizer_config.json | 48 B |
| file | vocab.txt | 231.5 KB |

## Step 2 — GitHub audit deliverable

- Repository: `mcpmark-eval-liuhezi/zephyr-release-audit` (public)
- Branch: `release-notes` (off `main`)
- Notes file: `RELEASE_NOTES.md`
- Pull request: "Add Zephyr release notes" from `release-notes` into `main`
- After the pull request was opened, a housekeeping commit was pushed to `main`, and the pull request branch was updated from the default branch to confirm the sync took effect.

## Step 3 — Hand-off deadline

- Deadline: 17:00 Beijing time (Asia/Shanghai) — 2026-10-23 17:00 +08:00 (Friday)
- Naoko Tanaka (QA reviewer, Tokyo, Asia/Tokyo): **2026-10-23 18:00 +09:00 (Friday)**
- UTC: **2026-10-23 09:00 UTC (Friday)**
