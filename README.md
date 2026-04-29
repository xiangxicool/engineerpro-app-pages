# Public Site Deployment Package

This folder contains the privacy and support pages required before App Store Connect upload.

GitHub Pages URL patterns after deployment:

- User/organization site repo: `https://<github-user>.github.io/privacy/236_cue_trim/`
- Project site repo: `https://<github-user>.github.io/<repo-name>/privacy/236_cue_trim/`

Required privacy/support paths:

- `/privacy/236_cue_trim/`
- `/support/236_cue_trim/`
- `/privacy/237_loop_budget/`
- `/support/237_loop_budget/`
- `/privacy/238_stud_span/`
- `/support/238_stud_span/`
- `/privacy/239_ping_ledger/`
- `/support/239_ping_ledger/`
- `/privacy/240_jsonl_desk/`
- `/support/240_jsonl_desk/`
- `/privacy/241_schedule_window/`
- `/support/241_schedule_window/`

App Store Connect should use the final public HTTPS URLs after GitHub Pages is enabled and verified.

## Generic local-tool URLs

For simple local-only utility apps with no account, no tracking, no ads, no third-party SDKs, no cloud processing, no permissions, and no IAP/subscription, these generic URLs may be used:

- Privacy Policy: `https://xiangxicool.github.io/engineerpro-app-pages/privacy/local-tool-apps/`
- Support URL: `https://xiangxicool.github.io/engineerpro-app-pages/support/local-tool-apps/`

Do not use the generic URLs for apps that request camera, microphone, photo library, location, local network, Bluetooth, contacts, health, calendar, account login, cloud sync, analytics, ads, tracking, subscriptions, or in-app purchases. Those apps need app-specific pages.
