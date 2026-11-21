# OSS O501i

A retro mobile phone concept: an imaginary 1999-style clamshell phone, released as open source.

![OSS O501i](oss-o501i.jpg)

## Live page

**https://tsuyoshi-otake.github.io/oss-o501i/**

The phone is drawn with sprite stacking: 771 slices are layered to build the body in 3D.

- The page shows only the phone. Open the control panel with the ☰ button at the top left for the on-screen keypad, the incoming-call demo, body colours and render settings.
- Drag to rotate. The keys on the phone body can be pressed directly.
- The LCD is 116×148 dots. The standby screen, menu, phone book, calculator and a mini game all run on it.
- Press 着信させる in the panel for an incoming call: the ringtone plays, the LED blinks and the phone vibrates.
- Keyboard: arrows, Enter, M (menu), Backspace (clear), E (mail), B (phone book), S (mute), C (call), Esc (end), digits, `*`, `#`.

The whole page is a single file, [`index.html`](index.html), with no build step.
The earlier viewer is still available in [`viewer/`](viewer/index.html).

OSS O501i, its charging cradle and everything on its screen are fictional and unrelated to any real model or carrier.

## License

This project is licensed under the [MIT License](LICENSE).
