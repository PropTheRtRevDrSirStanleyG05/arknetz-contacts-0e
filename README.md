# arknetz-contacts-0e

ArkNetzWebWeaver contacts shard `0e` (MIT) — one of 16 hash
shards of the global contacts / public-key directory, keyed like the
registry (by address hash). Used for protocol-mail addressing (X25519
public keys, PROTOCOL.md §3.5, §6.1).

- `contacts.json.zst` — canonical shard file (live empty state: `{}`, 15 bytes).
  `contacts.json` is the plain mirror.

Live state: empty. No contacts in this shard yet — an empty directory is
the live starting state, not test data.
