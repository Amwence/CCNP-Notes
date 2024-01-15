# Enterprise Architecture

## 2 Tier or Collapsed Core Design

2 Tier Design is (Collapsed Core) architecture takes the normal three-tier hierarchical network and collapses it into a two-tier network. In a two-tier network, the function of the switches in teh core layer and distribution layer are "collapsed" into a combined core and distribution layer on a single switch. 

![2 Tier vs. 3 Tier Design](Amwence/CCNP-Notes/Pictures/Collapsedcorevs3tier.png)

> The ***Core Layer*** is the backbone of the network (e.g. upstream routers in your home network). It provides high-speed connection between different distribution layer devices. The ***Distribution Layer*** connects the access layer to the core layer (e.g. switches connecting floors of a building). The ***Access Layer*** provides initial connection to end users. 