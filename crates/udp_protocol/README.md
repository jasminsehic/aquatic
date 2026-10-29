# aquatic_udp_protocol: UDP BitTorrent tracker protocol

UDP BitTorrent tracker message parsing and serialization.

Implements [BEP 015](https://www.bittorrent.org/beps/bep_0015.html) ([more details](https://libtorrent.org/udp_tracker_protocol.html)).

Also parses and serializes UDP announce event `4` (`paused`) for
[BEP 021](https://www.bittorrent.org/beps/bep_0021.html) partial seeds. Event
`4` is an implementation convention, not defined by BEP 15. The UDP message
format and scrape fields are unchanged.
