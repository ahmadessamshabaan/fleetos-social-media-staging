# FleetOS Static Images — SAME Proven Video Media Path (ADD-ONLY)
Date: 2026-11-12 Dubai. Owner direction: use proven video publishing storage pipeline; leave all existing social/video assets, video post IDs, schedules, captions, status, ledger content and publishing process untouched.

## Verified canonical storage route
- Source-of-truth for social media creatives: GitHub repository `ahmadessamshabaan/fleetos-social-media-staging` (public).
- Existing media release/tag: `social-preview`, release URL https://github.com/ahmadessamshabaan/fleetos-social-media-staging/releases/tag/social-preview (release ID 405590778).
- Existing video files are GitHub Release assets, e.g. `FleetOS_DeliveryInvoice_HERO_AR_V4R2META_20261112.mp4`, consumed by Buffer through stable direct download URLs:
  `https://github.com/ahmadessamshabaan/fleetos-social-media-staging/releases/download/social-preview/<EXACT_ASSET_FILENAME>`.
- The source upload procedure on authorized Lenovo is `gh release upload social-preview <LOCAL_FILE_PATH> -R ahmadessamshabaan/fleetos-social-media-staging`; use the *same verified release/tag*, without `--clobber`, deleting, renaming or overwriting ANY video or earlier asset.
- Lenovo GitHub CLI full path when short `gh` is not on PATH: `C:\Users\LENOVO\AppData\Local\Microsoft\WinGet\Links\gh.exe`. Authenticated connection verified 2026-11-12. Release was independently read from GitHub with existing video assets. GitHub test video and test PNG direct download returned HTTP 200 in earlier preflight.
- Buffer organization `6ac62b8aca3423ac47ad535c`; IG `6ac62c6d6a5c39ccb63f2e50`; FB `6ac62c176a5c39ccb63f2b99`. Use Buffer only for scheduling, never Metricool. Video arc takes priority. All publishing remains governed by current 09:00 FleetOS Social Growth Manager automation and original six-video atomic rules.

## Static image naming and storage (addition only)
- Put image assets into the SAME `social-preview` release, *not* into the FleetOS application repo, Production filesystem, website deploy tree or a different media provider.
- Make image filenames unique and recognizable, e.g. `FleetOS_DeliveryInvoice_STATIC_AR_HUMAN_V1_20261112.png` and `FleetOS_DeliveryInvoice_STATIC_EN_HUMAN_V1_20261112.png`, separate from `*.mp4`. Use descriptive topic/language/style/version/date and never overwrite release assets.
- The local staging file can be under an isolated `social-static\ready` directory on authorized Lenovo; that is ONLY the upload source, not a replacement for the GitHub Release media store.
- Verify actual PNG/JPEG dimensions/file integrity, public URL returns HTTP 200, and import into Buffer image DRAFT/readback on Instagram *and* Facebook; do not schedule until exact related six-part VIDEO arc is approved, completed, and scheduled, and sufficient free queue capacity remains.
- Photo-realistic generated people must not be claimed to be real FleetOS customers/staff; screenshots and statistics must be grounded/clearly illustrative. Comply with AI content flags.
- Preserve independent per-asset SHA256/content fingerprint, linked video topic, URL, approval, Buffer draft/schedule IDs and publication statuses in a NEW additive ledger section. No reupload of completed videos.

## Verified limitations / gate
- Earlier 2026-11-12 temporary 1080x1350 PNG via this same GitHub release was successfully imported as an Instagram Buffer DRAFT and independently read back. Disposable test file and draft were deleted afterwards. This verified path, not actual production publication.
- Image files generated *inside ChatGPT's sandbox* are NOT automatically on the authorized Lenovo and have not yet been proven transferred into the GitHub release. They are therefore NOT in Buffer or published. Never claim otherwise.
- The previous DeliveryInvoice and InvoiceCash VIDEO arcs were still drafts, not scheduled, at prior check; four older video posts were in media-processing ERROR. Those historical video failures do not justify replacing the successful storage path.
- The currently approved realistic/human visual direction is a STYLE approval. Before any real media asset is uploaded, independently verify the exact content is appropriate and the route can transfer the bytes without inventing an upload.

## Action for Growth Manager
At daily run, use the existing video upload path for the separate images. If the exact local image exists on Lenovo: upload unique image to `social-preview`, verify URL, add native Buffer IMAGE draft with the appropriate language/platform, read back, then schedule only when the corresponding video arc is cleared. If the image only exists as a ChatGPT sandbox artifact and the authorized device lacks it, report `IMAGE_TRANSFER_BLOCKED` and keep the image unscheduled. Keep current video work unaffected. No new publisher, no separate task, no paid plan, no Production deploy.

## Scope of this update
Documentation and automation handoff only. No image production asset has been uploaded via this instruction, and no existing video or Buffer post has been touched.
