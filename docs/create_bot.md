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

Once the bot is created, you will be redirected to the Bot Details page. Here you can:

- Manage the bot (start/stop/update/delete)
- Check bot performance statistics like Total Profit, Win Rate, and Max Drawdown.
- See the list of Open Trades and Closed Trades.
- Access advanced metrics such as CAGR, Sharpe Ratio, and more.

## Step 3: Edit Bot Settings

1. Click the “Edit” button on the Bot Details page to access the Edit Bot page.
2. Configure the following parameters:

General Parameters

- Name: Set a name for your bot.
- Crypto Exchange: Assign exchange credentials (required for Live mode).
- Available Capital: Define the capital allocation (Min: 10, Max: 1,000,000).
- Stake Currency: Choose the currency for trading (e.g., USDT).
- Max Open Trades: Limit the number of simultaneous trades (Min: 1, Max: 100).
- Timeframe: Select the trading timeframe (e.g., 5m, 15m).

Pairs to Trade

Select the trading pairs the bot will use (e.g., BTC/USDT, ETH/USDT, SOL/USDT).

Tip: Choose pairs based on your trading strategy and market analysis.

Paper Trading Wallet

Set the amount for paper trading (Min: 10, Max: 1,000,000).

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
