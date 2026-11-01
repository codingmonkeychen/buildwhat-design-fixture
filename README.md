# BuildWhat Test Design System

Minimal public fixture for the BuildWhat GitHub Design System import test.

## Files

```text
DESIGN.md
tokens.json
README.md
```

`DESIGN.md` and `tokens.json` are at the repository root.

## Upload

1. Create a new public GitHub repository.
2. Upload all files in this directory to the repository root.
3. Confirm the repository is public.
4. Use one of these URLs in BuildWhat:

```text
https://github.com/<owner>/<repo>
```

or, if the files live in a subdirectory:

```text
https://github.com/<owner>/<repo>/tree/<branch>/<directory>
```

The expected import reads:

```text
<base>/DESIGN.md
<base>/tokens.json
```

## Expected import

- Title: `BuildWhat Test Design System`
- Colors: 4
- Typography: 2 families + 3 sizes + 2 weights
- Spacing: 4
- Radii: 3
- Components: 3

## Notes

This repository intentionally contains no secrets, credentials, or private data.
