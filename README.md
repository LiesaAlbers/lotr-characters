## About the Dataset

This data explores the characters from the *The Lord of the Rings* series.

### Provenance

The dataset was retreived from [this Github repository](https://github.com/gordon-dsc/wot-data/tree/main), contributed to by users *Dean-Tengdin* and *dwcmcdonough*. The original data was gathered from https://the-one-api.dev/v2 API.

### Data Contents
- **Rows:** each row contains data on a single character from the series.
- **Columns** (variables):

  | Header | Description |
  | ------ | ----------- |
  | `name` | Full name of the character |
  | `height_in` | Height of each character measured in total inches |
  | `gender` | The stated gender of the character as shown in the films |
  | `birth_year` | The year in which the character was born |
  | `birth_age` | The historical Age the character was born in [^1] |
  | `death_year` | The year in which the character died |
  | `death_age` | The historical Age the character died in [^1] |
  | `years_alive` | The number of years a character was alive for if both year of `birth_year` and `death_year` are given [^2] |
  | `hair` | The colour or shade of a character's hair as described in the film adaptations [^3] |
  | `series` | The series which the character appears in |

[^1]: These are given in shorthand (FA = First Age, SA = Second Age, TA = Third Age, FO = Fourth Age, YT = Years of the Trees, AB = After Breaking, FY = Free Years, NE = New Era).
[^2]: If the character was still alive by the end of the series they recieved an NA for this variable.
[^3]: Characters with multiple conflicting descriptions were given the value described first and characters with the descriptive words Dark or Light before a color were assinged to only the color (ex. DARK RED changed to just RED).
  
