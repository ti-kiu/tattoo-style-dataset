# Tattoo Style Dataset

A free, curated dataset of 20 tattoo styles with descriptions, keywords, design counts, and placement recommendations. Generated from 480+ AI-designed tattoo references.

## What's Included

- `styles.csv` — 20 tattoo styles with descriptions, keywords, and design counts
- `placements.csv` — 8 body placement zones with style recommendations

## Quick Start

```python
import pandas as pd
styles = pd.read_csv("styles.csv")
print(styles[["style", "keywords", "design_count"]])
```

## Source

This dataset is derived from [InkPreview](https://inkpreview.co/tattoo-ideas), an AI tattoo simulator that generates realistic tattoo previews across 20 styles and 8 body zones.

## License

CC0 1.0 Universal — Public Domain. Use freely for research, design, or AI training.
