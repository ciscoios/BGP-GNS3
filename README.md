# BGP-GNS3
In this lab two routers (R2 and R3) act as router reflectors and in this case we don't need to create a full mesh topology to announce our networks beetween all BGP peers.
We only need to make a neighbourship with router reflectors and router reflectors in its turn will announce all neighbour networks.
Also we should additionally configure routing beetween BGP neighbours, to make it possible we can configure BGP inside our network, but since BGP AD inside private networks will be by default 200 and it'll be working quite slow,
it was decided to configure routing by using IGP protocol (OSPF). 
+ configures includes peer-group configuration on router R1 and R4 and BGP authentication
