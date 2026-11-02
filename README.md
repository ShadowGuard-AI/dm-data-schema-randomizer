![Introduction banner: one broom badge hanging on its peg at the turning point of a stone hall, moon gates and beaded amber drops behind it, woven cloaks on pegs, lanterns still lit, acorns resting by the door, no lettering anywhere](intro-banner.png)

# dm-data-schema-randomizer

Chapter opening, steward first: the name above is set in Cantata One in troll bridge grey, with a small ring beside this title block and the broom badge drawn once as a header plate under the banner. Later headings keep the chapter dress, minus that plate.

![Logo](logo.png)

![Banner](banner.png)

![Animated scene: three bands. Far band, moon gates standing with one hinged leaf swinging in the draught. Middle band, woven cloaks still on the peg wall while carried lantern light travels across them. Near band, the badge swaying a finger's width on its peg, acorns resting where they fell](scene.svg)

![Major separator: an iron key turning in an unseen lock](sep-heavy.svg)

# dm-data-schema-randomizer
Randomly renames, reorders, and changes the data types of columns in a dataset to obfuscate its structure. Preserves data integrity within constraints to maintain usability while scrambling the schema. - Focused on Tools designed to generate or mask sensitive data with realistic-looking but meaningless values

![Major separator: an iron key turning in an unseen lock](sep-heavy.svg)

## Install
`git clone https://github.com/ShadowGuardAI/dm-data-schema-randomizer`

> Storybook aside: the README clone line spells the organisation without its hyphen.

![Minor separator: a short centred line with a small iron key](sep-light.svg)

## Usage
`./dm-data-schema-randomizer [params]`

![Minor separator: a short centred line with a small iron key](sep-light.svg)

## Parameters
- `-h`: Show help message and exit
- `--seed`: Random seed for reproducibility.

The output file must not be the input file. A run that names the same file for both, in any spelling that resolves to the same path, is refused at exit 1 before any write.

> Storybook aside: output must not be the input file.

> Storybook aside: any spelling resolving to the same path is still the same file.

> Storybook aside: a matching run is refused at exit 1 before any write.

![Minor separator: a short centred line with a small iron key](sep-light.svg)

## License
Copyright (c) ShadowGuardAI

![Major separator: an iron key turning in an unseen lock](sep-heavy.svg)

## After the flood, the minutes

The main button of this re-skin reads Scramble the Schema. Its seed field label reads Union Seed. Its guard heading reads Output Is Never the Input. Its agenda heading reads Controls, All Two of Them. It ends with the badge back on its peg on the last page, the spell kept, the hall at rest, and the brooms drying by the wall.
