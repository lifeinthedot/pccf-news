# News digest

One signed file, `digest.json`, read by a phone app. It holds short, plain-language security news
for everyday people, each item linking to its public source. It is the same for everyone and holds
nothing about any person.

The file is signed (Ed25519). The app checks the signature against a key built into it and shows
nothing from a file that fails, or from one older than the copy it already has.
