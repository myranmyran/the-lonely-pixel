# The Lonely Pixel

One pixel. One custodian. No practical purpose.

The project is a single 1 × 1 SVG. It starts white. Each round, people put themselves forward to look after it, the community votes, and the selected custodian proposes its next colour. The change is recorded here.

## Take part

1. Open [Discussions](https://github.com/myranmyran/the-lonely-pixel/discussions) and find the current nomination thread.
2. Reply with your GitHub username, one six-digit hex colour (for example, `#4A90E2`), and a short reason for choosing it.
3. You may nominate yourself once per round. Nominations stay open for 24 hours.
4. When nominations close, a poll will run in the **Polls** category for 24 hours. Vote for one candidate.
5. The winner becomes the symbolic custodian for seven days and can propose the colour change in a pull request.
6. The repository maintainer reviews and merges the change, then updates the site and [custody log](CUSTODY_LOG.md).

If a round receives no valid nominations, the pixel stays as it is and the round can be opened again.

## A few boundaries

- The pixel is a small community experiment, not a financial asset.
- There is no payment, prize, investment, or transferable ownership.
- “Custodian” is a title only. It does not give anyone access to repository settings or special GitHub permissions.
- A colour change must use a valid six-digit hex value. Pull requests should only change the pixel, the matching status on the site, and the custody log.
- The maintainer may close spam or unrelated submissions and will explain any rejected change in the pull request.

## The files

- `index.html` is the project page.
- `pixel.svg` is the one-pixel image.
- `CUSTODY_LOG.md` records each completed round.
