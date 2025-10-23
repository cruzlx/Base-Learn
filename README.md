# Base-Learn
Educational docs inspired by Base Learn
# 🧠 Learn to Build Smart Contracts and Onchain Apps on Base Sepolia

Welcome to **Base-Learn** — a step-by-step, hands-on tutorial to build, deploy, and interact with smart contracts using **Remix IDE** and the **Base Sepolia testnet**. Follow the lessons in order; each step links directly to the file in this repository so you can open, copy, and run the code in Remix.

---

## 💧 Base Sepolia Faucet Links

Before starting, make sure you have test ETH for the **Base Sepolia** network. You’ll need it to deploy contracts and interact via Remix.

Claim free Base Sepolia ETH from one of these trusted faucets:

1. [Alchemy Base Sepolia Faucet](https://www.alchemy.com/faucets/base-sepolia)
2. [Chainstack Faucet](https://faucet.chainstack.com/)
3. [Optimism Console Faucet](https://console.optimism.io/faucet)

---

## 🔁 How to use this tutorial (quick)

1. Open Remix: [https://remix.ethereum.org](https://remix.ethereum.org)
2. Click the file link in the step below to open the source on GitHub.
3. Copy the contract code from GitHub and paste a new file in Remix (create a file with the same name).
4. Compile in Remix, connect MetaMask (set network to Base Sepolia), then deploy and interact.

> Tip: If a file name contains spaces, GitHub will show it properly — use the link to view the raw file content.

---

## 📖 Step-by-step lessons

Click a step to open the file in your repo.

1. [**AddressBook.sol**](https://github.com/sntacruzz/Base-Learn/blob/main/AddressBook.sol) — basic wallet/address book contract.
2. [**Control Structures**](https://github.com/sntacruzz/Base-Learn/blob/main/Control%20Structures) — conditionals, loops, and flow control in Solidity.
3. [**Arrays**](https://github.com/sntacruzz/Base-Learn/blob/main/Arrays.ts) — working with arrays (dynamic, fixed-size, arrays of structs).
4. [**Storage**](https://github.com/sntacruzz/Base-Learn/blob/main/Storage%20in%20Solidity) — storage vs memory, gas implications, layout.
5. [**Mappings**](https://github.com/sntacruzz/Base-Learn/blob/main/The%20Mapping%20Type) — how to use mappings for key-value storage.
6. [**Inheritance**](https://github.com/sntacruzz/Base-Learn/blob/main/Inheritance) — contract inheritance and visibility.
7. [**Structs**](https://github.com/sntacruzz/Base-Learn/blob/main/Structs) — defining and using structs in Solidity.
8. [**Error**](https://github.com/sntacruzz/Base-Learn/blob/main/Error) — error handling with `require`, `revert`, and custom errors.
9. [**Keyword**](https://github.com/sntacruzz/Base-Learn/blob/main/The%20New%20Keyword%20Other%20Contract) — using `new` and interacting with other contracts ("The New Keyword Other Contract").
10. [**Imports**](https://github.com/sntacruzz/Base-Learn/blob/main/Import) — modularizing contracts using `import` statements.
11. [**ERC721**](https://github.com/sntacruzz/Base-Learn/blob/main/ERC721) — an example NFT implementation and how to mint/interact.
12. [**Minimal**](https://github.com/sntacruzz/Base-Learn/blob/main/Minimal) — minimal contract to demonstrate the deployment flow.
13. [**ERC20**](https://github.com/sntacruzz/Base-Learn/blob/main/ERC20) — basic ERC20 token implementation and testing.

---

## 🪙 Learn to Mint NFTs on Base

For a complete guide on how to mint NFTs on Base Sepolia, check out:
👉 [Base Learn Docs — Mint NFTs on Base](https://docs.base.org/learn/welcome)

---

## 🛠 Remix-specific steps (detailed)

1. Open Remix: [https://remix.ethereum.org](https://remix.ethereum.org)
2. In the left panel, click the **File Explorers** → **+** to create a new file.
3. Name the new file exactly as the lesson file (e.g. `AddressBook.sol`).
4. Open the corresponding GitHub link above and copy the contract code.
5. Paste into the new Remix file, save, then go to the **Solidity Compiler** plugin and compile.
6. Open **Deploy & Run Transactions**, choose **Injected Provider - MetaMask**, set network to **Base Sepolia** in MetaMask.
7. Deploy contract and interact via Remix UI.

---

## 🔎 Troubleshooting & tips

* If compilation fails, check the Solidity version in the file's pragma and set the same compiler version in Remix.
* For contracts that import other files, paste the imported contract(s) as separate files in Remix with the same relative paths.
* If MetaMask doesn’t show Base Sepolia, add it manually in MetaMask’s network settings (RPC URL for Base Sepolia may vary; use a trusted RPC provider or the Base docs).

---

## 📚 Next steps

* After finishing all lessons, try combining them: build a dApp where an ERC20 token and an ERC721 interact (for example, paying fees to mint NFTs).
* Learn deployment scripting with Hardhat once you’re comfortable with Remix.

## ☕ Support & Donations
If this tutorial helped you, consider sending a small donation to support more educational content:

0x5629AEA7C12097bB4aF9920577Dcd5fC33D3f77e (cruzl.eth)