# actionlint composite action

actionlint composite action lint and validates all GitHub Actions workflows via
[actionlint](https://github.com/rhysd/actionlint) and adds annotations if there
is any errors.

## Inputs

### `pyflakes`

Path to `pyflakes` external command.

**Default**: `""` (disabled)

### `shellcheck`

Path to `shellcheck` external command.

**Default**: `""` (disabled)

## Example usage

```yaml
name: Lint GitHub Actions workflows
uses: iamleot/actions/actionlint
with:
  shellcheck: shellcheck
```
