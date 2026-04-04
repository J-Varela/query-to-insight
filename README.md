# query-to-insight

An AI-powered analytics assistant that converts business questions into validated SQL queries and returns trustworthy visual insights.

## Overview

`query-to-insight` bridges the gap between natural language business questions and actionable data insights. Users describe what they want to know in plain English; the system generates SQL, validates it, executes it, and returns clear visual results.

## Features

- Natural language to SQL conversion
- SQL validation and safety checks
- Query execution against connected data sources
- Visual insight generation from query results

## Getting Started

### Prerequisites

- Python 3.10+
- A compatible SQL database (PostgreSQL, MySQL, SQLite, etc.)

### Installation

```bash
git clone https://github.com/YOUR_USERNAME/query-to-insight.git
cd query-to-insight
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

### Configuration

Copy the example config and fill in your credentials:

```bash
cp config.example.yaml config.yaml
```

### Usage

```python
# Example usage (placeholder — update as the project develops)
from query_to_insight import QueryToInsight

agent = QueryToInsight(config="config.yaml")
result = agent.ask("What were our top 10 customers by revenue last quarter?")
result.show()
```

## Project Structure

```
query-to-insight/
├── query_to_insight/   # Core package
├── tests/              # Test suite
├── requirements.txt    # Dependencies
└── README.md
```

## Contributing

Pull requests are welcome. Please open an issue first to discuss significant changes.

## License

[MIT](LICENSE)
