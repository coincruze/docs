# Creating a Bot in Coincruze

In Coincruze, you can easily create and manage trading bots. Follow this guide to create a bot, configure its settings, and run it in Paper Trading or Live mode.

## Step 1: Copy a Bot from the Repository

1. Navigate to the [Repository](https://coincruze.com/bot-repository) page.
2. Browse the available bots. Each bot card displays key metrics such as:
	-	Profit/Loss
	-	Duration
	-	Timeframe
	-	Win Rate
3. Choose bot that best fits your risk profile and trading style (frequency, timeframe, etc.)
4. Click the “Copy” button on the bot you want to create.

!!! note
	After clicking “Copy”, the bot will be created and after a few moments will be ready for trading.

## Step 2: View the Bot Details

After creating your bot, you'll be taken to the Bot Details page - your central command center for monitoring and managing your trading bot. This comprehensive dashboard will be where you track your bot's performance once it starts trading. Initially, most metrics will show zero or empty values since the bot hasn't started trading yet.

The Bot Details page will help you monitor:

**Performance Metrics**

- Total Profit: Track your future profits and losses
- Win Rate: Monitor the success rate of your bot's trades
- Max Drawdown: Keep an eye on maximum potential losses
- Average Trade Duration: Understand your bot's trading frequency
- Total Trades: Follow the number of completed trades
- Open Trades: Watch active positions in real-time

**Advanced Statistics**

- Duration: Track how long your bot has been running
- Profit %: Monitor overall return on investment
- Profit Factor: Evaluate the ratio of winning to losing trades
- Long/Short Trade Distribution: Analyze trading direction balance
- CAGR %: Measure annual growth rate
- Sharpe Ratio: Assess risk-adjusted returns
- Calmar Ratio: Evaluate risk-adjusted performance

**Trading History**

- Access daily, weekly, and monthly performance summaries
- Review detailed trade logs once trading begins
- Track trade reasons and outcomes
- Monitor stake amounts and individual trade results

!!! tip
    Once your bot starts trading, regularly review these metrics to evaluate its performance and make necessary adjustments to your trading strategy.

## Step 3: Configure Bot Settings

The Edit Bot page is where you'll customize your bot's trading behavior and risk management settings. Each bot comes with pre-configured parameters optimized by our AI, but you can
adjust these settings to match your trading preferences and risk tolerance.

### Basic Configuration

**Bot Name**

- Give your bot a unique, descriptive name to easily identify it among your other bots
- Example: "High Volatility BTC-ETH" or "Conservative USDT Swing Trader"

**Crypto Exchange Connection**

- Select from your previously connected exchanges
- If you haven't connected an exchange yet, you'll need to set one up in Account Settings first
- Required for live trading mode, not needed for paper trading

### Bot Parameters

**General Settings** (Available for all bots)

- Available Capital: Define how much capital the bot can use (10 - 1,000,000)
- Stake Currency: Select the base currency for trading (e.g., USDT, BUSD)
- Max Open Trades: Set the maximum number of simultaneous positions (1 - 100)
- Timeframe: Choose the trading interval (e.g., 5m, 15m, 30m, 1h)
- Trading Pairs: Select which cryptocurrency pairs to trade

**Specialized Parameters** (Vary by bot type)

Different bots will have additional parameter sections based on their strategy:

- Stop Loss: Configure loss prevention settings
- ROI: Define take-profit targets
- Buy/Sell: Set entry and exit conditions
- Protections: Add trading safeguards
- Other strategy-specific parameters

!!! note
    Each parameter section contains tooltips explaining its purpose and recommended ranges. Hover over the (?) icon next to each setting for detailed information.

!!! tip
    Start with the default parameters while paper trading. Make gradual adjustments based on performance data rather than making multiple changes at once.

## Step 4: Run the Bot in Paper Trading Mode

Before trading with real money, it’s recommended to run the bot in Paper Trading mode:

1. From the Bot Details page, click “Start”.
2. Ensure the bot’s status changes to “running”.
3. Monitor the bot’s performance and analyze the trades in the Closed Trades section.

## Step 5: Switch to Live Mode

Once you are satisfied with the bot’s performance in Paper Trading mode, you can switch to Live mode:

1. Ensure you have connected your exchange credentials in the Edit Bot page.
2. Click “Connect Exchange to Go Live” on the Bot Details page.
3. Start the bot and let it trade with real funds.

## Managing Your Bot

- Start/Stop: Control the bot’s trading activity.
- Restart: If the bot encounters an issue and enters the “failing” status, restart it to resume trading.
- Edit Settings: Modify parameters at any time through the Edit Bot page.

## Bot Lifecycle and Statuses

After creating a bot, it will go through several statuses during its lifecycle:

- preparing: The bot is being set up on your trading server.
- ready: The bot is ready to be started.
- starting: The bot is in the process of starting.
- running: The bot is actively trading.
- stopping: The bot is in the process of stopping.
- stopped: The bot has stopped trading.
- failing: The bot has encountered an issue.

You can manage the bot by starting, stopping, or restarting it if it fails.

## Summary

- Copy a bot from the Repository.
- Configure settings on the Edit Bot page.
- Test in Paper Trading mode first.
- Switch to Live mode when ready.

With Coincruze, managing your trading bots is seamless and flexible. Happy trading! 🚀
