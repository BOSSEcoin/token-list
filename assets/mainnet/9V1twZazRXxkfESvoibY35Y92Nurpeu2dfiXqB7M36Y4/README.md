# BOSSE Token Assets

This folder contains the official assets and metadata for the BOSSE token on Solana mainnet.

- **Mint:** `9V1twZazRXxkfESvoibY35Y92Nurpeu2dfiXqB7M36Y4`
- **Symbol:** BOSSE
- **Network:** mainnet-beta

## Files
- `logo.png` → 512x512 PNG with transparent background. Replace the placeholder.
- `metadata.json` → Token name, symbol, description, and extensions (links).

## How to submit a Pull Request to solana-labs/token-list

1. Fork `https://github.com/solana-labs/token-list` to your GitHub.
2. Create the directory: `assets/mainnet/9V1twZazRXxkfESvoibY35Y92Nurpeu2dfiXqB7M36Y4/`
3. Place two files inside:
   - `assets/mainnet/9V1twZazRXxkfESvoibY35Y92Nurpeu2dfiXqB7M36Y4/logo.png` (PNG 512x512, transparent)
   - `assets/mainnet/9V1twZazRXxkfESvoibY35Y92Nurpeu2dfiXqB7M36Y4/metadata.json`
4. Commit and open a Pull Request with the title: `Add BOSSE (9V1twZazRXxkfESvoibY35Y92Nurpeu2dfiXqB7M36Y4)`
5. In the PR description, include:
   - Proof you control the mint (transaction links or signature from the team's wallet).
   - Official links (website, Twitter, Telegram, Discord).
6. Wait for the CI to pass and for maintainers to merge.

## Notes
- Disable `mintAuthority` and `freezeAuthority` for the token to improve trust.
- Keep links consistent with your website and socials.
