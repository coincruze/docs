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

Selecting the right subscription plan is crucial to unlocking Coincruze's AI-powered trading platform. Our plans are designed to accommodate different trading needs, experience levels, and investment goals.

Key considerations when choosing a plan:

- Number of bots you want to run
- Exchanges you'll be trading on
- Complexity of trading strategies

An active subscription is essential to access platform features, including:

- Creating and running trading bots
- Connecting exchanges
- Leveraging AI optimization tools

!!! tip "Cost-Saving Tip"
    Annual plans offer significant discounts, providing a cost-effective way to maximize your trading potential.

Visit our [Pricing](https://coincruze.com/pricing) page to explore current plans and find the best fit for your trading objectives.

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

Carefully review and follow these exchange-specific guidelines to ensure smooth bot operation and prevent potential trading interruptions.

#### Binance

When setting up Binance, users must be aware of several critical configurations.

**Select the correct Binance platform:**

- International users: Binance
- US-based users: Binance.US

**Futures Trading Requirements:**

- Binance has [complex futures quantitative trading rules](https://www.binance.com/en/support/faq/binance-futures-trading-quantitative-rules-4f462ebe6ff445d4a170be7d9e897272)
- Minimum stake amounts apply to prevent trading restrictions
- Mandatory settings:
    - Position Mode: Set to "One-way Mode"
    - Asset Mode: Set to "Single-Asset Mode"

!!! warning
    Failure to configure these settings will prevent bot activation

#### OKX

OKX requires an additional security step:

- Each API key must include a unique passphrase
- Ensure the passphrase is correctly entered into the `password` field during exchange configuration

#### Gate.io

Specific API key permissions on top of the market you want to trade are crucial for Gate.io:

- Required Permissions:
    * "Spot Trade" or "Perpetual Futures" (Read and Write) (either select both, or the one matching the market you want to trade)
    * "Wallet" (Read only)
    * "Account" (Read only)

!!! warning
    Incomplete permissions will prevent bot functionality

#### Bybit

Futures trading on Bybit demands precise API configurations:

- API Key Permissions:
    * Read-write access
    * Contract - Orders
    * Contract - Positions

!!! danger
    Coincruze operates under the assumption that each account is exclusively allocated to a single bot. Therefore, we advise assigning a separate subaccount for each bot, particularly when dealing with unified accounts.

!!! warning
    Alternative setups — such as running multiple bots on a single account or executing manual (non-bot) trades within a bot-operated account — are not supported and could result in unpredictable behavior.

#### BitMart

Bitmart mandates that the API key Memo (the label assigned to the API key) be provided alongside the exchange key and secret.
Enter the memo into `Api key` field.

Additionally, Bitmart requires Verification Level 2 to trade on the spot market via the API.

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

- Check our [FAQ section](./faq.md)
- Contact our [support team](mailto:support@coincruze.com)
- Join our [Discord community](https://discord.gg/aBhW5Sbk) for real-time assistance

Remember: Trading cryptocurrencies involves risk. Start with small amounts and thoroughly test your strategies before committing significant capital.
