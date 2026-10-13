# AI-origin-transparency-assistant-for-YouTube
Adds AI-origin status labels beside YouTube video titles.
I've prepared the YouTube AI Labeler MVP as a Chrome and Microsoft Edge browser extension. You can install it locally and test it on YouTube.
<img width="1846" height="812" alt="image" src="https://github.com/user-attachments/assets/c1a87f20-e8cb-456c-b03b-74f65396ba6b" />

YouTube AI Labeler — MVP v0.1

Adds AI-origin status labels beside YouTube video titles.

Download the extension source code

## 1. What the prototype does

AI disclosure found

The page contains text that appears to disclose AI-generated or altered content. The disclosure still needs verification.

AI status unknown

No reliable AI-origin signal was found. This does not prove the video was created by a human.

## 2. How to install it on Windows

1. Download the ZIP file above.
2. Extract the `youtube_ai_labeler` folder to your computer.
3. Open Chrome and enter `chrome://extensions` in the address bar. For Edge, use `edge://extensions`.
4. Enable Developer mode.
5. Click Load unpacked and select the extracted folder containing `manifest.json`.
6. Open YouTube or refresh the existing page to see the labels.

## 3. The important next step: make it a real AI detector

The current prototype detects visible disclosure phrases. It does not yet analyze video frames, voices, audio, or embedded provenance metadata.

Future product, will do the following architecture:

YouTube video

Video ID and public metadata

Evidence collection engine

Creator disclosures · Content credentials · Provenance

Multimodal AI analysis

Video frames · Audio · Speech · Editing artifacts

Evidence-based label

Disclosed AI · Likely AI-assisted · Mixed · Unknown

No single detector can reliably identify every AI-generated video. A trustworthy product should present its evidence and uncertainty instead of making unsupported binary claims.

My recommendation is to start with the Chrome/Edge extension plus hybrid detection, then add a URL-checking web app. That provides a practical path from this initial prototype toward a product that can help viewers assess AI-generated content without falsely accusing legitimate creators.
