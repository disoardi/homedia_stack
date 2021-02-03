# Env for automatic download of contente from torrent or other

In this infrastructure we have differente functional roles:
- downloader
    - deluge for torrent stream
- orgnanizer and tracker
    - radarr for movies
    - sonarr for tv shows
- indexer layer
    - jackett for wrap all external indexer
    - flaresolver for by pass the bot controll
- streaming
    - plex

This docker infrastructure join with the base with traefik and portainer.

## Install



## ToDo

Features to add
- [ ] add config for captcha solver to flaresolver

## Authors

Contributors names and contact info

Davide Isoardi abacus@linux.it or business mail davide.isoardi@valuepartners.com

## Version History

* 0.1
    * deploy base config

## License

This project is licensed under the [GPLv3] License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
