# Pending

Special thanks to external contributors with PRs included in this release:

BREAKING CHANGES:

* CLI/RPC/Config

* Apps

* Go API
  * \#2310 Mempool.ReapMaxBytes -> Mempool.ReapMaxBytesMaxGas
* Blockchain Protocol

* P2P Protocol


FEATURES:
  * \#2310 Mempool is now aware of the MaxGas requirement

IMPROVEMENTS:
- [metrics] `consensus.block_interval_metrics` is now gauge, not histogram (you will be able to see spikes, if any)

BUG FIXES:
