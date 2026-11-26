# AutoMorph Patched Builds

![Active Apps](https://img.shields.io/badge/Active_Apps-4-20cfce?style=flat-square) ![Architecture](https://img.shields.io/badge/Arch-arm64-v8a-4A7FC8?style=flat-square) ![Signing Cert](https://img.shields.io/badge/Signing_Cert-97c5c6b996e6-10B981?style=flat-square) ![Obtainium Ready](https://img.shields.io/badge/Obtainium-Ready-6366F1?style=flat-square)

Automated Android APK builds patched locally with **AutoMorph** & **Morphe Desktop** and distributed via GitHub Releases.

> [!TIP]
> **Quick-Install with Obtainium (1-Click Import)**
> 1. Copy or import the config URL: `https://github.com/LoginRs99/automorph-builds/releases/download/automorph-config/obtainium-github-export.json`
> 2. In Obtainium, open **Import/Export → Obtainium Import** (`Verify Latest Tag: OFF` is pre-configured for all apps).
> 3. *(Private repo only)* Add a read-only GitHub PAT under **Settings → Source-Specific → GitHub PAT**.
>
> Browse: [**CHANGELOG.md**](./CHANGELOG.md) · [**catalog.json**](./catalog.json)

## Available Builds

| App | Version | Size | Android SDK | Patches | Updated (UTC) | Download |
| --- | --- | --- | --- | --- | --- | --- |
| **com.reddit.frontpage** (`com-reddit-frontpage`) | `v2026.45.0` | 129.52 MB | API 32–36 | 32 | 2026-11-26 | **[⬇ Download APK](https://github.com/LoginRs99/automorph-builds/releases/download/com.reddit.frontpage-v2026.45.0/com.reddit.frontpage-2026.45.0-arm64-v8a-morphe.apk)** |
| **com.twitter.android** (`x-lg`) | `v12.19.1-release.0` | 213.79 MB | API 28–35 | 69 | 2026-11-26 | **[⬇ Download APK](https://github.com/LoginRs99/automorph-builds/releases/download/x-lg-v12.19.1-release.0/x-lg-12.19.1-release.0-arm64-v8a-morphe.apk)** |
| **com.zhiliaoapp.musically** (`com-zhiliaoapp-musically`) | `v47.9.3` | 235.08 MB | API 23–36 | 137 | 2026-11-26 | **[⬇ Download APK](https://github.com/LoginRs99/automorph-builds/releases/download/com.zhiliaoapp.musically-v47.9.3/com.zhiliaoapp.musically-47.9.3-arm64-v8a-morphe.apk)** |
| **YouTube LG** (`youtube-lg`) | `v21.45.82` | 170.14 MB | API 32–37 | 114 | 2026-11-26 | **[⬇ Download APK](https://github.com/LoginRs99/automorph-builds/releases/download/com.google.android.youtube-v21.45.82/com.google.android.youtube-21.45.82-arm64-v8a-morphe.apk)** |

## Expandable App Cards

<details><summary><strong>com.reddit.frontpage</strong> (<code>com.lg.reddit</code> — v2026.45.0)</summary>

| Property | Value |
| --- | --- |
| **Source Package** | `com.reddit.frontpage` |
| **Patched Package** | `com.lg.reddit` |
| **Version Code** | `2147483647` |
| **Morphe Engine** | `2.1.0` |
| **APK SHA-256** | `6723b8bae065baf158b50a07b5aa4b6de90ec4d8f1a572c2e8d475fe2a615aa6` |
| **Signing Cert SHA-256** | `97c5c6b996e6e589bb8d0ad097587395637c1d05e5b1c15467f08b1fa78aad3a` |
| **Patch Sources** | `https://github.com/MorpheApp/morphe-patches` |

**Applied Patches:**
- App icon
- Clone app
- Copy text
- Custom branding name for Reddit
- Custom font
- Customize post layout
- Disable Play Store updates
- Disable modern home
- Disable screenshot popup
- Download location
- Feed media max height
- Force system font
- Full width feed media
- Hide Ask button
- Hide Trending shelves
- Hide ads
- Hide communities shelf
- Hide media viewer components
- Hide navigation buttons
- Hide sidebar components
- High quality avatars
- Keep feed position
- Media viewer black background
- Media viewer fade
- Open links directly
- Open links externally
- Redgifs audio
- Remember collapsed comments
- Remove subreddit dialog
- Sanitize sharing links
- Show flairs in home feed
- Spoof signature

</details>

<details><summary><strong>com.twitter.android</strong> (<code>com.twitter.android</code> — v12.19.1-release.0)</summary>

| Property | Value |
| --- | --- |
| **Source Package** | `com.twitter.android` |
| **Patched Package** | `com.twitter.android` |
| **Version Code** | `2147483647` |
| **Morphe Engine** | `2.3.0` |
| **APK SHA-256** | `bdf9cae2e4d9ba591c21d934a07b5a85ca6941f2b54f8ee8dc00f586ac1aa777` |
| **Signing Cert SHA-256** | `97c5c6b996e6e589bb8d0ad097587395637c1d05e5b1c15467f08b1fa78aad3a` |
| **Patch Sources** | `https://github.com/crimera/piko` |

**Applied Patches:**
- Add ability to copy media link
- Block redirecting to X Lite
- Block update screen
- Clear tracking params
- Control video auto scroll
- Custom download folder
- Custom emoji font
- Custom font
- Custom share menu
- Custom sharing domain
- Customise post font size
- Customize Inline action Bar items
- Customize Navigation Bar items
- Customize default reply sorting
- Customize explore tabs
- Customize notification tabs
- Customize profile tabs
- Customize search suggestions
- Customize search tab items
- Customize side bar items
- Customize timeline top bar
- Delete from database
- Disable Play Store updates
- Disable auto timeline scroll on launch
- Disable chirp font
- Download patch
- Enable Undo Posts
- Enable debug menu for posts
- Enable force HD videos
- Force enable translate
- Handle custom twitter links
- Hide Banner
- Hide FAB
- Hide FAB Menu Buttons
- Hide Live Threads
- Hide Recommended Users
- Hide badges from navigation bar icons
- Hide bookmark icon in timeline
- Hide community badges
- Hide followed by context
- Hide hidden replies
- Hide immersive player
- Hide nudge button
- Hide post metrics
- Hide promote button
- Hide recommendation items
- Hook feature flag
- Import/Export login token
- Legacy share links
- Log server response
- More information on profile
- Native downloader
- Native reader mode
- Native translator
- No shortened URL
- Pause search suggestions
- Remove Ads
- Remove premium upsell
- Remove search suggestions
- Remove view count
- Restore legacy follower lists
- Round off numbers
- Selectable Text
- Share Tweet as Image
- Show changelogs
- Show poll results
- Show post source label
- Show sensitive media
- Support external downloader

</details>

<details><summary><strong>com.zhiliaoapp.musically</strong> (<code>com.zhiliaoapp.musically</code> — v47.9.3)</summary>

| Property | Value |
| --- | --- |
| **Source Package** | `com.zhiliaoapp.musically` |
| **Patched Package** | `com.zhiliaoapp.musically` |
| **Version Code** | `2147483647` |
| **Morphe Engine** | `2.3.0` |
| **APK SHA-256** | `ffeb958de9e36e9d0e264cb35539ebd077f4c7143634f33afb5df36b9b2f65a4` |
| **Signing Cert SHA-256** | `97c5c6b996e6e589bb8d0ad097587395637c1d05e5b1c15467f08b1fa78aad3a` |
| **Patch Sources** | `https://github.com/SysAdminDoc/hushfeed` |

**Applied Patches:**
- Account cleanup
- Allow Duet and Stitch
- Allow screenshots and Circle to Search
- Always show publish date
- Always upload in HD
- App lock
- Automatic video advance
- Block author button
- Block contact list access
- Block installed app scanning
- Block popups
- Block suggested video notifications
- Camera and microphone indicator
- Comment publish diagnostics
- Comment send fix
- Comment sort controls
- Comment tools
- Confirm feed interactions
- Copy bio and IDs
- Copy comments without username
- Create stickers
- Custom offline videos limit
- Device privacy guard
- Diagnostic tools
- Disable login requirement
- Disable screen capture detection
- Disable telemetry
- Disable the long press quick share
- Disable the long press repost
- Double-tap controls
- Downloads
- Drop the animated image cache
- Enable voice comments
- Expand activity list
- Feature Gate Lab
- Feed filter
- Feed tab navigation
- Feed text sizes
- Fit the video to the screen
- Fix Google login
- Fix Spotify login
- Fix notifications on OPPO, OnePlus and realme
- Foldable split comment view
- Follow diagnostics
- Freeze TikTok's experiments
- Ghost mode
- Group likes per comment
- Hide CAPTCHA popups
- Hide Play Store update offer
- Hide already seen videos
- Hide comment popup ads
- Hide comment typing suggestions
- Hide feed LIVE button
- Hide feed follow button
- Hide feed save button
- Hide feed search button
- Hide floating promotions
- Hide inbox items
- Hide inbox stories
- Hide profile shortcuts
- Hide read receipts
- Hide search suggestions
- Hide suggested accounts
- Hide the launcher shortcuts
- Hide video overlays
- Hold-and-slide 2x lock
- In-app browser privacy guard
- Keep a streak going
- Keep playing in the background
- Keep pulled sounds
- Keep recent stickers
- Keep the Favorites tab
- Keep the app language
- Keep the next videos in full screen
- Keep the screen's brightness in the camera
- Keep the screen's refresh rate
- Keep unsent messages
- LIVE controls
- Lift text length limits
- Limit background traffic
- Load all saved stickers
- Location access governor
- Long-press controls
- Mute feed videos
- Network proxy
- Not interested button
- Notification controls
- Open external links directly
- Open the comments at full height
- Picture-in-picture
- Play SDR instead of HDR
- Play original audio
- Playback quality
- Playback speed
- Prefer H.264 playback
- Profile background
- Remember clear display
- Remove avatar rings
- Report a newer phone to effects
- Report a newer phone to game LIVE
- Repost diagnostics
- Resource and battery governor
- Resume videos after scrolling
- SIM spoof
- Sanitize sharing links
- Settings
- Share sheet tools
- Show LIVE search
- Show author region
- Show commenter handle and region
- Show engagement rate
- Show exact counts
- Show follow status
- Show the progress bar
- Show the progress bar thumbnail
- Skip content warnings
- Skip passkey sign-in
- Skip the splash ad
- Skip update checks
- Smaller text sizes
- Split activity list
- Stay on the video in full screen
- Stop on-device AI profiling
- Stop recording watch history
- Stop saving search history
- Stop search autoplay
- Stop video looping
- Story controls
- Subtitle tools
- Swipe-left controls
- Translate comments
- Turn off haptics
- Turn off screen transitions
- Turn profiles and comment pictures on tablets
- UI scale
- Use non-personalized search
- Use system font

</details>

<details><summary><strong>YouTube LG</strong> (<code>com.lg.youtube</code> — v21.45.82)</summary>

| Property | Value |
| --- | --- |
| **Source Package** | `com.google.android.youtube` |
| **Patched Package** | `com.lg.youtube` |
| **Version Code** | `2147483647` |
| **Morphe Engine** | `2.1.0` |
| **APK SHA-256** | `e311a88083586cfb0b2f5d788d83a27a01983464d388b5bc61e7fed758de97df` |
| **Signing Cert SHA-256** | `97c5c6b996e6e589bb8d0ad097587395637c1d05e5b1c15467f08b1fa78aad3a` |
| **Patch Sources** | `https://github.com/MorpheApp/morphe-patches` |

**Applied Patches:**
- AI channel filter
- Add to queue
- Ambient mode
- App refresh rate
- Ask flyout menu
- Bypass image region restrictions
- Bypass link redirects
- Captions
- Change form factor
- Change header
- Change picture-in-picture actions
- Change start page
- Channel search
- Channel whitelist
- Check watch history domain name resolution
- Clone app
- Copy text
- Copy video link
- Custom branding
- Custom font
- Custom player overlay opacity
- DeArrow
- Disable DRC audio
- Disable Play Store updates
- Disable QUIC protocol
- Disable Shorts resuming on startup
- Disable auto feed refresh
- Disable continue watching prompt
- Disable double tap actions
- Disable fullscreen gestures
- Disable haptic feedback
- Disable layout updates
- Disable player popup panels
- Disable playlist autoplay
- Disable rolling number animations
- Disable scrolling speed limit
- Disable sign in to TV popup
- Disable video codecs
- Double tap to seek
- Download post images
- Downloads
- Exit fullscreen mode
- Feed card layout
- Feed video actions
- Feed view count
- Force animations
- Force fullscreen landscape
- Force original audio
- Fullscreen video scale
- GmsCore support
- Hide Shorts components
- Hide ads
- Hide autoplay preview
- Hide end screen cards
- Hide end screen suggested video
- Hide info cards
- Hide layout components
- Hide player flyout menu components
- Hide player overlay buttons
- Hide related video overlay
- Hide related videos
- Hide status bar
- Hide timestamp
- Hide video action buttons
- Loop video
- Media notification controls
- Miniplayer
- Mute button
- Navigation bar
- Niconico comments
- On-the-go player
- Open Shorts in regular player
- Open channel of live avatar
- Open links externally
- Open system share sheet
- Open videos fullscreen
- Override YouTube Music buttons
- Picture-in-picture button
- Play all
- Playback buffer
- Playback in feeds
- Playback speed
- Player icon style
- Playlist improvements
- PoToken provider
- Reload video
- Remember live stream playback position
- Remove background playback restrictions
- Remove viewer discretion dialog
- Restore original titles
- Return YouTube Dislike
- Sanitize sharing links
- Save to Watch later
- Search comments
- Seekbar
- Series tracking
- Settings menu filter
- Shorts autoplay
- Shorts icon style
- Skip live Shorts
- Skip silence
- Snackbar
- SponsorBlock
- Spoof app version
- Spoof device dimensions
- Spoof video streams
- Swipe controls
- Theme
- Translate live chat
- Translate posts
- Video delay
- Video quality
- Voice over translation
- Wide search bar

</details>
