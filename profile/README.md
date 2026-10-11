# hidane

hidane (火種, *the seed of fire*) is a Firestore emulator without Java. A single Rust binary
speaks the official emulator's gRPC, REST and WebChannel protocols, runs under `firebase-tools`,
and is tested against the official emulator.

```sh
curl -fsSL https://hidane.dev/install.sh | sh
hidane exec -- firebase emulators:start --only firestore
```

- [hidane](https://github.com/hidane-dev/hidane): the emulator, its issues and roadmap
- [homebrew-tap](https://github.com/hidane-dev/homebrew-tap): `brew install hidane-dev/tap/hidane`
- Website: [hidane.dev](https://hidane.dev)

Not affiliated with Google.
