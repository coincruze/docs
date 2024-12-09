# Setting Up Your Coincruze Account

This guide will walk you through the process of setting up your Coincruze account and getting started with automated trading. Follow these steps to complete your initial setup.

## Step 1: Create an Account

1. Visit [coincruze.com](https://coincruze.com)
2. Click on "[Sign Up](https://coincruze.com/users/sign_up)" in the top navigation bar
3. Fill in your registration details:
    - Trading nickname
    - Your full name
    - Email address
    - Password
    - Confirm password
4. Accept the Terms of Service and Privacy Policy
5. Click "Create Account"

## Step 2: Choose a Plan

Selecting the right subscription plan is crucial to unlocking the full potential of Coincruze's AI-powered trading platform. We offer flexible plans designed to accommodate different trading needs, experience levels, and investment goals. When choosing a plan, carefully consider factors such as the number of bots you want to run, the exchanges you'll be trading on, and the complexity of trading strategies you wish to deploy. Our plans are structured to provide scalability, allowing you to start small and upgrade as your trading sophistication grows.

Coincruze operates on a subscription model, which means that an active subscription is essential to access and utilize our platform's features. Without a subscription, you won't be able to create or run trading bots, connect exchanges, or leverage our AI optimization tools. We recommend reviewing our [Pricing](https://coincruze.com/pricing) page to explore the current plans in detail, compare their features, and select the one that best aligns with your trading objectives.

We offer attractive annual plans that come with significant discounts, providing a cost-effective way to maximize your trading potential while reducing your overall investment in the platform.

## Step 3: Trading Server Setup

!!! info
      No action is required from you during this step - just wait for the setup to complete.

Once you've selected your plan, Coincruze will automatically set up your dedicated trading server. This process:

- Creates your secure trading environment
- Configures necessary trading components
- Establishes connections to our AI systems
- Takes approximately 2 minutes to complete

## Step 4: Connect to a Crypto Exchange

### Create an Exchange Account (If Needed)

Before connecting to Coincruze, you'll need an active account with a supported cryptocurrency exchange. If you haven't already registered:

1. Choose from our supported exchanges: 
   - Binance
   - BingX
   - BitMart
   - Bybit
   - Gate.io
   - HTX
   - Kraken
   - OKX
2. Visit the exchange's official website
3. Click "Register" or "Sign Up"
4. Complete the registration process:
   - Provide required personal information
   - Verify your email address
   - Complete Know Your Customer (KYC) verification
   - Enable two-factor authentication (2FA)
5. Fund your account with cryptocurrency or fiat currency

!!! warning "Important"
    Always use official exchange websites to prevent phishing. Verify the URL carefully before registering.

### Connect Exchange to Coincruze

After creating your exchange account, connect it to Coincruze:

1. Click on the "Connect to a crypto exchange" option
2. Select your preferred exchange from the supported platforms
3. Follow the exchange-specific API key setup instructions
4. Enter your API credentials:
   - API Key
   - API Secret
   - Additional security settings (if required)
5. Test the connection

!!! info "Important"
    Make sure to enable trading permissions when creating your API keys, but restrict withdrawal permissions for added security.

### Exchange Specific Notes

#### Binance Configuration
When setting up Binance, users must be aware of several critical configurations:
- Select the correct Binance platform:
  - International users: Standard Binance
  - US-based users: Binance.US
- Futures Trading Requirements:
  - Complex quantitative rules govern trading
  - Minimum stake amounts apply to prevent trading restrictions
  - Mandatory settings:
    * Position Mode: Set to "One-way Mode"
    * Asset Mode: Set to "Single-Asset Mode"
  - Failure to configure these settings will prevent bot activation

#### OKX API Configuration
OKX requires an additional security step:
- Each API key must include a unique passphrase
- Ensure the passphrase is correctly entered during configuration

#### Gate.io API Permissions
Specific API key permissions are crucial for Gate.io:
- Required Permissions:
  * "Spot Trade" or "Perpetual Futures" (Read and Write)
  * "Wallet" (Read only)
  * "Account" (Read only)
- Incomplete permissions will prevent bot functionality
- Recommended: Select permissions matching your intended trading market

#### Bybit API Setup
Futures trading on Bybit demands precise API configurations:
- API Key Permissions:
  * Read-write access
  * Contract - Orders
  * Contract - Positions
- Security Recommendations:
  * Limit API keys to specific IP addresses
  * Use dedicated subaccounts for each bot
  * Avoid mixing manual and bot trading on the same account

#### BitMart API Requirements
BitMart has unique API key configuration needs:
- API Key Components:
  * Requires API key, secret, and UID (Memo)
  * Place the Memo in the API key field
- Trading Verification:
  * Level 2 verification mandatory for spot market API trading
  * Level 1 verification insufficient for API trades

!!! warning "Important"
    Carefully review and follow these exchange-specific guidelines to ensure smooth bot operation and prevent potential trading interruptions.

## Step 5: Create Your First Bot

The final step is creating your first trading bot:

1. Navigate to the bot creation interface
2. Choose a trading strategy from the repository
3. Configure basic settings:
      - Trading pair
      - Investment amount
      - Risk parameters
4. Name your bot
5. Launch the bot

## Next Steps

After completing the setup process, we recommend:

1. Starting with paper trading to test your strategies risk-free
2. Reviewing the bot's performance metrics
3. Adjusting parameters as needed
4. Joining our [Discord community](https://discord.gg/aBhW5Sbk) for support and tips

## Need Help?

If you encounter any issues during the setup process:

- Check our [FAQ section](/faq)
- Contact our [support team](mailto:support@coincruze.com)
- Join our [Discord community](https://discord.gg/aBhW5Sbk) for real-time assistance

Remember: Trading cryptocurrencies involves risk. Start with small amounts and thoroughly test your strategies before committing significant capital.
