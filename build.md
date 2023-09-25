Music (arm64-v8a): 6.20.51  
YouTube: 18.33.40  
Music (arm-v7a): 6.20.51  


Install [mMicroG](https://github.com/inotia00/mMicroG/releases) (recommended), [Vanced Extended MicroG](https://github.com/inotia00/VancedMicroG/releases) or [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases) to be able to use non-root YouTube or YT Music  

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)  

---
Changelog:  
CLI: inotia00/revanced-cli-3.1.2-all.jar  
Integrations: inotia00/revanced-integrations-0.117.12.apk  
Patches: inotia00/revanced-patches-2.190.12.jar  

YouTube
==
- fix(integration): apply more precise class names
- fix(integration): no longer override User-Agent when sending request
- fix(youtube/append-time-stamps-information): when the video quality is set to `Auto`, the quality is not displayed properly
- fix(youtube/hide-feed-flyout-panel): no longer overwrites default values https://github.com/inotia00/ReVanced_Extended/issues/1402
- fix(youtube/hide-info-cards): block new type of infocards https://github.com/inotia00/ReVanced_Extended/issues/1406
- fix(youtube/hide-suggestions-shelf): does not work on tablet https://github.com/inotia00/ReVanced_Extended/issues/1398
- fix(youtube/overlay-buttons): wrong formatted timestamps copied
- fix(youtube/settings): apply correct strings resource https://github.com/inotia00/ReVanced_Extended/issues/1392
- fix(youtube/settings): when rebooting from the AlertDialog displayed when first installed, reboot does not work properly
- fix(youtube/spoof-player-parameters): `Ambient mode`, `Clip`, `FilmStrip overlay`, `Thumbnail preview in SeekBar` does not working
- fix(youtube/spoof-player-parameters): remove dependencies that are no longer used
- feat(youtube/translations): update translation
`Arabic`, `Brazilian`, `Chinese Traditional`, `Greek`, `Korean`, `Russian`, `Spanish`, `Vietnamese`


YouTube Music
==
- feat(music): add support version `v6.20.51`
- feat(music): add `remember-repeat-state` patch
- feat(music): add `remember-shuffle-state` patch
- feat(music): remove `enable-force-shuffle` patch
- feat(music/hide-flyout-panel): add setting to hide podcast-related menus
- feat(music/litho-filter): no longer uses `identifier` parameter
- fix(music/exclusive-audio-playback): switch didn't actually work
- fix(music/import-export-settings): integrated into `settings` patch https://github.com/inotia00/ReVanced_Extended/issues/1391
- feat(music/translations): update translation
`Chinese Traditional`, `French`, `Greek`, `Indonesian`, `Korean`, `Polish`, `Russian`, `Spanish`, `Vietnamese`


Etc
==
- build: bump dependencies
- some side effects of the `spoof-player-parameter` patch have been fixed
- following known issues remain:
• Enhanced bitrate is not available
• Offline downloads may not work
• SeekBar thumbnail preview quality is very low


※ Compatible ReVanced Manager: [RVX Manager v1.9.7 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.9.7)
[Crowdin translation]
- [YT Music](https://crowdin.com/project/revanced-music-extended)

---
CLI: inotia00/revanced-cli-3.1.2-all.jar  
Integrations: YT-Advanced/revanced-integrations-0.120.0.apk  
Patches: YT-Advanced/revanced-patches-2.191.0.jar  

### [2.191.0](https://github.com/YT-Advanced/ReX-patches/compare/v2.190.2...v2.191.0) (2023-09-19)
### Bug Fixes
* **music/return-youtube-dislike:** add translation exception ([6f56d78](https://github.com/YT-Advanced/ReX-patches/commit/6f56d78e3edb8f34643168c6cbe513cf71124f6a))
* **music/spoof-app-version:** add missing dependencies ([acd7d05](https://github.com/YT-Advanced/ReX-patches/commit/acd7d057b9918a6a539dfd1ea748fcc143efee52))
* **youtube/bypass-ambient-mode-restrictions:** update fingerprint ([6087d7b](https://github.com/YT-Advanced/ReX-patches/commit/6087d7be8340e48488a054c715ebd0b9b4a80bd0))
* **youtube/default-video-quality:** default video quality is not applied at cold start ([517e86f](https://github.com/YT-Advanced/ReX-patches/commit/517e86f75ceb18b1fbeac7a01a39bc065e6deb67))
* **youtube/settings:** remove unused string resources ([a09e2e5](https://github.com/YT-Advanced/ReX-patches/commit/a09e2e5b137c71a65377feb55aa3d0aee26dc6d3))
* **youtube/sponsorblock:** change invalid patch name ([ae06785](https://github.com/YT-Advanced/ReX-patches/commit/ae06785f7741c73d046658a5eecf97ebfa4f1217))
### Features
* **music/hide-flyout-panel:** code refactoring ([33ad9af](https://github.com/YT-Advanced/ReX-patches/commit/33ad9afe89a556014a1aa083bf9dd18781642fa1))
* **music:** add `replace-dismiss-queue` patch ([0a06b69](https://github.com/YT-Advanced/ReX-patches/commit/0a06b69b6bd842df34aac55a9117e63d0b81c49a))
* **music:** add `sponsorblock` patch https://github.com/inotia00/ReVanced_Extended/issues/97 ([88d6389](https://github.com/YT-Advanced/ReX-patches/commit/88d63898bce47d78e535114a40beb3be5c41d695))
* **music:** add support version `v6.19.51` ([69cb800](https://github.com/YT-Advanced/ReX-patches/commit/69cb800603356e98f74888342634eca305b80054))
* Readd Ads Whitelist ([c83c3b8](https://github.com/YT-Advanced/ReX-patches/commit/c83c3b823ee574e8f06814ec79a2943934ad8956))

---  
