# Unraid templates by PilaScat

Docker templates for Unraid Community Applications, for the apps I build and maintain.

## Apps

| App | What it does | Template |
|---|---|---|
| [cinema-watch](https://github.com/PilaScat/cinema-watch) | Ticket hunts for Italian cinemas (UCI, The Space, Webtic cinemas and 18Tickets), with Telegram alerts and the seat map | [cinema-watch.xml](cinema-watch/cinema-watch.xml) |
| [Plex Rewind](https://github.com/RaunoT/plex-rewind) by RaunoT | Plex statistics Spotify Wrapped style, from Tautulli or Tracearr, with Seerr requests | [plex-rewind.xml](plex-rewind/plex-rewind.xml) |

## Install

From the Apps tab in Unraid, search for the app name. Without Community Applications, copy the template to `/boot/config/plugins/dockerMan/templates-user/my-<app>.xml` and add the container from the Docker tab.

Support for each app is in the issues of its own repository.

## License

[MIT](LICENSE). Each app has its own license in its repository.
