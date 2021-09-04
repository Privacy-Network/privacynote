# Octopus Appchain Template

# complile
```
$ cargo build
$ ./target/debug/appchain-privacynote purge-chain --dev
$ ./target/debug/appchain-privacynote --dev --enable-offchain-indexing true
```

# pack
```
//Generate the Chain Spec file and hash by the following commands
cargo build --release

# Generate the chainspec file, feel free to use any filename you wish
./target/release/appchain-privacynote build-spec --disable-default-bootnode --chain dev> privacynoteSpec.json 
# Generate sha256 hash
sha256sum privacynoteSpec.json> SHA256SUMS

```