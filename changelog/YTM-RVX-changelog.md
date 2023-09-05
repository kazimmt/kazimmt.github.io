---
label: "YT Music RVX Changelog"
order: 98
icon: "/assets/icons/ytm-rvx.svg"
---

# YT Music RVX Changelog

### 06 September 2023
- bumped base to YT Music 6.17.52
- add `enable-old-style-library-shelf` patch
- add `enable-playback-speed` patch
- add `hide-button-container-labels` patch
- add `hide-emoji-picker` patch
- add `hide-flyout-panel` patch
- add `hide-radio-button` patch
- add `hide-sample-button` patch
- add `hide-tooltip-content` patch
- add `hook-download-button` patch
- delete `share-button-hook` patch
- add `remember-playback-speed` patch
- add `return-youtube-dislike` patch
- remove `decoding-patch` that are no longer used
- amoled: patch now applies the amoled theme to the comment input box as well
- enable-custom-filter: separate filters by line instead of commas
- settings: apply material style to alert dialog
- settings: change some default value
- settings: remove divider from settings
- settings: trim empty space from edit text dialog
- settings: when installing for the first time, a reboot dialog is shown
- shared-resource-id: If the target resource ID is not found, empty index is returned instead of generating patch exception
- hide-get-premium: patch now also hides the premium membership label in settings
- fix: exclusive audio playback not compatible with latest version
- fix: hide-upgrade-button not compatible with latest version
- fix: remember-video-quality: not compatible with latest version
- fix: settings: blank screen appears when text input dialog is shown
- refactor: change settings structure
Credits: inotia00

### 19 August 2023
- bumped base to YT Music 6.15.51
- fix: `Hide Upgrade Button` hiding the **Library** icon in **Navigation bar**

### 09 August 2023
- bumped base to YT Music 6.14.50
- add `hide-channel-guidelines` patch
- litho: add some exception
- enable-new-layout: change default value
- enable-new-layout: forcibly disable when the switch is off
- enable-sleep-timer: forcibly disable when the switch is off
- litho: filter litho components using prefix tree

### 24 July 2023
- bumped base to YT Music 6.11.52
- remove enable-dismiss-queue patch (already applied to all users)
- fix(music/spoof-app-version): patch not applied
- fix(music/disable-auto-captions): failed to resolve SubtitleTrackFingerprint
- fix(youtube/litho-filter): incorrect smali syntax
- More bug Fixes
