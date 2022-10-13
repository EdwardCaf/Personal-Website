---
title: "Bitcoin Node"
date: 2022-10-10T21:37:38-04:00
type: "blog"
tags: ["bitcoin", "linux"]
---

## Why run a Bitcoin node?

The process of running your own node provides many benefits to not just yourself, but the Bitcoin network. Bitcoin node operators validate incoming blocks to make sure they follow consensus rules. More information about how Bitcoin nodes secure the network can be found online.

I chose to run the node for personal and ethical reasons. Running my own node allows me to enforce the rules of Bitcoin onto the network and allow me to use Bitcoin without trusting a 3rd party. It also allows me to serve a "lightning node" which is important for self-custody of funds over the lightning network (Layer 2 Bitcoin). I can go into more depth for anyone interested in the topic.

### Hardware & Software

Most of what I used is just my old computer. Old computers would work for most applications of running a node. I also chose Debian 11 for an OS to get stability in the long run. I also plan to use this server for photos and video storage/backup.

- i5 4690k
- 16GB DDR3 RAM
- 2TB Samsung QVO (At least 1TB is needed)
- Debian 11 (OS)
- Umbrel (Bitcoin software suite)

### Setting up the node

1. Plug in a bootable USB with the ISO of Debian 11.
2. Go through the installation process and use the Username "umbrel".
3. Obtain the umbrel installer with `curl -L https://umbrel.sh | bash`.
4. Follow the installer and you'll have Umbrel setup!
5. Add the Bitcoin Node app and let it sync the blockchain (this takes a **LONG** time).
6. Add Lightning node app and open channels (best to follow a tutorial on this part).

This is just a brief overview of what to expect when starting your Bitcoin node journey.

**[Open a channel with my node](https://1ml.com/node/03c943b1c315929551a60e9ff6dbb0ce527f3f87829fcfb06f219ddc546c3ef8e9)**

If anyone is interested in doing it themselves, I would be more than happy to share my expertise on the matter!
