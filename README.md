Sementic IPA input method v0.0.5

# Basic Idea
Semanticize IPA input method.

# How to

## For pulmonic consonants

`(place)(manner)[voiced?]`

| Argument | Type | Content |
| -------- |:-----:| ------- |
| place    | Required | Place of articulation. See [the table](#place) below. |
| manner   | Required | Manner of articulation. See [the table](#manner) below. |
| voiced?  | Optional  | Decide if it is a voiced plosive/fricative/affricate. |

### For example

1. `ap` = `a` + `p` = Alveolar + Plosive = Voiceless alveolar plosive
2. `vl` = `v` + `l` = Velar + Lateral approximent = Voiced velar lateral approximant
3. `alfv` = `a` + `lf` + `v` = Alveolar + Lateral fricative + Voiced = Voiced alveolar lateral fricative

## For vowels

`(backness)(height)[rounded?]`

| Argument | Type | Content |
| -------- |:-----:| ------- |
| backness | Required | Backness of vowel. See [the table](#backness) below. |
| height   | Required | Height of vowel. See [the table](#height) below. |
| rounded?  | Optional  | Decide if it is a rounded vowel. |

## For diacritics

### For subscripts
If a subscript diacritic is a normal symbol in the IPA chart, it would be `^{SIPA of the symbol}`, e.g, "tʰ" = `ap^gf`.

### For other diacritics
See [the table](#special) below.

# Tables

## <span id="place">Place of Articulation</span>

| Place | Code |
| ----- | ---- |
| Bilabial | `b` |
| Labiodental | `l` |
| Dental | `d` |
| Alveolar | `a` |
| Postalveolar | `o` |
| Retroflex | `r` |
| Palatal | `p` |
| Velar | `v` |
| Uvular | `u` |
| Pharyngeal | `h` |
| Glottal | `g` |
| Bilabial-labiodental | `l` |
| Labial-velar | `lv` |
| Labial-palatal | `lp` |
| Epiglottal | `e` |
| Alveolo-palatal | `ap` |
| Linguolabial | `ll` |


## <span id="manner">Manner of Articulation</span>

| Manner | Code |
| ----- | ---- |
| Plosive | `p` |
| Nasal | `n` |
| Trill | `r` |
| Tap or Flap | `t` |
| Fricative | `f` |
| Lateral fricative | `lf` |
| Approximent | `a` |
| Lateral approximent | `l` |
| Affricate | `af` |
| Lateral flap | `lt` |

## <span id="backness">Backness of Vowel</span>

| Backness | Code |
| ----- | ---- |
| Front | `f` |
| Near-front | `f` |
| Central | `c` |
| Near-back | `b` |
| Back | `b` |

## <span id="height">Height of Vowel</span>

| Backness | Code |
| ----- | ---- |
| Close | `c` |
| Near-close | `c'` |
| Close-mid | `cm` |
| Mid | `m` |
| Open-mid | `om` |
| Near-open | `o'` |
| Open | `o` |

## <span id="special">Special</span>

| Symbol | Name | Code |
| ------ | ---- | ---- |
| ◌̚  | No audible release (Applosive) | `^app` |
| ◌̥  | Voiceless | `v-` |
| ◌̬ | Voiced | `v+` |
| ◌̹ | More rounded | `r+` |
| ◌̜ | Less rounded | `r-` |
| ◌̟ | Advanced (Fronted) | `f+` |
| ◌̠ | Retracted (Backed) | `f-` |
| ◌̈ | Centralized | `c+` |
| ◌̽ | Mid-centralized | `mc+` |
| ◌̩ | Syllabic | `s+` |
| ◌̯ | Non-syllabic | `s-` |
| ◌˞ | Rhoticity | `+r` |
| ◌̤ | Breathy voiced | `^gfv` |
| ◌̰ | Creaky voiced | `cv+` |
| ◌̼ | Linguolabial | (-) |
| ◌̴ | Velarized or pharyngealized | `^vfv` or `^hfv` |
| ◌̝ | Raised | `h+` |
| ◌̞ | Lowered | `h-` |
| ◌̘ | Advanced Tongue Root | `t+` |
| ◌̙ | Retracted Tongue Root | `t-` |
| ◌̪ | Dental | `d+` |
| ◌̺ | Apical | `a+` |
| ◌̻ | Laminal | `l+` |
| ◌̃ | Nasalized | `n+` |
| ◌͡◌ or ◌͜◌ | Tie Bar | `+` |

### Notes
  1. Linguolabial is counted as a place of articulation
