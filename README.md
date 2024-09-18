# Euro Final 2024 data

Getting data for football analysis can be difficult, I wanted to play and practice with the data of the [Euro Final 2024](https://www.fotmob.com/es/matches/spain-vs-england/1wvxa5#4043985). In this repository you'll find relevant information I found and some visualizations for the shots.

## Repository details

- Scrape data from [FotMob](www.fotmob.com)

__What can you get from euroFinal.ipynb?__

- matchId, team colors, home team, away team
- events -> home & away goals
- player of the match -> shotmap, stats(attack, defense, duels)
- events -> added time, half, substitution, GOAL(details), assist
- stadium info
- home & away top player
- match momentum
- top stats -> ball possesion, xG, total shots, shots on target, big chances, big chances missed... shots, xG, passes, defence, duels, first half, second half
- stats players -> top stats, attack, defense, duels
- shots, shots by periods
- line up starters info, coach info, subs info

__What can you get from shots.ipynb?__

- shots as a DataFrame
- save shots as a CSV
- read CSV shots
- different types of visualizations using mplsoccer such as:
  - all shots in a single pitch
  - shots by team with xG
  - Shots by team in different fields
  - Vertical pitch, shots by team in different fields
  - Spain shots, vertical pitch
  - Shots by player ID
  - Shots by periods

## License

Feel free to use and re-use any way you want.

## More

- Follow me on Twitter [axel_bol](https://x.com/axel_bol).
- Check my YouTube channel [Dot Coding](https://www.youtube.com/@DotCoding).
- Feel free to send me an e-mail for support [dot.bol.lp@gmail.com](mailto:dot.bol.lp@gmail.com).
