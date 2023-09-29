YouTube: 18.31.40  


Install [mMicroG](https://github.com/inotia00/mMicroG/releases) (recommended), [Vanced Extended MicroG](https://github.com/inotia00/VancedMicroG/releases) or [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases) to be able to use non-root YouTube or YT Music  

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)  

---
Changelog:  
CLI: inotia00/revanced-cli-3.1.2-all.jar  
Integrations: inotia00/revanced-integrations-0.117.15.apk  
Patches: inotia00/revanced-patches-2.190.15.jar  

YouTube
==
- feat(youtube): add `alternative-thumbnails` patch https://github.com/inotia00/revanced-patches/pull/19
- feat(youtube): add support version `v18.32.39`
- feat(youtube): drop support version `v18.19.36` ~ `v18.21.35`
- feat(youtube/hide-button-container): add `Hide transcript button` settings https://github.com/inotia00/revanced-patches/pull/19
- feat(youtube/hide-layout-components): add `Hide notify me button` settings https://github.com/inotia00/revanced-patches/pull/19
- feat(youtube/hide-player-flyout-panel): add `Hide stable volume menu`, `Hide captions menu footer`, `Hide quality menu footer` settings https://github.com/inotia00/revanced-patches/pull/19
- feat(youtube/hide-shorts-components): add `Hide pivot button` settings https://github.com/inotia00/revanced-patches/pull/19
- fix(youtube/enable-old-quality-layout): causes a crash in certain situations http://github.com/inotia00/ReVanced_Extended/issues/1430
- fix(youtube/sponsorblock): some strings resources are missing https://github.com/inotia00/ReVanced_Extended/issues/1425
- fix(youtube/spoof-player-parameters): seekbar thumbnail preview not shown in age restricted video & live stream
- fix(youtube/spoof-player-parameters): seekbar thumbnail preview quality is very low
- feat(youtube/translations): update translation
`Arabic`, `Brazilian`, `Greek`, `Italian`, `Korean`, `Polish`, `Russian`, `Spanish`, `Turkish`, `Ukrainian`, `Vietnamese`


YouTube Music
==
- feat(music): add support version `v6.21.51`
- feat(music): add `repace-cast-button` patch https://github.com/inotia00/ReVanced_Extended/issues/1431
- fix(music): some patches are broken in `v6.15.52` https://github.com/inotia00/ReVanced_Extended/issues/1414
- fix(music/hook-download-button): apply more safer method
- fix(music/settings): some toggles do not change properly when importing settings https://github.com/inotia00/ReVanced_Extended/issues/1427
- feat(music/translations): update translation
`Brazilian`, `Greek`, `Italian`, `Japanese`, `Korean`, `Polish`, `Russian`, `Spanish`, `Turkish`, `Vietnamese`


Etc
==
- build: bump dependencies
- in case of YouTube, clean install is recommended
- In case of YouTube Music, Google dropped support for Android 5.0.x to 6.0.x since `v6.21.51`


※ Compatible ReVanced Manager: [RVX Manager v1.9.7 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.9.7)
[Crowdin translation]
- [YouTube/European Countries](https://crowdin.com/project/revancedextendedeu)
- [YouTube/Other Countries](https://crowdin.com/project/revancedextended)
- [YT Music](https://crowdin.com/project/revanced-music-extended)


---
CLI: inotia00/revanced-cli-3.1.2-all.jar  
Integrations: YT-Advanced/revanced-integrations-0.117.12.apk  
Patches: YT-Advanced/revanced-patches-2.192.2.jar  

#### [2.192.2](https://github.com/YT-Advanced/ReX-patches/compare/v2.192.0...v2.192.2) (2023-09-25)


### Bug Fixes

* Failed to merge resources ([da3b85e](https://github.com/YT-Advanced/ReX-patches/commit/da3b85e89c40502a2fe5d873682343a6a77793ea))




---  
