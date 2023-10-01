# mdformat composite action

mdformat composite action uses [mdformat](https://mdformat.readthedocs.io/)
to check formatting of Markdown documents.

## Inputs

### `paths`

**Required** Paths passed to mdformat

## Example usage

```yaml
name: Check Markdown formatting
uses: iamleot/actions/mdformat
with:
  paths: .
```
