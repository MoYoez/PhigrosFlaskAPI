## Phigros Flask API Reference

### Based On [PhigrosLibrary](https://github.com/7aGiven/PhigrosLibrary)

### API List

- [x] /api/phi/bests

> args: Session | overflow (max:20)

```{
    "status": true,
    "content": {
        "phi": true,
        "bests": [
            {
                "score": 1000000,
                "acc": 100.0,
                "level": "IN",
                "fc": true,
                "songId": "Adastraperaspera.RabbitHouse",
                "songname": "Ad astra per aspera",
                "difficulty": 15.8,
                "rks": 15.8
            },
            {
                "score": 972338,
                "acc": 99.57353210449219,
                "level": "AT",
                "fc": false,
                "songId": "Stasis.Maozon",
                "songname": "Stasis",
                "difficulty": 16.4,
                "rks": 16.090625251373435
            },
            {
                "score": 975114,
                "acc": 99.28541564941406,
                "level": "AT",
                "fc": false,
                "songId": "DESTRUCTION321.Normal1zervsBrokenNerdz",
                "songname": "DESTRUCTION 3,2,1",
                "difficulty": 16.6,
                "rks": 16.076981457484795
            }
            ...
        ],
        "PlayerID": "压压鸭ya",
        "ChallengeModeRank": 445,
        "RankingScore": 15.800082206726074
    }
}


```

- [ ] /api/phi/re8
- [ ] /api/phi/songs

...


## License

AGPL-3.0 License

