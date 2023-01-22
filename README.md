# awesome-buskill-triggers

This repo contains a list of links to antiforensic software that are designed to lock-down your computer in response to something bad happening, such as your device being physically stolen from you while you're using it.

These "triggers" are designed to be used with the [BusKill Dead Man Switch](https://buskill.in) (open-source [hardware kill cord](https://en.wikipedia.org/wiki/BusKill)) and the [BusKill App](https://github.com/buskill/buskill-app)

# Low-Risk (Non-Destructive)

This section enumerates triggers that are designed to be very safe to use. BusKill *only* ship with non-destructive triggers

 * [lock-screen](https://github.com/BusKill/buskill-app/blob/v0.6.0/src/packages/buskill/__init__.py#L1024)

# Medium to High-Risk

This section enumerates medium-risk triggers (that may accidentally cause data loss or corruption) and high-risk triggers (that are designed to intentionally cause data loss or corruption)

 * [soft-shutdown](https://github.com/BusKill/buskill-app/blob/v0.6.0/src/packages/buskill/__init__.py#L1097)
 * [cryptomator_umount](https://github.com/BusKill/trigger_cryptomator_umount) (WIP)

## Self-Destruct Triggers

This section enumerates triggers that are specifically designed to cause data loss or corruption.

* [LUKS Header Shredder](https://www.buskill.in/luks-self-destruct/)
* [Veracrypt Self-Destruct](https://github.com/BusKill/veracrypt-self-destruct) (WIP)

# LICENSE

This repo is licensed under a [Creative Commons Attribution-ShareAlike 2.0 Generic License](http://creativecommons.org/licenses/by-sa/2.0/).
