---
label: "YT RVX Changelog"
order: 99
icon: "/assets/icons/yt-rvx.svg"
---

# YT RVX Changelog

### 12 November 2023
YT RVX v18.43.45
- bumped YouTube base 18.43.45
- add `Disable speed overlay` patch
- `Disable speed overlay` now restores the old `Slide to seek` behavior
- add `Enable music search` patch
- add `Hide search term thumbnail` patch
- add `Sanitize sharing links` patch
- add `Hide videos with low views` settings
- more fixes

[!button size="s" variant="secondary" text="VirusTotal Check v18.44.45"](https://www.virustotal.com/gui/file-analysis/ZWQ1NDJiNzNiMmM2ZWFiMDdhYmRkZmExZTBlNTZhNmU6MTY5OTcyOTc4Ng==/detection)

### 22 October 2023
YT RVX v18.40.34
- bumped YouTube base v18.40.34
- add `Hide transcript button` settings
- add `Hide notify me button` settings
- add `Hide stable volume menu`, `Hide captions menu footer`, `Hide quality menu footer` settings
- add `Skip dummy segment` setting
- add `Hide pivot button` settings
- add `Enable gradient loading screen` patch. if you disable `Enable gradient loading screen`, gradient loading screen will be disabled.
- add `Enable HDR codec` settings
- add `Hide channel profile links` settings
- add `Hide toolbar button` patch
- add `Custom player overlay opacity` patch
- add `Spoof device dimensions` patch
- add `Disable ambient mode`, `Disable ambient mode in fullscreen` settings
- Seek undo message (`Release to cancel`) is also hidden
- custom-speed-overlay: change patch name `hide-speed-overlay` → `custom-speed-overlay`
- Alternative thumbnails: add Using `DeArrow API` settings
- Spoof player parameters: add `Spoof player parameter in feed` settings
- Hide general ads: block new type of `web search` panel
- Hide layout components: add `Hide start trial button` settings
- Hide shorts components: `Hide info panels` now also hides the panel for music information
- Hide navigation buttons:` Open library on app startup` now also works in the You tab (`Open library on app startup` → `Open library(You) on app startup`)
- Hide quick actions: add `Hide open mix playlist button`, `Hide open playlist button` settings
- change patch name `Force VP9 codec` → `Force video codec`
- change patch name `Language switch` → `Enable language switch`
- change patch name `Bypass ambient mode restrictions` → `Ambient mode switch`
- remove `optimize-resource` patch
- remove `Hide live chat button` settings (no longer exists in the button container)
- remove `press-to-swipe gesture` settings
- remove `save and restore brightness` settings
- remove `Enable new comment popup panels` patch
- remove `Hide player overlay filter` patch
- remove `Disable speed overlay` settings
- Settings: `import/export` settings are no longer Experimental Flags
- Spoof app version: add target version `18.01.38` - remove 'Comments by members' banner
- append-time-stamps-information: users can now choose between playback speed and video quality, which users can also toggle by long-pressing on the timestamp
- Custom playback speed: regulate maximum playback speed to 8.0x (playback rate that can be handled by the client)
- Hide layout components: move `Hide join button` to the `Channel bar` subpreference in the `Bottom player` category
- Hide shorts components: remove the `Hide toolbar` setting and add settings to `hide each toolbar button`
- & More fixes from ReVanced Team & Inotia00

[!button size="s" variant="secondary" text="VirusTotal Check v18.40.34"](https://www.virustotal.com/gui/file/1b037bc5516864f4271254cf83487a0cfd150ca7c618a773bbb18e1a8387e2a7/detection)

### 19 September 2023
YT RVX 18.36.39
- bumped YouTube base 18.36.39
- fix (whitelist): SponsorBlock option disappear
- fix (hide-quality-footer): hide-quality-footer
- bypass-ambient-mode-restrictions: update fingerprint
- add: Ads whitelist
- fix: some old bugs
- add: some new bugs

[!button size="s" variant="secondary" text="VirusTotal Check v18.36.39"](https://www.virustotal.com/gui/file/e89ccf18d8579ea0b012cfaaa11cb3c4fe0aed60815a8da5a0ca727ea56207a1/detection)

### 01 September 2023
YT RVX 18.33.40
- bumped YouTube base 18.33.40
- add: `Hide quality layout footer` settings (inside flyout menu)
- add: `higher-seekbar-height` patch
- fix: `Emoji picker` in comment section not hidden
- fix: `Hide Fullscreen panel` not working correctly

[!button size="s" variant="secondary" text="VirusTotal Check v18.33.40"](https://www.virustotal.com/gui/file/7b6e2e2085c7aec76b3a3b97741758edb6335105517b1bed7e6438f2d158ddab/detection)

### 19 August 2023
YT RVX 18.32.37
- bumped YouTube base 18.32.37
- add: `Alternative video thumbnails` (Anti Clickbait)
- hide product banner: Hide new product type (in Store tab)
- hide action button: Add hide for action button (like Transcript, Chapter, etc)
- save video quality: Video Quality Preset not worked
- hide suggestion shelf: Suggesstion shelf hidden on tablet layout

Thanks to @annonyviet for continuing the RVX Project.


### 11 August 2023
YT RVX 18.30.37
- bumped YouTube base 18.30.37
- hide-button-container: now it support latest version
- fix: new type of Shorts shown in search feed
- shorts: Hide pivot button
- whitelist: Take whitelist feature back

### 03 August 2023
YT RVX 18.29.38
- bumped YouTube base 18.29.38
- add `Hide chips shelf` settings
- add `hide-latest-videos-button` patch
- `enable-old-quality-layout`: match with the official Revanced
- `hide preview comment` hides the dots of live comments
- `hide-general-ads`: update filter
- `spoof-player-parameters`: match with official revanced patches
- `sponsorblock`: voting button and creating new segments button are shown during the double tap
- `overlay-buttons`: vertical fullscreen icon does not match
- `settings`: wrong alphabetical alignment
  & more fixes

### 24 July 2023
YT RVX 18.27.35
- bumped YouTube base 18.27.35
- add `hide-suggested-video-overlay` patch
- apply `custom seekbar color` to shorts
- hide new type of ads
- change the default value of `Hide expandable chip under video`
- `hide-suggested-video-overlay`: no longer dependent on `overlay-buttons` patches
- fix: dislikes not showing in some situations
- fix(youtube/swipe-controls): When `Press-to-swipe` is disabled, `Press-to-swipe haptic feedback` should also be disabled
  & more fixes

### 17 July 2023
YT RVX 18.25.40
- bumped YouTube base 18.25.40
- add `enable-new-comment-popup-panels` patch
- feat(youtube/hide-description-component): add `Hide game sections`, `Hide info cards sections` settings
feat(youtube/hide-layout-components): add `Hide browse store button` settings
- feat(youtube/hide-button-container): removed settings marked as Experimental Flags (these settings no longer fixable in latest YouTube)
- remove `hide-live-chat-button` patch (location of the live chat button has been moved even in the old layout)
- fix(youtube/hide-feed-flyout-panel): unintended menus are hidden
- fix(youtube/hide-account-menu): app crashes in landscape mode
& more fixes

Thanks to ReVanced team & Inotia00

Telegram: https://t.me/revanced_mmt
