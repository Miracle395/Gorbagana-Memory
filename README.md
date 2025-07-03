# Gorbagana-Memory

Gorbagana Multiplayer Memory Game.

Its a sleek, two player, turn based memory card matching game, i built it with Firebase for realtime sync and integrated with the Gorbagana testnet for token gated access via Backpack Wallet.


**Pay to Play. Match to Win. Show your memory muscle.**


🎮 Game Overview

This is a multiplayer memory card game where:

Players join the same room via a shared link.

Each player must pay a small amount of testnet $GOR (Gorbagana) to unlock gameplay.

Turns alternate after every flip/match, synced in real time.

First to finish all matches wins.

Designed with soft snowflake animations, ambient music, and clean card-flip UI.❤️







Gorbagana Integration

This game uses:

✅ Gorbagana RPC: to send and confirm transactions.

✅ Backpack Wallet: to connect and sign Solana testnet payments.

✅ Testnet SOL payment gate: Game only starts after the payment is confirmed on-chain.

✅ Recipient Wallet: Payments are sent to:
7NUGG7w9aL7czQEN1ouZrErFnfXkbBVD3HqA7jVHWvBL






How to Run Locally.

Requirements:

A local static server (e.g., Live Server extension in VSCode, or Python/Node server)

Testnet SOL on Gorbagana

Backpack Wallet installed in your browser




Steps:

1. Clone the repo or download source
Place all files (HTML, JS, images, etc.) in a folder.


2. Open the index.html in a local server

You can’t just open the HTML directly due to Firebase/Web3 dependencies.

Use a static server like:

python3 -m http.server

or use Live Server in VSCode.



3. Connect your Backpack Wallet


4. Click “Pay to Play”

Confirm the testnet transaction

Once confirmed, game starts!



5. Share the room link

Another player must visit the same link and pay too.



🌍 Online Demo:

(https://gorbagana-memory.vercel.app)



Tech Stack

✓ HTML + CSS + Vanilla JavaScript.

✓ Firebase Realtime Database.

✓ Solana Web3.js

✓ Backpack Wallet.

✓ Gorbagana RPC.
