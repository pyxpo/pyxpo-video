# Changelog

## Unreleased

- Moved to its own repository, github.com/pyxpo/pyxpo-video, with CI on Python 3.9 and 3.12 and releases from tags.
- Added a security policy, a contributing guide and issue templates.

## 0.1.0a1

- First release: `VideoView` plays a local file or an http(s) URL with the platform's controls. AVPlayer on iOS and
  Mac Catalyst, `android.widget.VideoView` with a `MediaController` on Android, and a `<video>` element on the web
  page and the desktop window.
- Props `playing`, `loop`, `muted`, `controls` and `resize_mode`; events `on_load`, `on_error` and `on_end`;
  `ref.current.play()`, `.pause()` and `.seek(seconds)`.
- README with screenshots from Android and iOS.
- Needs `pyxpo>=0.1.0a3`. The desktop window seeks in local files with the byte-range support in the next pyxpo
  release.
