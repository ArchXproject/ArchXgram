# ArchXgram

Unofficial Telegram client for Android with **20-account** multi-login.

- Based on [Nekogram](https://github.com/Nekogram/Nekogram) (GPLv2), which is based on [Telegram for Android](https://github.com/DrKLO/Telegram)
- App ID: `com.archx.gram` (debug: `com.archx.gram.beta`)
- Max accounts: 20
- API ID / hash: own (via `local.properties`, never committed)
- Builds: `.github/workflows/archxgram.yml` (debug APK artifact)

## Changes from Nekogram

- `UserConfig.MAX_ACCOUNT_COUNT` 8 → 20, `getMaxAccountCount()` → 20
- App name / package / APK name rebranded to ArchXgram
- User-facing strings rebranded (keys untouched), update/download links pointed here
- Donation config removed

## License

GPLv2 (same as upstream). `LICENSE` kept. Upstream credits belong to Nekogram and Telegram teams.
