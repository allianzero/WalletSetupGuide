# WalletSetupGuide

How to set up, back up, and secure a crypto wallet step by step. Follow this guide slowly, with a small amount first. A wallet is only as safe as its backup.

> This guide is educational only, not financial advice. Never share your seed phrase with anyone, for any reason.

## 1. What a wallet really is

A wallet does not hold coins inside your phone. Coins live on the blockchain. Your wallet holds two things:

- **Public address:** like an account number. Safe to share when you want to receive funds.
- **Private key / seed phrase:** the secret that proves you own the address. Whoever has it controls everything in the wallet.

A **seed phrase** is usually 12 or 24 ordinary words, in a specific order. Those words can recreate your entire wallet on any device. That is why losing them means losing the wallet, and sharing them means giving the wallet away.

## 2. Choose the right kind of wallet

### Software wallet (hot wallet)
An app on your phone or a browser extension. Connected to the internet, convenient for everyday use.

- Best for: small amounts, learning, frequent transactions.
- Risk: if your device is compromised, your keys can be exposed.

### Hardware wallet (cold wallet)
A physical device that keeps your keys offline and signs transactions on the device itself.

- Best for: larger amounts you plan to hold long term.
- Risk: you must still protect the seed phrase and the device's PIN.

### Custodial wallet (exchange account)
The exchange holds your keys. You log in with email and password.

- Best for: buying and selling easily.
- Risk: the exchange can freeze, restrict, or lose your funds.

**Beginner rule:** start with a reputable software wallet and a small amount. Move to a hardware wallet once the amount would hurt to lose. Do not keep everything in one place.

## 3. Setting up a wallet, step by step

1. **Download only from the official source.** Go to the wallet project's own website, or the official app store listing linked from it. Never install a wallet from a link in a DM, ad, or search result you have not verified.
2. **Create a new wallet.** Choose "Create new wallet", not "Import", unless you are deliberately restoring an existing one.
3. **Write down the seed phrase by hand, on paper.** Do this in a private place, with nobody watching and no camera pointed at you.
4. **Verify the words.** The app will ask you to confirm the words in order. This proves you wrote them down correctly.
5. **Set a strong password or PIN.** This protects the app on your device. It does not replace the seed phrase.
6. **Do a test receive.** Send a tiny amount to your new address and confirm it arrives.
7. **Do a test send.** Send a tiny amount back, or to another wallet you control, and confirm it. Now you know the wallet works both ways.

Do not skip steps 6 and 7. A wallet you have never tested is a wallet you do not yet trust.

## 4. Backing up your seed phrase properly

Good backups:

- Written on paper, by hand, in two separate safe places (for example, at home and with a trusted family member's safe — never with the wallet's password).
- Stored where fire, water, and casual visitors cannot easily reach it.
- Checked once a year to make sure it is still readable.

Bad backups — never do these:

- A photo of the seed phrase. Photos back up to the cloud automatically.
- A text file, note app, email, or chat message containing the words.
- A screenshot, even one you "deleted" afterwards.
- Telling the words to a friend, a support agent, or anyone online.

**Test your backup once.** The safest test is to restore the wallet on a second device (or after reinstalling the app) using only your paper backup, with a tiny amount in it. If the restore works, your backup works. If it does not, fix the backup before you put real funds in.

## 5. Receiving funds safely

1. Open your wallet and copy your receiving address.
2. Paste it into the sender — never type it by hand.
3. Check the **network** matches on both sides. The same asset on different networks is not interchangeable.
4. Check the first and last few characters of the address after pasting.
5. Start with a small test amount, confirm it arrives, then send the rest.

## 6. Sending funds safely

Before every send, stop and check three things, out loud if it helps:

1. **Address:** is it exactly right? Compare first and last characters.
2. **Network:** does it match the receiving wallet's network for this asset?
3. **Amount and fee:** is the amount right, and do you have enough native coin left for gas?

Then send a test amount first for any new address, new network, or large amount. A few cents of gas on a test is far cheaper than a large amount sent to the wrong place.

## 7. Connecting your wallet to apps and sites

Connecting a wallet to a website or app (usually called "Connect Wallet") does not by itself move your funds. But it does let that site ask you to sign transactions and approvals, and a malicious approval can drain tokens.

Rules for connecting:

- Only connect to sites you deliberately chose, from a link you verified yourself.
- Read every approval before you sign it. If it says "unlimited" and you do not understand why, do not sign it.
- Disconnect wallets from sites you no longer use.
- Regularly review and revoke old token approvals.
- If a site asks for your seed phrase to "connect" or "verify", close it immediately. Real connections never ask for it.

## 8. Common mistakes

| Mistake | Consequence | Fix |
|---|---|---|
| Storing the seed phrase in a photo or cloud note | Cloud breach exposes your whole wallet | Paper only, offline |
| Importing a seed phrase into a random website | The site copies your keys | Only restore in the official wallet app |
| Using the same password everywhere | One breach unlocks everything | Unique passwords, password manager |
| Skipping the test transaction | A wrong address or network costs the full amount | Always test small first |
| Keeping everything on one exchange | Exchange problems freeze all your funds | Spread across wallet types, learn self-custody |
| Losing the seed phrase and having no backup | Funds are unrecoverable | Two paper backups, tested restore |

## 9. If something goes wrong

- **You sent to the wrong address:** contact the owner if you know them. Otherwise, the funds are almost always unrecoverable. Do not pay anyone who promises to "recover" them for a fee — that is a second scam.
- **You shared your seed phrase:** move your funds to a brand-new wallet with a brand-new seed phrase immediately, before the other party does. Treat the old wallet as compromised forever.
- **Your device is lost or stolen:** your funds are safe if your seed phrase backup is safe. Restore on a new device from the paper backup, then move funds to a fresh wallet if you worry the old device could be unlocked.
- **You suspect a malicious approval:** revoke the approval, and move your funds to a fresh wallet if you are unsure.

## 10. Security checklist

- [ ] Wallet downloaded from the official source only.
- [ ] Seed phrase written on paper, verified in order, stored offline in two places.
- [ ] Restore tested with a tiny amount.
- [ ] Strong, unique password or PIN on the wallet app.
- [ ] 2FA on the email account tied to any exchange.
- [ ] Test receive and test send completed.
- [ ] Old approvals reviewed and revoked.
- [ ] No seed phrase photo, file, or message exists anywhere.

## 11. Frequently asked questions

**Can I have more than one wallet?**
Yes, and you should. Separate wallets for learning, everyday use, and long-term holding reduce the damage of any single mistake.

**What happens if I lose my phone?**
Nothing, if your seed phrase backup is safe. Install the wallet on a new device and restore from the paper backup.

**What happens if I lose my seed phrase?**
The wallet cannot be recovered by anyone — not the wallet company, not the network, not support. This is the trade-off of self-custody.

**Is a wallet address the same as a seed phrase?**
No. The address is public and safe to share. The seed phrase is secret and must never be shared.

**Should I use the same wallet for everything?**
No. A wallet you connect to many experimental sites should not hold your long-term savings.

> Educational content only. This is not financial, legal, or tax advice.
