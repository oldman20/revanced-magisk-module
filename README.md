#### ⚠️ Do not download modules from 3rd party sources like random websites you found on Google. There are many that uses my modules and impersonates ReVanced.
# [OTHERS REVANCED APP APK](https://github.com/oldman20/ReVanced-Extended-Automated-Builder)

https://github.com/Jman-Github/ReVanced-Patch-Bundles

https://github.com/FiorenMas/Revanced-And-Revanced-Extended-Non-Root

# ReVanced Magisk Module
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/rvc_magisk)
[![CI](https://github.com/j-hc/revanced-magisk-module/actions/workflows/ci.yml/badge.svg?event=schedule)](https://github.com/j-hc/revanced-magisk-module/actions/workflows/ci.yml)

Extensive ReVanced builder

Discord, Telegram, Twitter chính thức của ReVanced: [Link](https://github.com/revanced/.github/blob/main/profile/README.md)

Danh sách tính năng: [YouTube ReVanced Extended Features](https://telegra.ph/RV--RVX-Features-List-10-31)

Kiểm tra phiên bản phù hợp bằng cách truy cập [revanced-patches](https://github.com/revanced/revanced-patches) và xem **Target Version** hiện tại là gì (Nếu muốn dùng **ReVanced Extended** thì truy cập [revanced-extended](https://github.com/inotia00/revanced-patches/tree/revanced-extended)
Hoặc vào [Revanced Documentation](https://github.com/inotia00/revanced-documentation) - [latest-reddit-patch-info](https://github.com/inotia00/revanced-documentation/blob/main/docs/latest-reddit-patch-info.md)

Use [**zygisk-detach**](https://github.com/j-hc/zygisk-detach) to detach YouTube and YT Music from Play Store if you are using magisk modules. 

<details><summary><big>Features</big></summary>
<ul>
 <li>Support all present and future ReVanced and <a href="https://github.com/inotia00/revanced-patches">ReVanced Extended</a> apps</li>
 <li> Can build Magisk modules and non-root APKs</li>
 <li> Updated daily with the latest versions of apps and patches</li>
 <li> Optimize APKs and modules for size</li>
 <li> Modules</li>
    <ul>
     <li> recompile invalidated odex for faster usage</li>
     <li> receive updates from Magisk app</li>
     <li> do not break safetynet or trigger root detections</li>
     <li> handle installation of the correct version of the stock app and all that</li>
     <li> support Magisk and KernelSU</li>
    </ul>
</ul>
</details>
Note that the <a href="../../actions/workflows/ci.yml">CI workflow</a> is scheduled to build the modules and APKs everyday using GitHub Actions if there is a change in ReVanced patches. You may want to disable it.

## To include/exclude patches or patch more ReVanced Apps
[**See the list of patches**](https://github.com/revanced/revanced-patches#-patches)

[Check patches enable default](https://api.revanced.app/v2/patches/latest) or https://github.com/ReVanced-Extended-Community/Patches-Documentation#patches-documentation

 * Star the repo :eyes:
 * Fork the repo or use the repo as a [template](https://github.com/new?template_name=revanced-magisk-module&template_owner=j-hc)
 * Customize [`config.toml`](./config.toml) using [rvmm-config-gen](https://j-hc.github.io/rvmm-config-gen/) Dùng cái generator rồi ấn nút Upload patches.json của [inotia](https://github.com/inotia00/revanced-patches/blob/revanced-extended/patches.json) vào xong điền theo ý thôi. icon thì ghi mmt. 
 * Run the build [workflow](../../actions/workflows/build.yml)
 * Grab your modules and APKs from [releases](../../releases)

also see here [`CONFIG.md`](./CONFIG.md), [inotia00 link](https://github.com/inotia00/revanced-documentation), if need edit json on phone use [JSON Editor Online](https://jsoneditoronline.org)

## Building Locally
### On Termux
```console
bash <(curl -sSf https://raw.githubusercontent.com/j-hc/revanced-magisk-module/main/build-termux.sh)
```

### On Desktop
```console
$ git clone https://github.com/j-hc/revanced-magisk-module
$ cd revanced-magisk-module
$ ./build.sh
```
# Additional:

<a href="https://visitcount.itsvg.in">
  <p align="center"><img src ="https://visitcount.itsvg.in/api?id=STEK1337&label=Visitors&color=12&icon=0&pretty=false" />
</a>

# Nếu bị buffering thì vào cài đặt Revanced bật Spoof client lên:

>cài đặt,cài đặt nâng cao,chung,rồi bật giả mạo phiên bản ứng dụng lên.

**Bật. spoof client lên thì mất cái tính năng playback speed để coi nhanh 1.5x luôn**

# [Revancify](https://github.com/decipher3114/Revancify)

# [docker-py-revanced-extended](https://github.com/nikhilbadyal/docker-py-revanced)

# YouTube ReVanced Extended

Download patched APKs from the [latest releases](https://github.com/STEK1337/youtube-extended/releases/tag/latest)

# <img src="http://i.imgur.com/hXY4lcC.png" height="42px" alt="microG" />
[![Release](https://img.shields.io/github/v/release/inotia00/mMicroG?label=mMicroG)](https://github.com/STEK1337/youtube-extended/releases/latest/download/mMicroG.apk)

👆 to download mMicroG. Necessary in order for YouTube to work. Install it first.

# 🧩 Applied Patches ([detailed info](https://docs.google.com/document/d/1CTZBLYgVszL-P_qzvOIMuswG-3bxMBEqFblQBaRf8tQ/edit))
| 💊 Patch | 📜 Description |
|:--------:|:--------------:|
| `bypass-ambient-mode-restrictions` | Bypass ambient mode restrictions in battery saver mode.
| `change-homepage` | Change home page to subscription feed.
| `custom-branding-name` | Changes the YouTube launcher name to your choice (defaults to ReVanced Extended).
| `custom-double-tap-length` | Add 'double-tap to seek' value.
| `custom-package-name` | Specifies the package name for YouTube and YT Music in the MicroG build.
| `custom-seekbar-color` | Change seekbar color and progressbar color.
| `custom-video-speed` | Adds more video speed options.
| `default-video-quality` | Adds ability to set default video quality settings.
| `default-video-speed` | Adds ability to set default video speed settings.
| `disable-haptic-feedback` | Disable haptic feedback when swiping.
| `disable-hdr-video` | Disable HDR video.
| `disable-landscape-mode` | Disable landscape mode when entering fullscreen.
| `disable-quic-protocol` | Disable CronetEngine's QUIC protocol.
| `disable-startup-shorts-player` | Disables playing YouTube Shorts when launching YouTube.
| `enable-external-browser` | Open url outside the app in an external browser.
| `enable-minimized-playback` | Enables minimized and background playback.
| `enable-old-quality-layout` | Enables the original quality flyout menu.
| `enable-open-links-directly` | Skips over redirection URLs to external links.
| `enable-seekbar-tapping` | Enables tap-to-seek on the seekbar of the video player.
| `enable-tablet-miniplayer` | Enables the tablet mini player layout.
| `enable-tablet-navigation-bar` | Enables the tablet navigation bar.
| `enable-timestamps-speed` | Add the current video speed in brackets next to the current time.
| `enable-wide-searchbar` | Replaces the search icon with a wide search bar. This will hide the YouTube logo when active.
| `force-vp9-codec` | Forces the VP9 codec for videos.
| `header-switch` | Add switch to change header.
| `hide-account-menu` | Hide account menu elements.
| `hide-auto-captions` | Hide captions from being automatically enabled.
| `hide-auto-player-popup-panels` | Hide automatic popup panels (playlist or live chat) on video player.
| `hide-autoplay-button` | Hides the autoplay button in the video player.
| `hide-autoplay-preview` | Hides the autoplay preview container in the fullscreen.
| `hide-breaking-news-shelf` | Hides the breaking news shelf on the homepage tab.
| `hide-button-container` | Adds the options to hide action buttons under a video.
| `hide-captions-button` | Hides the captions button in the video player.
| `hide-cast-button` | Hides the cast button in the video player.
| `hide-category-bar` | Hide the category bar at the top of the feed and at the top of related videos.
| `hide-channel-avatar-section` | Hides the channel avatar section of the subscription feed.
| `hide-channel-watermark` | Hides creator's watermarks on videos.
| `hide-collapse-button` | Hides the collapse button in the video player.
| `hide-comment-component` | Adds options to hide comment component under a video.
| `hide-crowdfunding-box` | Hides the crowdfunding box between the player and video description.
| `hide-double-tap-overlay-filter` | Remove the double tap dark filter layer.
| `hide-email-address` | Hides the email address(handle) in the account switcher.
| `hide-endscreen-cards` | Hides the suggested video cards at the end of a video in fullscreen.
| `hide-endscreen-overlay` | Hide endscreen overlay on swipe controls.
| `hide-filmstrip-overlay` | Hide flimstrip overlay on swipe controls.
| `hide-floating-microphone` | Hide the floating microphone button above the keyboard.
| `hide-flyout-panel` | Adds options to hide player settings flyout panel.
| `hide-fullscreen-panels` | Hides video description and comments panel in fullscreen view.
| `hide-general-ads` | Removes general ads.
| `hide-info-cards` | Hides info-cards in videos.
| `hide-live-chat-button` | Hides the live chat button in the video player (for old layout).
| `hide-load-more-button` | Hides the button under videos that loads similar videos.
| `hide-mix-playlists` | Removes mix playlists from home feed and video player.
| `hide-music-button` | Hides the YouTube Music button in the video player.
| `hide-navigation-buttons` | Adds options to hide or change navigation buttons.
| `hide-navigation-label` | Hide navigation bar labels.
| `hide-pip-notification` | Disable pip notification when you first launch pip mode.
| `hide-player-button-background` | Hide player button background.
| `hide-player-overlay-filter` | Remove the dark filter layer from the player's background.
| `hide-previous-next-button` | Hides the previous and next button in the player controller.
| `hide-quick-actions` | Adds the options to hide quick actions components in the fullscreen.
| `hide-search-terms` | Hide trending searches and search history in the search bar.
| `hide-seek-message` | Hides the 'Slide left or right to seek' message container.
| `hide-seekbar` | Hides the seekbar and progressbar.
| `hide-shorts-component` | Hides other Shorts components.
| `hide-shorts-navbar` | Hide navigation bar when playing shorts.
| `hide-snack-bar` | Hides the snack bar action popup.
| `hide-stories` | Hides YouTube Stories shelf on the feed.
| `hide-suggested-actions` | Hide the suggested actions bar inside the player.
| `hide-time-stamp` | Hides timestamp in video player.
| `hide-tooltip-content` | Hides the tooltip box that appears on first install.
| `hide-video-ads` | Removes ads in the video player.
| `layout-switch` | Tricks the dpi to use some tablet/phone layouts.
| `microg-support` | Allows ReVanced to run without root and under a different package name with MicroG.
| `optimize-resource` | Removes duplicate resources from YouTube.
| `overlay-buttons` | Add overlay buttons to the player such as copy video link, auto-repeat, download and speed control.
| `protobuf-spoof` | Spoofs the protobuf to prevent playback issues.
| `return-youtube-dislike` | Shows the dislike count of videos using the Return YouTube Dislike API.
| `settings` | Applies mandatory patches to implement ReVanced settings into the application.
| `sponsorblock` | Integrates SponsorBlock which allows skipping video segments such as sponsored content.
| `spoof-app-version` | Tricks YouTube into thinking, you are running an older version of the app. One of the side effects also includes restoring the old UI.
| `swipe-controls` | Adds volume and brightness swipe controls.
| `theme` | Applies a custom theme (default: amoled).
| `translations` | Add Crowdin translations for YouTube.
