# Install
- Install dependencies (OSX)
  curl https://sh.rustup.rs -sSf | sh
  rustup target add aarch64-apple-ios
  rustup target add armv7-apple-ios
  rustup target add armv7s-apple-ios
  rustup target add x86\_64-apple-ios
  rustup target add i386-apple-ios
  cargo install cargo-lipo

  cd ssh-wire
  ./build.sh

More coming soon...
by krypt co
