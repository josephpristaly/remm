YouTube-ReX: 18.30.37  
Music (arm64-v8a): 6.14.50  
Music (arm-v7a): 6.14.50  


Install [mMicroG](https://github.com/inotia00/mMicroG/releases) (recommended), [Vanced Extended MicroG](https://github.com/inotia00/VancedMicroG/releases) or [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases) to be able to use non-root YouTube or YT Music  

[revanced-extended-magisk-module](https://github.com/MatadorProBr/revanced-extended-magisk-module)  

---
Changelog:  
CLI: inotia00/revanced-cli-2.22.2-all.jar  
Integrations: YT-Advanced/revanced-integrations-0.116.0.apk  
Patches: YT-Advanced/revanced-patches-2.187.3.jar  

### [2.187.3](https://github.com/YT-Advanced/ReX-patches/compare/v2.187.2...v2.187.3) (2023-08-11)


### Bug Fixes

* **youtube/overlay-button:** Overlay buttons are not hidden when swiping the seekbar with new thumbnail preview ([d43184c](https://github.com/YT-Advanced/ReX-patches/commit/d43184c3b488269fd706b5372076437496e31b35))


### Features

* **youtube/layout:** Hide reminder button ([356fead](https://github.com/YT-Advanced/ReX-patches/commit/356feaddba902214517696b931eae61b5d150cb4))
* **youtube/spoof-player-parameters:** Readd short parameter ([bd7b678](https://github.com/YT-Advanced/ReX-patches/commit/bd7b6785a239f903ba5b3ae6a8d606f639767702))




---
CLI: inotia00/revanced-cli-2.22.2-all.jar  
Integrations: inotia00/revanced-integrations-0.115.1.apk  
Patches: inotia00/revanced-patches-2.187.1.jar  

YouTube
==
- feat(youtube): add support version `v18.30.37`
- feat(youtube/hide-button-container): now it support versions other than YouTube v18.20.39 https://github.com/ReVanced/revanced-patches/pull/2723
- fix(youtube/integration): move dependence to dummy class path
- fix(youtube/microg-support): app does not close when an error occurs
- fix(youtube/microg-support): error toast message is not set correctly
- feat(youtube/translations): update translation
`Belarusian`, `Bulgarian`, `Chinese Traditional`, `French`, `German`, `Greek`, `Hungarian`, `Indonesian`, `Italian`, `Japanese`, `Polish`, `Russian`, `Vietnamese`


Music
==
- feat(music): add `hide-channel-guidelines` patch
- feat(music/litho): add some exception
- feat(music/enable-new-layout): change default value
- feat(music/enable-new-layout): forcibly disable when the switch is off
- feat(music/enable-sleep-timer): forcibly disable when the switch is off
- feat(music/translations): update translation
`Brazilian`, `Chinese Traditional`, `French`, `Indonesian`, `Korean`, `Russian`, `Spanish`, `Ukrainian`, `Vietnamese`


Etc
==
- At the end of this release, RVX has been [discontinued](https://github.com/inotia00/revanced-documentation/wiki/Announcement). Thank you for using it so far.


※ Compatible ReVanced Manager: [RVX Manager v1.5.2 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.5.2)

---  
