# Meme Trading Bot

This bot automatically trades meme tokens based on wallet activity, token safety, and social media presence. It integrates with APIs for market data, safety checks, and social sentiment analysis to identify potential trading opportunities.

---

## **Features**
- **Monitor Profitable Wallets:** Fetches profitable wallet addresses daily from Monitor.fi.
- **Token Analysis:** Evaluates token distribution using DEX Screener.
- **Safety Checks:** Validates tokens against rug-pull risks using SolSniffer.
- **Social Media Sentiment:** Assesses token support via TweetScout.
- **Automated Trading:** Places buy orders using Toxi Solana Bot (optional).

---

## **Setup Instructions**

### **1. Prerequisites**
- Node.js installed on your system.
- API keys for the following services:
  - SolSniffer
  - TweetScout
- A GitHub account for deploying the bot.
- A Railway account for deployment.

---

### **2. Clone the Repository**
Clone the repository to your local machine or upload the files directly to GitHub.

---

### **3. Environment Variables**
Create a `.env` file in the root directory and add your API keys:

