![Banner](banner.png)

# dm-data-schema-randomizer
Randomly renames, reorders, and changes the data types of columns in a dataset to obfuscate its structure. Preserves data integrity within constraints to maintain usability while scrambling the schema. - Focused on Tools designed to generate or mask sensitive data with realistic-looking but meaningless values

## Install
`git clone https://github.com/ShadowGuardAI/dm-data-schema-randomizer`

## Usage
`./dm-data-schema-randomizer [params]`

## Parameters
- `-h`: Show help message and exit
- `--seed`: Random seed for reproducibility.

The output file must not be the input file. A run that names the same file for both, in any spelling that resolves to the same path, is refused at exit 1 before any write.

## License
Copyright (c) ShadowGuardAI
