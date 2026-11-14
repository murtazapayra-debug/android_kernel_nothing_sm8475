# Nothing stock BakaSU + SUSFS port

This branch is based directly on NothingOSS sm8475/b/mr (Linux 5.10.252).
It intentionally does not merge the divergent Arter kernel history.

The existing BakaSU/SUSFS build workflow and tested Pong defconfig are
carried over for the first compile-validation pass. Arter-only source
features, including charging-current control and vibration changes, are
not yet declared ported; they must be reviewed and applied as focused
patches against this stock base after the BakaSU/SUSFS baseline builds.
The packaged test boot image is pinned to the matching Pong B4.1-260818-1726
stock release and is TEST-ONLY.
