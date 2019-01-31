# animalsiknow.github.io

You can find in this repository the sources for my github.io site.

## Regenerating the Rust documentation

Run `cargo doc`, then replace `/doc` with the newly generated `/target/doc`. It is a good idea to remove `winapi` since it is very large.

```sh
rm -r doc/winapi doc/src/winapi
```
