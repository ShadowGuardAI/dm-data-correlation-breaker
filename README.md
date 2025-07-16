# dm-data-correlation-breaker
Identifies and removes subtle correlations between seemingly unrelated data points that could lead to re-identification of masked data. It focuses on finding and breaking these hidden links, for example, by injecting carefully chosen errors or variations. - Focused on Tools designed to generate or mask sensitive data with realistic-looking but meaningless values

## Install
`git clone https://github.com/ShadowGuardAI/dm-data-correlation-breaker`

## Usage
`./dm-data-correlation-breaker [params]`

## Parameters
- `-h`: Show help message and exit
- `--input`: Path to the input CSV file.
- `--columns`: Comma-separated list of column names to process.
- `--error-rate`: No description provided
- `--output`: Path to the output CSV file. Default: output.csv
- `--seed`: Seed for the random number generator to ensure reproducibility.

## License
Copyright (c) ShadowGuardAI
