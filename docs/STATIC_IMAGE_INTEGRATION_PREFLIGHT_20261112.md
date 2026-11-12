# FleetOS Static-Image Publishing — Additive Integration Preflight
Date: 2026-11-12 (Asia/Dubai)
Owner instruction: Preserve every existing video/caption/queue/schedule; ADD realistic, human-first static-image companion posts matching the day's verified video topic, plus separate reminders for previously published arcs. No production changes; no paid plans; Buffer only for publishing, Metricool read-only.

## Verified environment
- Buffer organization 6ac62b8aca3423ac47ad535c; Instagram channel 6ac62c6d6a5c39ccb63f2e50 and Facebook channel 6ac62c176a5c39ccb63f2b99, both connected/unpaused.
- Buffer scheduled queue: ZERO scheduled items at 2026-11-12 preflight; 12 video drafts (two 6-endpoint arcs: InvoiceCash and DeliveryInvoice) and four prior video posts in ERROR. Draft != scheduled.
- Failed videos: TripMargin Morning Nov 9 (IG+FB); QuotationHandoff Hero Nov 8 (IG+FB). Error responses mention video-media processing/specification, not proven root cause. Never retry failed posts blindly.
- Canonical video arcs require final audio/visual QC and six-endpoint atomic readiness before scheduling.
- Social GitHub staging repository is PUBLIC and authenticated GitHub CLI available on Lenovo DESKTOP-A24E792 through C:\Users\LENOVO\AppData\Local\Microsoft\WinGet\Links\gh.exe; authorized social-preview GitHub release exists. A sample existing release MP4 was independently reachable (HTTP 200) from Lenovo on 2026-11-12. This does NOT prove every asset works for Buffer.
- Human-style static creative generated in a separate ChatGPT conversation exists as a sandbox image; its local sandbox path is NOT automatically accessible from Lenovo or a public URL. Cannot claim uploaded/scheduled unless transferred and independently verified.
- Existing Buffer Free organization account reports a 10 scheduled-post limit; confirm per-channel queue allowance in live service before scheduling additional posts. Do not use image slots if they prevent the six-video arc.
- No new images have been uploaded to Buffer or scheduled as of this preflight.

## Mandatory additive gates for each static post
1. Read current Buffer scheduled/draft/error/sent and canonical social ledger. Select topic only from a VERIFIED corresponding video arc; no assumed publication.
2. Confirm exact final asset is approved visual direction (natural photography/human touches, legible Arabic/English, correct FleetOS branding). Use verified product visuals only; synthetic examples require suitable disclosure/avoid fabricated client claims. The approved image creative direction is NOT a blanket assertion that every generated image accurately represents product screens.
3. Put exact final JPEG/PNG into approved public social asset store on Lenovo using authenticated gh CLI or GitHub tool; check HTTP 200, image content-type, non-zero size and dimensions externally. No local/sandbox/preview/share URL passed into Buffer.
4. Verify buffer native image constraints, media URL import, correct platform metadata and any AI labeling. Consider creating a private/draft-only proof post before scheduling the first campaign image. Confirm readback; no false success reports.
5. Do NOT schedule a matching static post while corresponding video arc still draft/QC-blocked. Only after complete six-endpoint video scheduled, choose nonconflicting time and sufficient Buffer Free capacity. Preserve ALL existing video assets/posts.
6. For past-topic reminders use only verified SENT video URLs and separate dayparts, with a new useful angle and CTA. Deduplicate based on platform, topic, content hash/date.
7. Add separate static-image ledger section with exact asset link, SHA/identity, QC, topic, matching video post IDs, Buffer image post IDs/status, time, published URLs. Never rewrite historic ledger lines.
8. Report exact blocker instead of pretending that prompt update itself uploads/generates/schedules images.

## Current blockers / next actions
A. Transfer/host the actual approved static creative to a public media URL (no automatic sandbox-to-Lenovo transport confirmed). Test file upload and Buffer image import with a draft before scheduling.
B. Video DeliveryInvoice and InvoiceCash arcs are DRAFT, requiring final quality gate. Therefore companion image scheduling is currently intentionally BLOCKED.
C. Diagnose the four old media-processing errors via source file/container/codec/metadata validation, Buffer response and external URL test before attempting any retry; separate from new image track.
D. Check remaining free queue slots immediately prior to scheduling any additional image.

## 2026-11-12 LIVE PNG IMPORT PROOF — PASS (draft only)
- Authorized Lenovo created a disposable 1080x1350 PNG and uploaded it via authenticated `gh release upload social-preview` (exit code 0).
- Release asset direct URL returned HTTP 200 with nonzero payload (13,275 bytes; GitHub content type application/octet-stream; Buffer recognized actual MIME as image/png).
- Buffer Instagram create_post with image URL, `saveToDraft=true`, `schedulingType=automatic`, `metadata.instagram.type=post` returned DRAFT id 6af58f09f662733b84a70152, image dimensions 1080x1350, MIME image/png, error=null. Independent get_post readback confirmed identical status and media URL.
- Test draft DELETED from Buffer and disposable GitHub release asset DELETED, exit code 0. No public post or scheduled slot consumed.
- Scope: proves Lenovo→GitHub→Buffer Instagram DRAFT import, NOT production scheduling/delivery, NOT Facebook image import, and NOT transfer of generated sandbox image to Lenovo. Leave these as separate verifications.
- The four historical video errors remain; raw GitHub video URL was separately downloaded with HTTP 200, so URL disappearance is not established as their root cause. Source-media compatibility and provider processing must be tested rather than assumed.
