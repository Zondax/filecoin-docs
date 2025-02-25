---
title: "Explore the network"
description: "There are several ways to explore and get insights from the Filecoin network."
lead: "There are several ways to explore and get insights from the Filecoin network."
draft: false
images: []
type: docs
menu:
  get-started:
    parent: "lorem"
    identifier: "explore-the-network-907ce577ef35ff2110ac2ddf7cbd2661"
weight: 20
toc: true
aliases:
    - "/build/the-filecoin-ecosystem/"
---

## Block explorers

Block explorers allow you to view the details of the Filecoin network on a single website. Individual block explorers contain different features that may be useful. None of these sites are created or maintained by Protocol Labs or the Filecoin Foundation. This list is in alphabetical order:

### Filfox

Website: [filfox.io](https://filfox.io)

![](filfox.png)

### Filscan

Website: [filscan.io](https://filscan.io)

![](filscan.png)

### Filscout

Website: [filscout](https://filscout.io)

![](filscout.png)

## Lotus

Once you are [set up with Lotus](https://lotus.filecoin.io), you can use the command line to query information about the network.

Get the head tipset:

```shell
lotus chain head
```

Print a block:

```shell
lotus chain getblock <block_cid>
```

Print message information:

```shell
lotus chain getmessage <message_cid>
```

For additional chain-related commands:

```shell
lotus chain --help
```
