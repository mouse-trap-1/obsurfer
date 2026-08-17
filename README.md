# obsurfer — Navigation & Usage Guide

obsurfer is a web client for interacting with a DAO/token platform on the Sepolia Ethereum test network. It allows users to trade NFTs as part of a DAO, sharing a stake in the DAOs trades and allowing users to vote on trades that can either permit or deny a trade to happen.

[LINK](https://receives-from-advertisements-networking.trycloudflare.com)
[Discord LINK](https://discord.gg/MMc4a4EGD)

## Signing in

When you open the app, what you see depends on your session state:

- **Restoring session…** — a brief loading state shown while the app checks whether you have an existing session.
- **Signed out** — you'll land on one of three screens, switchable via on-screen links:
  - **Login** — sign in with an existing account.
  - **Register** — create a new account.
  - **Import** — bring in an existing wallet/account instead of creating a new one.
- **Locked** — your account exists and was previously set up on this device, but needs to be unlocked (e.g. with a password) before you can continue.
- **Unlocked** — you're signed in and see the full app with the tab strip and status bar.

## The status bar

Once you're past sign-in, a status bar sits at the top of every screen and shows:

- **Network** — which chain you're connected to (shown as "Sepolia" when on chain ID 11155111, otherwise the raw chain ID).
- **Your account** — once unlocked, a shortened version of your wallet address is shown on the right. If your session is locked, this area shows "locked" instead.

This bar is a quick way to confirm you're on the right network and signed in as the right account before doing anything that costs money.

## The tab strip

Once unlocked, six tabs run across the top of the app. Click any tab to switch screens; the active tab is underlined in blue.

| Tab | What it's for |
|---|---|
| **Home** | The default landing screen after unlocking. |
| **All DAOs** | Browse all DAOs / rounds available on the platform. |
| **My DAOs** | View the DAOs / assets associated with your account. |
| **Deploy** | Deploy a new DAO. |
| **Leaderboards** | View rankings/leaderboards. |
| **Sell Token** | Sell a token you hold. |

Only one tab's content is shown at a time — switching tabs doesn't reload the app, it just swaps the visible panel.

## All DAOs

You can find all the DAOs that are available, select on one to begin your journey. Displayed is the DAOs data and held NFTs and from there you can decide if it's the right investment for you. 

Here you can find shares available for sale, if there are any, and a selector box to buy shares. Shares are used to hold seats for voting and is used to calculate the percentage of profit you receive.

Admins can see additional buttons that assist in the upkeep of the DAO.

## My DAOs

Once you have invested in a DAO, it will appear here. Click on a DAO to get started.

Here you can find the proposals list, select a proposal to vote or execute, or create a proposal via one of the buttons. Creating a proposal opens up a form to enter the details of the NFT etc. 

Sell -> DAO sells NFT to user
Buy -> DAO buys NFT from user

## Deploy

Here you can find a form to deploy a DAO. Admins can set the percentage of profit vs revenue where revenue is funds reused for purchasing NFTs and profit is distributed amongst shareholders.

## Leaderboards

[Under Construction] 

## Sell Token

Here you can find all tokens any user wants to sell to a DAO. You can also create a sale by clicking the button and filling out the form. You must own the token in your wallet. 

Clicking on a NFT you own will enable you to compare and accept a bid from a DAO.

## Modals and confirmations

Two dialogs are always available regardless of which tab you're on, and will pop up over whatever you're doing when triggered:

- **Notices** — informational or error messages (styled with a colored left border: green for success, amber for warnings, red for errors).
- **Transaction confirmations** — before anything that spends money or writes to the blockchain goes through, you'll be shown a confirmation dialog to review and approve it.

## Visual cues

A few consistent visual patterns to know:

- **Colored dots/text** — green usually means "OK" or connected, amber means a warning, red means a failure.
- **Cards and tables** — lists of DAOs, tokens, or leaderboard entries are shown as either a grid of clickable cards or a data table; clicking a row or card typically opens its detail view.
- **Disabled buttons** — greyed-out, unclickable buttons indicate an action isn't currently available (e.g. missing required input, or a transaction already in progress).
- **Spinners** — a small spinning indicator next to text means the app is waiting on something (a session restore, a network call, etc.).

## Notes

- The app targets the Sepolia test network, not Ethereum mainnet — check the status bar to confirm before assuming otherwise.
