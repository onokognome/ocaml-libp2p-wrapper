# ocaml-libp2p-wrapper
let's see if we can wrap the go implementation of libp2p in C, then create an ocaml interface

# Introduction
This is a mult-level learning experience which hopefully will also provide something useful. 
Here's what I think is going to happen:
* Get aquainted with linking Go and C
* Link together Ocaml, C, and Go as a proof-of-understanding.
* Map the Go types from a few libp2p modules to Ocaml types, then create the intermediate C header descriptions.
* Do some basic functionality tests
* Think through where there needs to be separate single-threaded and multi-threaded versions of the Ocaml wrapper
* go for broke!

we have a wiki
