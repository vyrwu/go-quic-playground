# TODO

Use https://github.com/golang/net for Multicast, https://github.com/lucas-clemente/quic-go for Quic.
PoC goal, send a single QUIC packet to two clients in the multicast group. That would show that we are able to multicast data.

Then, we will experiment with how to wrap HTTP requests into QUIC, and how can we actually send streaming data over Multicast.

