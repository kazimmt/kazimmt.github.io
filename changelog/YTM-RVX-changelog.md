---
label: "YT Music RVX Changelog"
order: 98
icon: "/assets/icons/ytm-rvx.svg"
---

# YT Music RVX Changelog

### 15 November 2023
- bumped base to YT Music 6.27.53
- Hide flyout panel: add `Hide help & feedback` settings
- add `Sanitize sharing links` patch
- & Fixes old bugs

[!button size="s" variant="secondary" text="VirusTotal Check v6.27.53"](https://www.virustotal.com/gui/file-analysis/ZDk5NTRiYzcwNGU0YzMxNWNlMGIwMjE5YjZhYzRkN2Y6MTY5OTk4NjQ3Mg==/detection)

### 22 October 2023
- bumped base to YT Music 6.23.54
- add `remember-repeat-state` patch
- add `repace-cast-button` patch
- add `remember-shuffle-state` patch
- add setting to hide `podcast-related` menus
- add `Enable new player background` patch
- add `Enable old player layout` patch
- remove `enable-force-shuffle` patch
- remove `Enable new layout` patch
- enable-playback-speed: apply radio button instead of list view in playback speed dialog
- fix/enable-playback-speed: excluding enable playback speed patch still shows playback speed icon in the flyout menu
- fix/hook-download-button: change the URL format used when launching external downloads
- fix/Custom playback speed: incorrect warning message
- & More fixes from inotia00

[!button size="s" variant="secondary" text="VirusTotal Check v6.23.54"](https://www.virustotal.com/gui/file/1298a8f66ffe73740c9c88d68c3d4c5d1c80ca7689b4d7207a1aadd4549139dd/detection)
This time it shows 1 warn. Even when I test Stock YT Music from Apkmirror, it shows this [warning](https://www.virustotal.com/gui/file/2f937be0939df2b384fd4601b0963d32782d38f6dde3637e65e081689017f49c/detection) Maybe false positive! 

### 22 September 2023
- bumped base to YT Music 6.19.52
- add `replace-dismiss-queue` patch
- add `sponsorblock` patch
- add `custom-playback-speed` patch
- add `hide-account-menu` patch
- add `hide-handle` patch
- add `hide-terms-container` patch
- add `import/export-settings` patch
- add `start-page` patch
- add `hide-navigation-bar-component` patch
- remove `optimize-resource` patch
- exclusive-audio-playback: now patch enables the `Don't play podcast videos` setting
- hide-cast-button: patch now hides the cast banner inside the player
- replace-dismiss-queue: add `Continue watching` settings
- hook-download-button: change the default external downloader package name
- Setting Category
- & more changes by inotia00

[!button size="s" variant="secondary" text="VirusTotal Check v6.19.52"](https://www.virustotal.com/gui/file/a21490331537733911c6626546a3b059b9b7a664a524b16765c8fc3542a6cf92/detection)

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
