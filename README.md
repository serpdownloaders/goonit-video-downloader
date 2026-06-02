# Goonit Downloader (Browser Extension)

> Download videos from GOONIT with a simple browser workflow, player button access, and GOONIT-focused host coverage.

Goonit Downloader is a browser extension candidate designed for saving videos from GOONIT's `.io` site flow. The extension focuses on providing a visible player download surface and helper-host awareness for Eporner-linked media paths, giving you a cleaner way to save content directly from your browser.

- GOONIT-specific extension identity with `.io` domain targeting
- In-player download button workflow for the GOONIT video wrapper
- Helper-host awareness for Eporner domain relationships
- Compact permission set for browser-based downloading
- Offscreen folder configuration for organized file saving

## Links

- :rocket: Get it here: [Goonit Downloader](https://serp.ly/goonit-downloader)
- :new: Latest release: [GitHub Releases](https://github.com/serpapps/goonit-downloader/releases/latest)
- :question: Help center: [SERP Help](https://help.serp.co/en/)
- :beetle: Report bugs: [GitHub Issues](https://github.com/serpapps/goonit-downloader/issues)
- :bulb: Request features: [Feature Requests](https://github.com/serpapps/goonit-downloader/issues)

## Preview

![Goonit Downloader workflow preview](https://raw.githubusercontent.com/devinschumacher/uploads/refs/heads/main/images/source-repo-readmes/goonit-downloader/assets/workflow-preview.png)

## Table of Contents

- [Why Goonit Downloader](#why-goonit-downloader)
- [Features](#features)
- [How It Works](#how-it-works)
- [Step-by-Step Tutorial: How to Download Videos from Goonit](#step-by-step-tutorial-how-to-download-videos-from-goonit)
- [Supported Formats](#supported-formats)
- [Who It's For](#who-its-for)
- [Common Use Cases](#common-use-cases)
- [Troubleshooting](#troubleshooting)
- [Trial & Access](#trial--access)
- [Installation Instructions](#installation-instructions)
- [FAQ](#faq)
- [Notes](#notes)
- [License](#license)
- [About Goonit](#about-goonit)

## Why Goonit Downloader

GOONIT pages do not always expose a simple right-click save target for video content. Users who want to save videos from the site often resort to copy-paste downloader sites or manual source hunting, which can be time-consuming and unreliable. The extension addresses this by providing a direct browser workflow with a visible player download button.

The extension is built around GOONIT's `.io` brand with strong button-driven handoff confidence. It includes helper-host permissions for Eporner domains, which is useful when media flows are not limited to the visible page domain. The setup is centered on the GOONIT player wrapper, making the download process more straightforward for regular viewers.

## Features

- GOONIT-specific extension identity and product page
- Matches `goonit.io`, `*.goonit.io`, and `www.goonit.io`
- Extra helper-host permissions for `eporner.com` and subdomains
- Player button targets the GOONIT video wrapper
- Generic static-media preset with Open Graph, media-tag, and Twitter stream detection patterns
- Content script stack includes download manager and player button surfaces
- Offscreen folder configured for organized file saving
- Strong handoff confidence from button-driven validation

## How It Works

1. Install the extension from the latest release.
2. Open Goonit and go to a supported video page.
3. Start playback so the extension can detect the media.
4. Open the popup or use the on-page controls.
5. Choose the quality option you want.
6. Start the download and wait for the MP4 export to finish.
7. Save the final file locally.

## Step-by-Step Tutorial: How to Download Videos from Goonit

1. Install the Goonit Downloader extension from the GitHub Releases page.
2. Open your browser and navigate to a supported Goonit video page.
3. Let the page load completely, including the video player.
4. Start playing the video so the player exposes the media path.
5. Look for the download button on the Goonit video player wrapper.
6. Click the download button to trigger the detection process.
7. Select your preferred quality option if available.
8. Wait for the browser download to complete and save the file.

## Supported Formats

- Input: GOONIT video pages with Open Graph, media-tag, and Twitter player stream detection patterns
- Output: MP4

Saved files use MP4 so they are easier to replay on standard media players, move between devices, or archive locally.

## Who It's For

- GOONIT viewers who want a direct browser workflow instead of copy-paste downloader sites
- Users who prefer a visible player download button over technical source hunting
- People who regularly save content from GOONIT and want a streamlined process
- Viewers who encounter GOONIT pages that rely on Eporner-related helper hosts

## Common Use Cases

- Saving a single GOONIT video directly from the browser
- Triggering a download from the player wrapper instead of digging through page source
- Handling GOONIT pages that use Eporner helper hosts for media delivery
- Building a local archive of GOONIT content for offline viewing
- Replacing manual copy-paste workflows with a button-driven experience

## Troubleshooting

**The download button does not appear on the player.**
Make sure the video is playing or has been started so the player wrapper is active. Refresh the page if the button still does not show.

**The extension cannot detect the video source.**
Some GOONIT pages may use non-standard media paths. Try playing the video fully before triggering the download.

**Downloads fail or stop midway.**
Check your internet connection and browser download settings. A stable connection is required for the download to complete.

**The extension does not work on certain GOONIT pages.**
The extension targets GOONIT's `.io` domain and supported host forms. Pages outside this scope may not be compatible.

**The download manager does not show progress.**
Open the browser's built-in download manager to track progress. The extension triggers standard browser downloads.

## Trial & Access

- Includes **3 free downloads** so you can test the workflow first
- Email sign-in uses secure one-time password verification
- No credit card required for the trial
- Unlimited downloads are available with a paid license

Start here: [https://serp.ly/goonit-downloader](https://serp.ly/goonit-downloader)

## Installation Instructions

1. Open the latest release page: [GitHub Releases](https://github.com/serpapps/goonit-downloader/releases/latest)
2. Download the correct build for your browser.
3. Install the extension.
4. Open a supported Goonit page.
5. Use the popup to detect and download the media.

## FAQ

**What site is this extension built for?**
The extension is built for GOONIT on `goonit.io`, including subdomains and the `www` host form.

**Why does the extension mention Eporner?**
The extension includes Eporner host permissions as a helper-host relationship tied to the GOONIT media flow.

**How does the extension detect media?**
The extension uses a generic static-media preset with Open Graph, media-tag, and Twitter player stream detection patterns.

**Is the extension fully released and verified?**
The extension has strong targeting and handoff signals but the extraction layer is still under review for release readiness.

**Can I use the extension on other sites?**
No, the extension is specifically designed for GOONIT and its helper-host relationship with Eporner domains.

## Notes

- Only download content you own or have explicit permission to save
- An internet connection is required for downloads
- The extension targets GOONIT's `.io` domain and supported host forms
- The extraction layer is still under review for full release verification

## License

This repository is distributed under the proprietary SERP Apps license in the [LICENSE](LICENSE) file. Review that file before copying, modifying, or redistributing any part of this project.

## About Goonit

GOONIT is a video platform operating on the `.io` domain that hosts a wide range of adult content. The extension helps users save videos from GOONIT by providing a direct browser workflow with player button access and helper-host awareness for Eporner-linked media paths.
