# Change Log - @yume-chan/adb-credential-web

## 2.1.0

### Patch Changes

- Updated dependencies [a835eb8]
- Updated dependencies [dbcfd34]
    - @yume-chan/adb@2.1.0

## 2.0.1

### Patch Changes

- @yume-chan/adb@2.0.1

## 2.0.0

### Patch Changes

- Updated dependencies
- Updated dependencies [05c01ad]
    - @yume-chan/adb@2.0.0

## 1.1.0

### Patch Changes

- Updated dependencies [ab98953]
    - @yume-chan/adb@1.1.0

## 1.0.1

### Patch Changes

- 53688d3: Use PNPM workspace and Changesets to manage the monorepo.

    Because Changesets doesn't support alpha versions (`0.x.x`), this version is `1.0.0`. Future versions will follow SemVer rules, for example, breaking API changes will introduce a new major version.

- db8466f: Add common interface for device observers
- Updated dependencies [53688d3]
- Updated dependencies [db8466f]
- Updated dependencies [db8466f]
- Updated dependencies [db8466f]
    - @yume-chan/adb@1.0.1

This log was last generated on Tue, 18 Jun 2024 02:49:43 GMT and should not be manually modified.

## 0.0.24

Tue, 18 Jun 2024 02:49:43 GMT

_Version update only_

## 0.0.23

Thu, 21 Mar 2024 03:15:10 GMT

_Version update only_

## 0.0.22

Wed, 13 Dec 2023 05:57:27 GMT

_Version update only_

## 0.0.21

Fri, 25 Aug 2023 14:05:18 GMT

### Updates

- Add name for public keys
- Change to save private keys in IndexedDB, allow usage from Web Workers

## 0.0.20

Mon, 05 Jun 2023 02:51:41 GMT

### Updates

- Change `AdbWebCredentialStore` to save private keys in IndexedDB, so it can be used in Web Workers. Previously saved keys in `localStorage` will be ignored and a new key will be generated.

## 0.0.19

Sun, 09 Apr 2023 05:55:33 GMT

_Version update only_

## 0.0.18

Wed, 25 Jan 2023 21:33:49 GMT

_Version update only_

## 0.0.17

Tue, 18 Oct 2022 09:32:30 GMT

### Updates

- Update to use new stream util package

## 0.0.16

Sat, 28 May 2022 03:56:37 GMT

### Updates

- Upgrade TypeScript to 4.7.2 to enable Node.js ESM

## 0.0.15

Mon, 02 May 2022 04:18:01 GMT

_Version update only_

## 0.0.14

Sat, 30 Apr 2022 14:05:48 GMT

_Version update only_

## 0.0.13

Thu, 28 Apr 2022 01:23:53 GMT

_Version update only_

## 0.0.12

Sun, 03 Apr 2022 11:18:47 GMT

_Version update only_

## 0.0.11

Sun, 03 Apr 2022 10:54:15 GMT

### Updates

- Update to use Web Streams API
- Improve compatibility with Node.js 12 ESM format

## 0.0.10

Sun, 09 Jan 2022 15:52:20 GMT

_Initial release_
