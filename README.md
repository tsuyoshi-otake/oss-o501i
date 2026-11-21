# OSS O501i

A retro mobile phone concept: an imaginary 1999-style clamshell phone, released as open source.

![OSS O501i](oss-o501i.jpg)

## Live page

**https://tsuyoshi-otake.github.io/oss-o501i/**

The phone is drawn with sprite stacking: the body, hinge and antenna are built from stacked slices.

- The page shows only the phone, over a pattern of 12-dot emoji. Open the control panel with the ☰ button at the top left for the on-screen keypad, the incoming-call demo, body colours and render settings.
- Drag to rotate. The keys on the phone body can be pressed directly. Click the antenna to pull it out (the signal goes from 2 bars to 3).
- The LCD is 116×148 dots with a green backlight (always on, auto or off). The standby screen shows the date, the time and a whale.
- メインメニュー is an icon grid: battery, ringtones, phone book, mail, wallpaper, backlight, calculator, mole game, own number, emoji, silent mode, phone info and i-mode.
- Mail: inbox, sent, drafts, a signature and new mail. The body is typed with multi-tap kana on the number keys (`*` adds dakuten and small kana) and emoji from the メニュー key. Some contacts reply a few seconds after you send.
- i-mode: weather, news, horoscope and 着メロ, where more ringtones can be downloaded into the ringtone list.
- Press 着信させる in the panel for an incoming call: the ringtone plays, the LED blinks and the phone vibrates.
- Keyboard: arrows, Enter, M (menu), Backspace (clear), E (mail), B (phone book), S (silent), I (i-mode), A (antenna), C (call), Esc (end), digits, `*`, `#`.

The whole page is a single file, [`index.html`](index.html), with no build step.
The earlier viewer is still available in [`viewer/`](viewer/index.html).

OSS O501i and everything on its screen, including the weather and news, are fictional and unrelated to any real model or carrier. The emoji and menu icons were drawn for this project. i-mode is a registered trademark of NTT DOCOMO, INC. The LCD text uses M+ BITMAP FONTS.

## License

This project is licensed under the [MIT License](LICENSE).
