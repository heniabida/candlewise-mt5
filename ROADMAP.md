# Roadmap

What is coming to CandlePattern Lite and Pro. Items are grouped by status, not by date; there are no release dates until a version is ready.

Statuses:

- **In testing**: built and being tested; ships in an upcoming update.
- **Planned**: accepted and scheduled after the items in testing.
- **Exploring**: being researched; may change or be dropped.

Each item has a PFR number. When an item comes from a feature request, its issue number is added next to it.

## In testing

### Alerts

| PFR | Feature | Edition | Why |
|---|---|---|---|
| [PFR-001](../../issues/1) | Sound alerts with a different sound for bullish and bearish patterns | Pro | Traders ask for an audible warning when a pattern appears. |
| [PFR-002](../../issues/2) | Real-time alerts: alert as soon as a pattern forms on the open candle, clearly marked "may change before close", then again when the candle closes | Pro | Traders ask for real-time alerts so they don't miss a move. |
| [PFR-003](../../issues/3) | Alert switch for each pattern, set from the Library tab | Pro | Get alerts only for the patterns you trade. |
| [PFR-004](../../issues/4) | One-click mute button on the toolbar | Pro | Silence alerts during news or while away. |
| [PFR-005](../../issues/5) | Optional second alert when a pattern is confirmed by a later candle | Pro | Act on confirmed patterns only. |

### Signal quality filters

| PFR | Feature | Edition | Why |
|---|---|---|---|
| [PFR-010](../../issues/6) | Minimum pattern size, as a multiple of ATR | Pro | Ignore tiny patterns in quiet markets. |
| [PFR-011](../../issues/7) | Minimum tick volume, as a multiple of the 20-bar average | Pro | Ignore patterns with little activity behind them. |
| [PFR-012](../../issues/8) | Trend filter with an EMA: classic mode (reversals against the trend) or trend-following mode | Pro | Fewer patterns that fight the trend. |
| [PFR-013](../../issues/9) | Reversals only at a swing high or low | Pro | Keep reversal patterns where they matter most. |
| [PFR-014](../../issues/10) | Hide repeated reversals in the same direction within a few bars | Pro | A cleaner chart when several reversals stack up. |

### Chart and display

| PFR | Feature | Edition | Why |
|---|---|---|---|
| [PFR-020](../../issues/11) | Marker style: zones, arrows, or both | Pro | Some traders prefer classic arrows. |
| [PFR-021](../../issues/12) | Custom bullish, bearish and indecision colours | Pro | Match your own chart colours. |
| [PFR-022](../../issues/13) | Short lesson for every pattern on the pattern card | Pro | Learn what each pattern means without leaving the chart. |
| [PFR-023](../../issues/14) | Toolbar choices remembered when you change symbol or timeframe | Pro | No need to set filters again on every switch. |

## Planned

| PFR | Feature | Edition | Why |
|---|---|---|---|
| [PFR-030](../../issues/15) | Telegram alerts through a small companion Expert Advisor | Pro | MetaTrader does not let indicators send web requests, so a companion EA will deliver alerts to Telegram. |
| [PFR-031](../../issues/16) | Guide and sample Expert Advisor for reading the indicator values with `iCustom` | Pro | Use the patterns in your own automated strategy. |

## Exploring

| PFR | Feature | Edition | Why |
|---|---|---|---|
| [PFR-040](../../issues/17) | Filter or highlight patterns that form at support and resistance zones | Pro | Patterns at key levels get more attention from traders. |
| [PFR-041](../../issues/18) | A simple popup alert in Lite | Lite | Requested by users of free candlestick indicators. |

## Shipped

See [CHANGELOG.md](CHANGELOG.md).

## Suggest something

Open a [Product feature request](../../issues/new/choose). Requests are reviewed and, when accepted, added here with their issue number.
