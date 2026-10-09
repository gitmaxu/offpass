# OffPass

Offline random password generator for Android. Free software (GPL-3.0).

## What it does

- Tap Generate to make a random password on your device.
- Choose the length: 8, 12, 16, 36, 64, 100 or 256 characters.
- Choose the character types: lowercase (a-z), uppercase (A-Z), digits (0-9) and symbols (!@#$%^&*()-_=+:;?). At least one type always stays on.
- Every password contains at least one character from each type you selected, in a random order.
- Tap Copy to put the password on the clipboard.
- The password is shown in a monospace font, so look-alike characters (l, 1, I, 0, O) are easier to tell apart.

## Privacy

- Passwords are made with the device's secure random number generator (Dart's Random.secure).
- The app declares no permissions, including no internet access.
- No ads, no analytics, no accounts, no tracking.
- Passwords are not saved. When you close the app they are gone.

## Good to know

- After you tap Copy, the password stays on the clipboard until you copy something else. Android may also show it in a clipboard preview. Paste it where you need it, then copy something else to clear it.
- The "Copied" message on screen shows the password for two seconds.

## Build

    flutter pub get
    flutter build apk --release

The package ID is offpass.secure.fast.

## License

GPL-3.0. See the LICENSE file.
