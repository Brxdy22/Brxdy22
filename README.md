# Brxdy22

Plugins and tools for [Dispatcharr](https://github.com/Dispatcharr/Dispatcharr).

| Project | What it does |
|---|---|
| [M3U Failover](https://github.com/Brxdy22/Dispatcharr-M3U-Failover) | Proxy that gives an M3U account several provider URLs and fails over between them. Docker image: [brxdy22/m3u-failover](https://hub.docker.com/r/brxdy22/m3u-failover) |
| [VOD Failover](https://github.com/Brxdy22/Dispatcharr-VOD-Failover-Plugin) | Retries a failed VOD stream on the next provider account that carries the title |
| [Gluetun AutoSwitch](https://github.com/Brxdy22/Dispatcharr-Gluetun-AutoSwitch-Plugin) | Moves Gluetun to another VPN exit when streams slow down, VOD is refused or speed tests fail |
| [Clean Titles](https://github.com/Brxdy22/Dispatcharr-Clean-Titles-Plugin) | Renames VOD movies and series to their official TMDB titles and tidies provider categories |
| [Teamarr Assistant](https://github.com/Brxdy22/Dispatcharr-Teamarr-Assistant-Plugin) | Tags regional sports networks with their teams and starts Teamarr generations when new streams appear |

M3U Failover, VOD Failover and Gluetun AutoSwitch work together: provider URL failover, account failover for VOD, and VPN exit switching. Setup guide: [Dispatcharr Failover Stack](https://github.com/Brxdy22/Dispatcharr-Failover-Stack).
