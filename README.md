## Tiny self-contained notebook implementations of NeRF

A weekend project where I did quick and simple implementations of the original NeRF paper and a recent improvement that uses a hashtable as local features.

NeRF: https://www.matthewtancik.com/nerf
INGP NeRF: https://nvlabs.github.io/instant-ngp/

The "simple" versions are short, easy to understand and lack most of the more advanced optimizations. The other notebooks implement also sampling of rays randomly from the whole training dataset, as well as hierarhical sampling, which improve the performance quite significantly.