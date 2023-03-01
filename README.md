# Auto Pull Phrase Translation v1

This Github action finds the "phrase.yml" file on your repository, retrieves the latest translations and creates a pull request.

# Usage

```yaml
- name: Auto Pull Phrase Translation v1
  uses: finalcad/auto-pull-translation@v1
  with:
    path-to-phrase-yml: './MyFolder' # Path to ".phrase.yml" file.
```
