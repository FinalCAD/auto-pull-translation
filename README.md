# Auto Pull Phrase Translation

This Github action finds the "phrase.yml" file on your repository, retrieves the latest translations and creates a pull request.

# Usage

```yaml
- name: Auto Pull Phrase Translation
  uses: finalcad/auto-pull-translation@v2
  with:
    path-to-phrase-yml: './MyFolder' # Path to ".phrase.yml" file.
```
