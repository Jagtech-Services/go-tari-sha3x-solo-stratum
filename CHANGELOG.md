# Changelog

## 1.0.0 (2026-10-28)


### ⚠ BREAKING CHANGES

* module path changed from github.com/snipa22/go-tari-p2pool-interface to github.com/snipa22/go-tari-sha3x-solo-stratum. Any consumer importing this module must update their import paths and go.mod require line.

### Features

* **bt:** convert to XN ([c8056a8](https://github.com/Jagtech-Services/go-tari-sha3x-solo-stratum/commit/c8056a8f770e25b7152f2c8aca7b1661828250ec))
* **init:** initial commit ([8317e02](https://github.com/Jagtech-Services/go-tari-sha3x-solo-stratum/commit/8317e0253676450bdbeebd8c10a565d2d564843a))
* **server:** convert defer to hard exit ([e2ed561](https://github.com/Jagtech-Services/go-tari-sha3x-solo-stratum/commit/e2ed56197485e86fa6b3a883b0a27a0dd1b37e59))
* **tracking:** add tracking back in ([23d1619](https://github.com/Jagtech-Services/go-tari-sha3x-solo-stratum/commit/23d16194383f1a50ca0741fa100ae665af3b7b8e))


### Bug Fixes

* correct module path from p2pool-interface copy-paste error ([7564f38](https://github.com/Jagtech-Services/go-tari-sha3x-solo-stratum/commit/7564f3821fd8250c26c43791138b32c0168cd12c))
* migrate to Jagtech-Services org and restore nodeGRPC import after go-tari-grpc-lib split ([47b2644](https://github.com/Jagtech-Services/go-tari-sha3x-solo-stratum/commit/47b2644ab54e6be8be568aacd9aea13be0a17fff))
* remove sync.RWMutex value-copy in minerTracking test fixture ([ca1c0ad](https://github.com/Jagtech-Services/go-tari-sha3x-solo-stratum/commit/ca1c0adeece35304f2e16602970acc68410ca9b6))
