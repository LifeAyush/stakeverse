# Stakeverse

Marketing pages for Stakeverse.

## Pages

The app is a React site with three routes and a shared navbar.

- **About us** (`/`) is the home page. It shows a hero, collection copy, item stats, and a recent-sales list. Desktop and mobile layouts are included.
- **Stakeverse** (`/stakeverse`) is the staking page. It shows total rewards earned, total NFTs, NFTs available for staking, and an amount available to claim. A sidebar repeats claimable rewards, total rewards, staked NFTs, and total NFTs. NFT cards sit beside that sidebar. Desktop and mobile layouts are included.
- **MiniMarket** (`/minimarket`) is a route placeholder.
- **Navbar** links to About us, MiniMarket, and Stakeverse. It also shows a notification icon, a coin balance, and a user control, with a hamburger menu on small screens. About us and Stakeverse both use it.

## Run

```bash
git clone https://github.com/LifeAyush/stakeverse.git
cd stakeverse
npm install
npm start
```

Scripts from `package.json`:

- `npm start` starts the development server.
- `npm run build` creates a production build.
- `npm test` runs the test runner.

## License

MIT
