# u76 Alphabet Specification

The u76 alphabet consists of 76 unique characters. The index of each character determines its numerical value in a base-76 positional system.

| Index | Character | Description |
|-------|-----------|-------------|
| 0-9   | `0-9`     | Arabic Numerals |
| 10-35 | `a-z`     | Lowercase Latin |
| 36-61 | `A-Z`     | Uppercase Latin |
| 62-75 | `...`     | Selected Special Characters |

## Selection Criteria
1. **URL Safety:** Characters must not require percent-encoding (RFC 3986).
2. **Visual Clarity:** Distinction between `1`, `l`, `I` and `0`, `O`.
3. **Sort Order:** The alphabet is ordered by ASCII/Unicode code point value for predictable lexicographical sorting.