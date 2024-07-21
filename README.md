Linux Flavors
---

A quick way to try Linux flavors via docker. Easy to extend. Quick to try:

```
docker compose run alpine
docker compose run arch
docker compose run nix
```

From there, you can poke around and play.

Arch, Alpine, and NixOS...what more can you ask for?

## Notes

I used pinned versions of the distributions, but you can easily just use `:latest` tags.

Yes, you could just use vanilla docker-commands, but between learning and applying, you have a sandbox in `compose.yml` for storing your knowledge. For example, you can update the file to encode updates to run, favorite packages, etc. The sandbox is yours to enjoy.

## Contributions

Ideas and contributions are welcome!

## License

Free for use. No strings attached. Make it your own. Don't blame me for anything. Use at your own risk. Just plain fun. No warranty or promises and no large amounts of legal text. I stand on the should of giants and make no effort to call any of this my own.

This is a simple repository with no actual IP. Just a demonstration of how I sometimes learn the ropes of a new distribution.
