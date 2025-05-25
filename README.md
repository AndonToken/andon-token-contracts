# andon-token-contracts
Andon Token v2 - 100% Binance/CEX/Audit-compliant ERC20 token.

# Andon Token (AND)

[![BscScan](https://img.shields.io/badge/BscScan-View-blue)](https://bscscan.com/address/0x12ca8cd01e5d099fb089b5d938e30eae98aafaf5)

## 🌟 Next-Generation, CEX-Compliant, Audit-Ready ERC20 Token on Binance Smart Chain

Andon Token (AND) is a fully decentralized, 100% CEX-compliant, no-tax, no-admin, and open-source ERC20 token contract. Built for security, transparency, and mass adoption!

---

## 🚀 Key Features

- **Fixed Supply:** 100,000,000 AND (18 decimals)
- **No Taxes or Fees:** No buy/sell tax, no transfer fee
- **No Admin or Owner:** Full decentralization, no admin wallet, no further mint, no pausing, no upgrades
- **No Blacklist/Whitelist:** Fully open for everyone
- **Burnable:** Anyone can burn their own tokens
- **No Staking/Locking:** For staking/vesting, use external contracts only
- **Audit-Ready:** Built with OpenZeppelin 5.x standards

---

## 🛡️ Contract Information

- **Contract Name:** AndonTokenV2
- **Symbol:** AND
- **Decimals:** 18
- **Total Supply:** 100,000,000 AND
- **Deployed on:** Binance Smart Chain (BSC)
- **Contract Address:** [`0x12ca8cd01e5d099fb089b5d938e30eae98aafaf5`](https://bscscan.com/address/0x12ca8cd01e5d099fb089b5d938e30eae98aafaf5)

---

## 📄 Contract Source Code

The complete, flattened and verified source code is publicly available on [BscScan](https://bscscan.com/address/0x12ca8cd01e5d099fb089b5d938e30eae98aafaf5#code).

---

## 🌐 Official Links

- [Website](https://andontoken.com)
- [BscScan](https://bscscan.com/address/0x12ca8cd01e5d099fb089b5d938e30eae98aafaf5)
- [Twitter](https://twitter.com/AndonToken) 
- [Telegram](https://t.me/AndonToken) 

---

## 💡 Usage

### Add Token to MetaMask / TrustWallet
1. Open your wallet and click “Add Token”.
2. Paste the contract address: `0x12ca8cd01e5d099fb089b5d938e30eae98aafaf5`
3. Symbol: `AND`, Decimals: `18`
4. Save and start using AND instantly!

### Burn Your AND Tokens
Anyone can call the `burn(amount)` function to burn their own tokens forever.  
**Example:**  
```solidity
AndonTokenV2(tokenAddress).burn(1000 * 10**18);
