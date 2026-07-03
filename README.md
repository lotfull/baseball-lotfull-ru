# baseball.lotfull.ru

Static mini baseball rules and scenario simulator for a 3 vs 3 first game.

Production:

- https://baseball.lotfull.ru
- nginx root: `/var/www/baseball.lotfull.ru`

Deploy:

```bash
rsync -az --delete ./ root@65.109.29.161:/var/www/baseball.lotfull.ru/
```
