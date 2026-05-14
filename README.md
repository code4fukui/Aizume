# Aizume

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

Aizume is a web-based application that uses [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands) to perform real-time hand tracking. It visualizes the five fingertips of each detected hand with blue circles, whose size dynamically changes based on the finger's perceived distance from the camera.

## Demo

[**Live Demo**](https://code4fukui.github.io/aizume/)

## Features

-   Real-time hand landmark detection via MediaPipe Hands.
-   Visualizes fingertips with dynamically sized blue markers.
-   Supports tracking up to 10 hands simultaneously.
-   Toggleable controls for:
    -   Displaying the original camera feed.
    -   Mirroring the video horizontally.
    -   Switching to the device's back camera.

## Usage

1.  Open the [demo page](https://code4fukui.github.io/aizume/) in a modern web browser.
2.  Allow access to your camera when prompted.
3.  The application will display your hand(s) with markers on the fingertips.
4.  Use the checkboxes to control the view:
    -   `show original image`: Toggles the visibility of the live camera feed.
    -   `mirror mode`: Flips the image horizontally.
    -   `backcamera mode`: Switches between the front and rear device cameras.

## Attribution

This project utilizes the [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands) solution.

## License

[MIT License](LICENSE)