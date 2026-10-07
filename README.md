# Urania's Mirror

**Play: <https://bertblookers.github.io/>**

Small daily puzzles about the sky, each at its own address and in its own
repository:

- **[Muldle 𒀯](https://bertblookers.github.io/muldle/)** — find the
  astronomical object name or identifier: a Wordle for deep-sky catalogues,
  constellations and stars.
  Source: [bertblookers/muldle](https://github.com/bertblookers/muldle).
- **[Retractle](https://bertblookers.github.io/retractle/)** —
  *work in progress.* A paper has been accidentally retracted! Restore a
  famous astronomy paper word by word.
  Source: [bertblookers/retractle](https://github.com/bertblookers/retractle).
- **Constelle** — *in the works:* find the constellations.

The name comes from *Urania's Mirror* (1824), a boxed set of 32
constellation cards with holes punched where the stars are, to hold up
to the light: a parlour game for learning the sky.

This repository holds the hub page, and `shared.css`: the look (palette,
star field, footer) the hub shares with the games built for it. Such a game
copies `shared.css` into its own repository when it is released, so no game
loads files from another. Muldle, which came first, has its own stylesheet
with the same palette.

## Privacy

No accounts and no tracking. The hub stores nothing; each game keeps your
games only in your own browser (`localStorage`).

## Run locally

It's a static site: serve the repository root with any web server, e.g.

```
python -m http.server 8081
```

then open <http://localhost:8081>. The games' links work on the live site,
where every game is served beside the hub.

## Data & attribution

See [ATTRIBUTION.md](ATTRIBUTION.md). Each game credits its own sources in
its own repository.

## License

The code is licensed under the GNU Affero General Public License v3.0; see
[LICENSE](LICENSE). SPDX: `AGPL-3.0-only`.
