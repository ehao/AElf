# AElf

# Project Status

HeHe, Early stage, still under development.

# Development Roadmap

## Phase1 : the internal affair of the wonderland (Nov 2017 - March 2018)

1. A graph-based scheduler algorithm implementation. [INTRO SCHEDULER](docs/SCHEDULER.md)
2. Tagged primitive resource Data-Structure(sstable a.k.a. sorted string table), the basic element for resource isolation, backed by distributed KV database, this structure is comparable to dataflow processing paradigm(like mr/reactivex).
3. In-cluster wire protocol(data/task marshal/unmarshal).
4. Actor(eg. akka) based task distribution inside a single cluster/ledger.
5. A contract for demostration of concurrent execution.

## Phase2 : a tale between two nodes (March 2018 - May 2018)

1. tx_pool/mem_pool design(unconfirmed tx).
2. basic block in-memory construct, eg: merkletree, block header, transactions, statsdb, caching.
3. wire protocol for inter-ledger block/tx transfering.
4. dPoS implementation, hashing, mining.
5. block validator, crypto related algorithms, eg signing, hmac.
6. p2p discovery/communication

## Phase3: the mainchain (May 2018)

1. crosschain，two-way peg, merkle proofs.
2. event trigger from one sidechain to another, a.k.a cross chain interoperability.

## Phase4: the governance (May 2018 - August 2018)

1. voting mechanism for sidechain join/leave
2. voting mechanism for emergency treatment 


## Phase5: ready to launch (August 2018 - January 2019)

1. code optimization before mainnet launching.
2. code review, pre-releases. 
3. business case battle test(public beta).





