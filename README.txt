Overview
========

A storage implementation which uses RAM to persist objects, much like
MappingStorage. Unlike MappingStorage, it needs not be packed to get rid of
non-cyclic garbage and it does rudimentary conflict resolution. This is a
ripoff of Jim's Packless bsddb3 storage.
