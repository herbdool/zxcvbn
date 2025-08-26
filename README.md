# ZXCVBN Password Strength Estimator

Overrides the Backdrop core password strength estimator and uses the commonly-used
library [Zxcvbn-PHP](https://github.com/bjeavons/zxcvbn-php).

Zxcvbn-PHP is a password strength estimator using pattern matching and minimum
entropy calculation. Zxcvbn-PHP is based on the the [Javascript zxcvbn](https://github.com/dropbox/zxcvbn)
project from [Dropbox and @lowe](https://blogs.dropbox.com/tech/2012/04/zxcvbn-realistic-password-strength-estimation/).
"zxcvbn" is a bad password, just like "qwerty" and "123456".

> zxcvbn attempts to give sound password advice through pattern matching and
> conservative entropy calculations. It finds 10k common passwords, common
> American names and surnames, common English words, and common patterns like
> dates, repeats (aaa), sequences (abcd), and QWERTY patterns.

There is an [ongoing discussion](https://github.com/backdrop/backdrop-issues/issues/4603)
about incorporating this library into core.

## License

This project is GPL v2 software. See the LICENSE.txt file in this directory for complete text.

## Current Maintainers

[Herb v/d Dool](https://github.com/herbdool/)

This module is currently seeking co-maintainers.

## Credits

Created for Backdrop by [Herb v/d Dool](https://github.com/herbdool/).
