# Black Bot ReadMe

Black Bot is a forex trading robot developed by the Forex Robot Easy Team. It is designed to trade the EURUSD currency pair on the M15 timeframe. This ReadMe provides an overview of the code and explains how the bot works.

## Input Parameters

- Aggressiveness: This parameter represents the aggressiveness of the bot and is defined as a percentage value.
- RiskPercentage: This parameter determines the percentage of the account balance to risk per trading cycle.

## Minimum Deposit and Leverage Ratio Requirements

To use Black Bot, the account must meet the following requirements:

- MinimumDeposit: The minimum deposit required to use Black Bot is 100 units.
- LeverageRatio: The leverage ratio required for trading is set to 200.

## Black Bot Core Functions

### OnInit()

This function is called when the bot is initialized. It checks if the account meets the minimum deposit and leverage ratio requirements. If the requirements are not met, an error message is displayed.

### OnTick()

This function is called on every tick and contains the trading logic for the bot. It implements the trading strategy for the EURUSD currency pair on the M15 timeframe. It also calculates the lot size based on the risk percentage and account balance. If a buy or sell signal is generated, a trade is opened using the OrderSend function.

### BuySignal()

This function checks for a buy signal based on the implemented buy signal logic.

### SellSignal()

This function checks for a sell signal based on the implemented sell signal logic.

## Black Bot Interface and Execution

### OnStart()

This is the main function of the bot. It calls the OnInit function to initialize the bot. If the initialization is successful, the bot's trading logic is executed on every tick using a while loop. The Sleep function is used to introduce a delay of 1 second between each tick.

## Product Description

Black Bot is an easy-to-use forex trading software developed by Forex Robot Easy Team. It is specifically designed to trade the EURUSD currency pair on the M15 timeframe. With its aggressive trading strategy and risk management features, Black Bot aims to provide consistent profits for traders.

To use Black Bot, the account must meet the minimum deposit requirement of 100 units and have a leverage ratio of 200. This ensures that the bot operates within the specified risk parameters.

Please note that ForexRobotEasy is not the official developer of Black Bot. We are showcasing the sample code that can work as described in the product. To find the official developer of this product, please refer to the MQL5 platform.

For detailed reviews and trading results of Black Bot, please visit [ForexRobotEasy](https://forexroboteasy.com/forex-robot-review/review-black-bot-easy-to-use-forex-software-for-eurusd-m15/).
