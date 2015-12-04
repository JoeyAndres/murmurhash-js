# MurmurHash.js

Forked from this [repo](https://github.com/garycourt/murmurhash-js) to work with meteor. Originally conceived by Austin Appleby,
this hash is very fast and low collision. Characteristics desired from a hash.

See [this](http://programmers.stackexchange.com/questions/49550/which-hashing-algorithm-is-best-for-uniqueness-and-speed/145633#145633)
for some detailed comparison between hashes.

# To acquire:
meteor add jandres:murmur

# Example:

```javascript
MURMUR_HASH.murmur_2('asdf');  // murmur 2, without seed.
MURMUR_HASH.murmur_2('asdf', 66);  // murmur 2, with seed.

MURMUR_HASH.murmur_3('asdf');  // murmur 3, without seed.
MURMUR_HASH.murmur_3('asdf', 66);  // murmur 3, with seed.
```

