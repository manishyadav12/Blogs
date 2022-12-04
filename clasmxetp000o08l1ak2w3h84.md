# What is InterPlanetary File System (IPFS)

# Overview

A majority of the platforms and data we have today are stored on central cloud servers owned by a few technology corporations like Google, Amazon, Microsoft, and IBM.

Due to centralized data storing downtime in these servers is high, affecting a large number of users.

Central servers often face issues and become inaccessible, resulting in the URLs failing to access websites and platforms and loading it on our browsers.

An alternative to centralized data storage is IPFS.

# What is IPFS

IPFS is built by Juan benet of protocol labs, The Interplanetary File System (IPFS) is a distributed file storage protocol that allows computers all over the globe to store and serve files as part of a giant peer-to-peer network.


![p2pipfs.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1669146612241/8IEIyHIQ3.png align="left")


If the server is unavailable or goes down, in the case of HTTP, we would not be able to access the data. On the other hand, with the IPFS protocol, this data is copied to several nodes and is accessible whenever necessary.

# How IPFS works

IF files are uploaded to IPFS, it will be split into smaller chunks and distributed over multiple computers and IPFS assigns a hash to allow users to locate the file.

 Rather than point you towards a *location*, IPFS links point you towards the *content*, which could be stored on any number of nodes or computers around the world. As long as the website or content is hosted on at least one computer, however, it will always be accessible.

IPFS allows to update the existing to a new version by connecting it to the old version.

It is **not** based on blockchain but is considered as the backbone of **web3**.



![http-vs-ipfs.a90615df.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1669146399549/1wSWeQfRn.png align="left")


Now, imagine accessing the file from the IPFS network. The file, and all of its blocks, are identified by a unique hash of the content itself. 

The whole system is based around a key-value data store. This is what allows for the content addressing: anyone can host the key no matter the origin of the information. So, you would connect to the swarm and request to the network that file. 

It would first look to the peers closest to you because chances are they have a copy of that file. If they don’t, however, you will connect with the node that originally uploaded the file, since he’s the one that hosts it.

# Who is using IPFS

- [Filecoin](https://filecoin.io/), Protocol Labs’ own distributed storage network, is based on IPFS. It 
   incentivizes node operators 
   to host files via cryptocurrency rewards.
- [Audius](https://audius.co/), a decentralized music service, uses IPFS to host its audio files.
- [Pinata](https://www.pinata.cloud/) is an NFT hosting service that uses IPFS to back up crypto- 
   collectibles for partners 
   like [Rarible](https://rarible.com/) and [Sorare](https://sorare.com/).
- [OpenBazaar](https://github.com/OpenBazaar) is a peer-to-peer e-commerce platform driven by IPFS.
- [Morpheus.Network](https://morpheus.network/) is a supply chain network service that also utilizes 
   IPFS.


