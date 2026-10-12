<p align="center">
  <img src="https://raw.githubusercontent.com/NoMercy-CI-Mirrors/.github/main/profile/logo.svg" width="128" alt="NoMercy CI Mirrors logo">
</p>

<h1 align="center">NoMercy CI Mirrors</h1>

<p align="center">Read-only mirrors of the upstream sources that the <a href="https://github.com/NoMercy-Entertainment/nomercy-ffmpeg">NoMercy FFmpeg build</a> depends on.</p>

## Why these mirrors exist

The FFmpeg build pulls its libraries from many hosts: freedesktop, GNOME, VideoLAN, GitLab, Googlesource, Bitbucket and GNU.
An outage or rate limit on any of them would break the build.
These mirrors keep a copy on GitHub, next to the CI.

## How they work

- Each repo mirrors one upstream project. Its homepage link points there.
- The `ci-mirror` branch syncs from upstream every day.
- [`sources`](https://github.com/NoMercy-CI-Mirrors/sources) keeps the release tarballs the build downloads. One release per file, with its SHA-256.
- Nothing here is changed by hand. Report problems and send patches upstream.

## Credits

The logo is based on the [Git logo](https://git-scm.com/downloads/logos) by Jason Long, licensed [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/).
Changes: recolored to #6E56CF and mirrored across a commit line.

Each mirror keeps the license of its upstream project.
