# portfolio-analytics

A Python-based portfolio analytics engine covering returns, risk, and factor analysis. Built to explore how quantitative finance concepts translate into working code.

## Features

- Returns: total, periodic, and cumulative return calculations
- Risk: volatility, drawdown, and other risk measures
- Factor analysis: decomposing performance into underlying drivers

<!-- TODO: Trim or expand this list so it matches exactly what the code in /src does. -->

## Tech stack

Python, pandas, NumPy

## Getting started

```bash
git clone https://github.com/ZaahidT14/portfolio-analytics.git
cd portfolio-analytics

python -m venv venv
source venv/bin/activate      # Windows: venv\Scripts\activate

pip install -r requirements.txt
```

## Usage

```python
# Example, adjust to match the modules in /src
from src.analytics import compute_returns

returns = compute_returns(prices)
print(returns)
```

<!-- TODO: Replace with a real example using your actual module and function names. -->

## Project structure

```
portfolio-analytics/
  src/                 Core analytics code
  requirements.txt     Dependencies
  README.md
```

## Roadmap

- Add unit tests
- Add example notebook with sample data
- Document each module's API

## License

<!-- TODO: Add a LICENSE file (MIT is a good default for portfolio projects). -->
