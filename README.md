# Live Transcription using Deepgram with Flutter

This repository is the finished code of a tutorial showing how to live transcribe your message through [Deepgram](https://www.deepgram.com) with Flutter. To follow the tutorial please head over to [Deepgram's Developer Blog](#URLhere)

## Usage

If you do not wish to follow the tutorial, then to successfully run this application on your mobile device you will need the following:

* [A Deepgram API key](https://console.deepgram.com/signup)
* Flutter installed on your machine

```bash
git clone git@github.com:gregholmes/deepgram-live-transcription-flutter.git
cd deepgram-live-transcription-flutter
flutter pub get # To download the dependencies for this project.
flutter run # This will run the application on your device if you've connected your device to your computer.
```

> **Note:** This project exposes an API key on the client-side! You can set API keys to expire after a period of time, or manually revoke them via the API.