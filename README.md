# Face-Triggered Message

A small browser demo that detects **face presence only** and displays a configurable message locally on the screen. It does not recognize identities or send messages to people.

## Run

Serve this directory over HTTPS or from `localhost` (camera access generally requires a secure context), then open `index.html` in a browser that supports the experimental `FaceDetector` API. Select **Enable camera** and grant camera permission. Select **Stop camera** to end the stream; the camera also stops when the page is closed.

The Face Detection API is not supported in every browser and may need to be enabled in the browser. The page reports when it is unavailable.

## Privacy and intended use

- Face detection and the preview stay in the browser; this app does not record or upload camera frames.
- It detects presence, not identity. It has no face database, matching, tracking, or criminality inference.
- The configurable message is displayed only on the current device. No SMS, email, or other outbound messaging is implemented.
- Use only with clear notice and the camera user's consent. Do not use this demo for surveillance, law-enforcement decisions, or identifying people.
