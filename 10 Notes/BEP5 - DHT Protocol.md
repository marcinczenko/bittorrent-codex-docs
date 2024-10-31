---
tags:
  - bittorrent
  - dht
link: http://bittorrent.org/beps/bep_0005.html
related-to:
  - "[[Learn BitTorrent]]"
---
#bittorrent #dht 

| link       | http://bittorrent.org/beps/bep_0005.html |
| ---------- | ---------------------------------------- |
| related-to | [[Learn BitTorrent]]                     |

For the DHT protocol, there are four **queries**:
- `ping`: to check if another node (one from its DHT routing table) is online and reachable,
- `find_node`: find the contact information for a node given its ID,
- `get_peers`: get peers associated with a torrent [[Infohash|infohash]],
- `announce_peer`: to *announce* that the peer, controlling the querying node, is downloading a torrent on a port.
