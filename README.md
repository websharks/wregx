## WRegx™ Watered-Down Regex

- `*` Matches zero or more characters that are not a `/`
- `**` Matches zero or more characters of any kind.
- `?` Matches exactly one character that is not a `/`
- `??` Matches exactly one character of any kind.
- `[abc]` Matches exactly one character: `a`, `b`, or `c`.
- `[a-z0-9]` Matches exactly one character: `a` thru `z` or `0` thru `9`.
- `[!abc]` A leading `!` inside `[]` negates; i.e., anything that is not: `a`, `b`, or `c`.
- `{abc,def}` Matches the fragment `abc` or `def` (one or the other).
- `{abc,def,}` Matches `abc`, `def` or nothing; i.e., an optional match.
- `{/**,}` Matches a `/` followed by zero or more characters. Or nothing.
- `[*?[]!{},^$]` Matches a literal special character. One of: `*?[]!{},^$` explicitly.

---

- `^` = beginning of the string (but can be turned off depending on the use case).
- `$` = end of the string (but can be turned off depending on the use case).
