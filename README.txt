ALPHA XP SCANNER â€” STARTER DEPLOYMENT

Included:
- index.html: responsive live market scanner prototype.
- This prototype reads public Deriv tick data and produces rule-based BUY/SELL/WAIT signals.
- It does not execute trades, does not require a trading token, and does not guarantee an 85% win rate.

Run locally:
1. Extract the ZIP.
2. Open index.html in a modern browser with internet access.
3. Press "Connect live data".
4. If the default app ID fails, register a Deriv application and enter its app ID.

Deploy free with GitHub Pages:
1. Create a new GitHub repository.
2. Upload index.html to the repository root.
3. Open repository Settings â†’ Pages.
4. Choose deployment from the main branch and root folder, then Save.
5. Open the published Pages URL.

Important limitations:
- The strategy is a simple EMA + RSI rule, not a trained AI model.
- SL/TP distances are heuristic estimates based on recent tick movement, not broker-calculated guarantees.
- Tick-based signals are not a substitute for candle-based backtesting, slippage/spread modelling, or demo validation.
- Never enter a Deriv password or API token into this static prototype.
- Do not use it to place live trades without independent testing and suitable risk controls.
