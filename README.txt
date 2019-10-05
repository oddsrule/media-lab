Plan is to use terraform to deploy docker infrastructure
for my home media environment.
Media is played by plex, which is not included in this

two distinct containers required for transmission-openvpn

Purpose,Application
MovieManager,radarr
TVShowManager,sonarr
SubtitleManager,bazarr
MovieDownloader,transmission-openvpn-radarr
TVDownloader,transmission-openvpn-sonarr
TorrentIndexerthing,jackett
#WebContainerGUI,portainer
#ContainerWatchdog,watchtower
#Database,mariadb
