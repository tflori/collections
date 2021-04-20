# Collections

This is a fork of illuminate/collections with the dependencies included and the php dependency corrected.

## Reason

The only reason I created this package was the compatibility to php 7.1. The collection nowhere needs php 7.3 but the
package is defined with `php: "^7.3|^8.0"` and I was not able to depend on it in a library for 7.1.

## Concerns

This package is separated from illuminate/framework and comes without tests as they are defined there. So we don't
have tests for it and can't make sure everything works in php 7.1.

## Support / Bugs

If you experience any type of bug please check first if that bug also exists in illuminate/collections and if so
report it there.

For outdated versions or problems with compatibility to php >= 7.1 to php < 7.3 please create tickets in this project.
