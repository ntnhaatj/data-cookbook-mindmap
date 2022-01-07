# Introduction
On-chain analytics service.

Aims to implement collector which gather all subscribed events on particular blockchain smart contract.

Requirements:
- subscribe buy/sell activities on nft exchange smart contract.
- be able to batch processing all blocks.
- be able to stream new activities.
- rule engine for alerting.
- visualization dashboard.
- 1-click-to-deploy collector.
- performance is measurable and collected in datastore.


# Objectives

- understand blockchain, web3.0 development

```
Key results:
- understand events log on ethereum/bsc/polygon.
- deploy smart contract on local network.
- understand the graph (be able to use subgraph, query...)
```
---

- full data pipeline design 
```
Key results:
- block diagram to show system interaction
- component design (class, routine)
- database schema design
```
---

- launch collector backbone successfully
```
Key results:
- run as batch processing
- run as streaming service (optional)
- scalability on multiple smart contract (easily integrate at least 2)
- easily deployment by 1 command
```
---

- benchmark performance tool
```
Key results:
- tracking ingestion time delay of streaming service
- tracking processing time of batch version
- tracking processing time of each component in system
```
---

- learning something new 
```
Key results:
- at least 1 tool for benchmarking performance
- at least 1 tool for buffering message queue
```