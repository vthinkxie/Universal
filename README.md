# Disney+ official English / Chinese subtitles

Personal Surge module based on DualSubs Universal v1.7.5 (Apache-2.0).

Select **English [CC]** in Disney+ to combine the original English and Chinese subtitle tracks. Chinese text uses 60% font size; English is unchanged. A Chinese track must exist for the title. No translation service is used.

Install `DisneyPlus-Official-EN-ZH.sgmodule` in Surge iOS, disable older Disney+ subtitle modules, and deploy the same module to Surge tvOS. Existing HTTPS decryption certificate setup is required.

The module contains no proxy credentials, device addresses, diagnostic uploads, or local-server dependencies. Subtitle matching caches stay on the device.

Changes: content-based HLS detection; native English option compatibility; guard unrelated playlists; fix the single-file subtitle queue logging error; Chinese-only WebVTT styling.
