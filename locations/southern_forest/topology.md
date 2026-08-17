# Southern Forest — Topological Map

This is a connectivity diagram, not a scale map. The road lies north; wet ground and Blight Swamp deepen toward the south and east.

```text
                         ROAD / EXIT
                              |
                    [01 Southern Road Verge]
                       /                \
       [12 Caravan Turnout]       [02 Forking Track]
          /          \             /       |       \
 [13 Sentry Blind]--[14 Hunting]---+      [03]----[04]
       |      \        |                  Fisher   Maren
       |      [16 Transfer Bank]          Path     Marker
       |        /    |      \                \      / \
       |     [17]  [15 Broken]-------------[10]  [05 Boundary]
       |   Aldric    Undead                  |       /       \
       |    Camp       |                   [11]   [06 Pool]--[09 Lagoon]
       |               |                   Web       |       /   |
       +---------------+----[18 Old River Ford]------+-[07]----[08]
                                  |                    Causeway  Mound
                           SWAMP / RIVER
```

## Adjacency list

| Area | Direct links |
|---|---|
| 01 | 02, 12, road/exit |
| 02 | 01, 03, 10, 13, 14 |
| 03 | 02, 04, 09 |
| 04 | 03, 05, 10 |
| 05 | 04, 06, 09 |
| 06 | 05, 07, 18 |
| 07 | 06, 08, 09 |
| 08 | 07, 09 |
| 09 | 03, 05, 07, 08, 18 |
| 10 | 02, 04, 11, 15 |
| 11 | 10, 18 |
| 12 | 01, 13, 14 |
| 13 | 02, 12, 14, 16 |
| 14 | 02, 12, 13, 15, 17 |
| 15 | 10, 14, 16, 18 |
| 16 | 13, 15, 17, 18 |
| 17 | 14, 16 |
| 18 | 06, 09, 11, 15, 16, swamp/river |

The party can always withdraw to the road. Only use the listed links when the exact approach matters—for a sentry, ambush, territorial boundary, or pursuit.

