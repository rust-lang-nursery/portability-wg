# Portability Working Group

> Coordination repository of the portability Working Group (WG)

This repository [issue tracker] is used by the portability WG to coordinate efforts towards making Rust
portable to new platforms.

[issue tracker]: https://github.com/rust-lang-nursery/portability-wg/issues

## Vision

> Rust is really super portable. It supports a lot of platforms. But not enough 
> … not nearly enough. Rust wants to be everywhere, in wild places that only 
> future generations will be able to imagine. We’ve got some work yet to enable 
> that future though, and it is our responsibility to the Rusting world to do 
> so!
>
> -- [@brson](https://github.com/brson)

Some concrete goals:

* Support in `std` for non-Unix, non-Windows platforms.
  * Support for platforms that don’t have or require libc. The `std` API surface is already designed to accomodate this, but not the implementation.
* Reduced maintenance burden for ports. Porting std today requires touching too many parts of the libraries, and those parts must be maintaned by the std maintainers. In general, day-to-day maintenance should not require dealing with platform-specific code, especially for lesser-maintained ports.
* Rust developers should be aware when they use non-portable interfaces, so that they can avoid them or at least plan for them.
* Most of Rust's crate ecosystem should be usable on any platform with ease.

## Roster

- [@acfoltzer](https://github.com/acfoltzer)
- [@alfriadox](https://github.com/alfriadox)
- [@bossmc](https://github.com/bossmc)
- [@Ericson2314](https://github.com/Ericson2314)
- [@jethrogb](https://github.com/jethrogb) (lead, all things SGX)
- [@le-jzr](https://github.com/le-jzr)
- [@pierzchalski](https://github.com/pierzchalski)
- [@ratmice](https://github.com/ratmice)
- [@retep998](https://github.com/retep998) (all things Windows)
- [@theJPster](https://github.com/theJPster)
- [@Tom-Phinney](https://github.com/Tom-Phinney)

### Contact

You can usually find the members of the portability WG on the #rust-portability channel (server:
irc.mozilla.org). Most of us use our GH usernames as our IRC nicknames.
