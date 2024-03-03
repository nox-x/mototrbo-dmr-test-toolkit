# Mototrbo DMR test toolkit

Toolkit providing some information and test cases helping to understand Motorolas DMR protocols.

## Local example test setup

```txt
+-----------+                               +---------+
|           |                               |         |
| Local PC  | eth0        00:11:22:33:44:55 | Gateway |
|           +---------[ USB cable ]---------+ radio   |
|           | 192.168.10.2     192.168.10.1 |         |
+-----------+                               +---------+
                                              
                                                 A
                                                 |
                                                 V
                                              
                                                DMR
                                               radio
                                              channel
                                              
                                                 A
                                                 |
                                                 V
                                              
                                            +---------+
                                            |         |
                                            | Remote  |
                                            | radio   |
                                            |         |
                                            +---------+
```

## Request gps position

Requests GPS position from a remote radio, parses it and provides an OSM-link showing the polled coordinates on a map.

## Other Projects

- <https://github.com/JarvisSmallhouse/gateway/blob/master/src/Protocols/LRRP.js>
- <https://forums.radioreference.com/threads/motorola-lrrp-protocol.370081/>
