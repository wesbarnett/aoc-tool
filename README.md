# aoc-tool

## Installation

```bash
python3 -m pip install git+https://github.com/wesbarnett/aoc-tool
```

## Usage

```python
from aoc import get_input, submit

if __name__ == "__main__":
    year, day, level = 2022, 10, 1
    aoc_input = get_input(year, day)

    # Do some calculations
    # ans = <calculations>

    submit(ans, year, day, level)
```
