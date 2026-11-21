# Audio-Recorder (ZimRec)

Simple audio recorder for Windows: system sound and/or microphone, with global hotkeys.

## Download

Grab `ZimRec-1.3.exe` from the **Releases** page. FFmpeg is bundled.

## Features

- Record system sound and/or microphone
- Global hotkeys (F8 record, F9 system, F10 mic), rebindable
- Formats: mp3, ogg, wav
- Auto-numbered files: record 1, record 2, ...
- Device picker (Devices button)

## Build from source

    javac -encoding UTF-8 -cp "jnativehook-2.2.2.jar" -d out src\main\java\ZimRec.java
    jar --create --file ZimRec.jar --main-class ZimRec -C out .

## License

MIT
