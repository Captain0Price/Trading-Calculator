# Trading-Calculator
Trading Calculator is a simple yet powerful Google Sheets tool designed to simulate and evaluate the outcomes of multiple trades based on user-defined parameters. Whether you're backtesting a trading strategy or estimating potential outcomes, this calculator gives you a realistic overview of how your capital could perform under different market conditions.

![Image](https://github.com/user-attachments/assets/341bcffa-f26e-4543-879b-c8313494b10c)

# 🔧 Features

## Accepts key inputs such as:

Initial Capital

Number of Trades

Win Rate (%)

Leverage

Profit Percentage per Winning Trade

Stop Loss Percentage per Losing Trade

## Outputs include:

Number of Winning Trades

Number of Losing Trades

Total Gross Profit

Total Gross Loss

Net Profit / Loss

Total Commission (based on Binance rates)

Final (Closing) Capital


# 📈 Example

## Inputs:

Initial Capital: $500

Number of Trades: 10

Win Rate: 40%

Leverage: 3x

Profit Percentage (per win): 2%

Stop Loss Percentage (per loss): 1%

## Outputs:

Winning Trades: 4

Losing Trades: 6

Gross Profit: $115.51

Gross Loss: $93.03

Net Profit: $22.47

Commission: $12.68

Closing Capital: $522.47

![Image](https://github.com/user-attachments/assets/a1a1f1bb-eb7a-44d3-85dd-38e56af7877e)

# 🔢 How It Works
1) You input the capital, trading parameters, and assumptions.

2) The sheet randomly assigns winning and losing trades based on your win rate.

3) It calculates:

    Profit and loss using leverage

    Commission on both buy and sell (as per Binance trading fees)

4) The result gives you a clear picture of your strategy's potential impact on your capital.

![Image](https://github.com/user-attachments/assets/c6265da8-8efe-402e-bfe5-5e16d8f094d4)

## 📌 Notes
The randomness in win/loss assignment helps simulate the uncertainty in real trading environments.

Commission rates are based on Binance's spot trading fee structure and can be updated if needed.

Designed primarily for educational and strategy testing purposes.

## 🧮 Ideal For
-Aspiring traders testing win/loss scenarios

-Strategy backtesting with different risk-reward setups

-Educators or mentors demonstrating trading outcomes

-Anyone looking to better understand the math behind trading
