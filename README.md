# Multi-Node Setup of Hyperledger Fabric Network 2.4 (VMs)
A Fabric Network of 3 Orderers with Kafka, 2 Organizations, each has 2 peers, deployed on 4 nodes.

Versions:
Fabric: 2.4
CA: 1.5.2
Kafka: latest

## Node Setup
Required 4 nodes with following setup:

| Node | Zookeeper | Kafka | Orderer | Peer | CLI |
| --- | --- | --- | --- | --- | --- |
| 1 | zookeeper0 | kafka0 | orderer0.example.com | peer0.org1.example.com|cli |
| 2 | zookeeper1 | kafka1 | orderer1.example.com | peer1.org1.example.com|cli |
| 3 | zookeeper2 | kafka2 | orderer2.example.com | peer0.org2.example.com|cli |
| 4 | | kafka3 | | peer1.org2.example.com |cli|
