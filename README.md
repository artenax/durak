# Durak - An online multiplayer card game

[![Build Status](https://travis-ci.org/rnixik/durak.svg?branch=master)](https://travis-ci.org/rnixik/durak) [![Go Report Card](https://goreportcard.com/badge/github.com/rnixik/durak)](https://goreportcard.com/report/github.com/rnixik/durak)

Rules are described on [Wikipedia](https://en.wikipedia.org/wiki/Durak).

![durak](https://user-images.githubusercontent.com/107228652/213781200-48f5b510-a65a-4027-b8a6-1bcffdfa24ec.png)

## Run

```bash
go build . && ./durak
```

## Deployment on production

```bash
bash scripts/release.sh
```

## Roadmap

[x] Basic structs and client-server interactions  
[x] Pile of cards, shuffle, deal  
[x] Lobby: creating a room, joining a room, leaving a room  
[x] Lobby: creating a game, joining a game, leaving a game, starting a game  
[x] Basic visualizing of cards on client-side  
[x] Game process and rules  
[x] I18n  
[x] Observing started games, joining by an url  
[x] Simple AI  
[ ] Advanced visualizing of cards on client-side: animations, drag'n'drops  
[x] Full structured log of games  
[ ] AI based on saved games  

## License

The MIT License
