# Bitcoin Checker

## Description
This project generates a set of passwords that are then used to derive Bitcoin private and public keys. The generated Bitcoin addresses are then compared against a dataset of the top 1 million richest Bitcoin wallets. If any generated address matches an entry in the dataset, it is recorded.

## Features
- Generates potential Bitcoin wallet passwords based on various algorithms.
- Uses the generated passwords to create Bitcoin private and public keys.
- Supports multiple Bitcoin address formats (Legacy, SegWit, Taproot, etc.).
- Checks generated addresses against the richest Bitcoin wallet dataset as of 2024.
- High-performance execution with profiling support.

## Installation
To set up and run the project, install the required dependencies:
```sh
pip install -r requirements.txt
```

## License
This project is licensed under the MIT License.

## Contact
For questions, reach out via GitHub Issues or email at `codalata@gmail.com`.
