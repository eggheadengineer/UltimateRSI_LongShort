Simplified Long/Short Arrows with Ultimate RSI by LuxAlgo

This is a Pine Script indicator designed for TradingView that uses a simplified approach to indicate long and short signals using moving averages and an enhanced version of the Relative Strength Index (RSI) called Ultimate RSI. This script is built to identify potential trading opportunities by showing green arrows for long (buy) signals and red arrows for short (sell) signals.

Features

Long/Short Indicators: Green arrows indicate long signals, while red arrows indicate short signals, providing a visual cue for trading opportunities.

Ultimate RSI by LuxAlgo: Uses the advanced RSI calculation, taking into account both overbought and oversold conditions.

Customizable Moving Averages: Users can set the fast and slow moving average lengths to customize the trading strategy.

Alert Notifications: Alert conditions for both long and short signals, allowing traders to receive notifications when trading opportunities arise.

Inputs and Customization

Moving Average Settings

Fast Moving Average Length: (Default = 9) The length of the fast moving average.

Slow Moving Average Length: (Default = 21) The length of the slow moving average.

Ultimate RSI Settings

RSI Length: (Default = 14) Period length for calculating the RSI.

Smoothing Type 1: Select the type of moving average for RSI calculation. Options include EMA, SMA, RMA, TMA.

Source: (Default = Close) The price source used in the calculation (e.g., close price).

Signal Line Smoothing: (Default = 14) The smoothing length for the signal line.

Smoothing Type 2: Moving average type for the signal line (Options: EMA, SMA, RMA, TMA).

Overbought Level: (Default = 70) The threshold level for overbought conditions.

Oversold Level: (Default = 30) The threshold level for oversold conditions.

Logic Behind the Signals

Long Condition

A long signal (green arrow below the price bar) is generated when:

The fast moving average crosses over the slow moving average.

The Ultimate RSI is below the oversold level (indicating a potential buying opportunity).

The signal line of the Ultimate RSI is also below the oversold level.

Short Condition

A short signal (red arrow above the price bar) is generated when:

The fast moving average crosses under the slow moving average.

The Ultimate RSI is above the overbought level (indicating a potential selling opportunity).

The signal line of the Ultimate RSI is also above the overbought level.

Alerts

Long Alert: Sends an alert notification when a long condition is met, suggesting a buy action.

Short Alert: Sends an alert notification when a short condition is met, suggesting a sell action.

How to Use

Add the indicator to your chart in TradingView.

Adjust the input parameters for moving averages, RSI settings, and smoothing to suit your trading strategy.

Observe the arrows (green for long, red for short) for trading signals.

Set alerts to receive notifications when a trading signal is generated.

Disclaimer

This indicator is a tool that aims to help traders identify potential trading opportunities. It is important to note that no trading strategy guarantees success, and traders should always perform their own research and consider risks when making trading decisions. This script is provided for educational purposes and should not be considered financial advice.

License

This script is provided as-is under an open-source license. You are free to use and modify it as needed.

