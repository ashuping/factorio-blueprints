# Factorio Blueprints
Various blueprints that I use in Factorio. Feel free to use them for whatever.

## Glossary
These abbreviations are used to remove ambiguity.

- **S.D. or sd:** Schematic Direction. These directions are relative to the blueprint, in the default orientation.
- **B.D. or bd:** Belt Direction. These directions are relative to the direction of transit of a belt. If a belt is traveling downward relative to the blueprint, "left bd" would be the same as "right sd"

## Belt I/O key

| Syntax             | Meaning                                                 |
|--------------------|---------------------------------------------------------|
| ITEM               | Belt containing ITEM                                    |
| {Item A | Item B}  | Belt containing Item A on the left and Item B on the right, in the direction of travel. Inputs cannot be switched. |
| {Item A || Item B} | Belt containing Item A and Item B. Either side of the belt is fine for either item. |
| Nothing            | Belt (or belt side) is empty.                           |
