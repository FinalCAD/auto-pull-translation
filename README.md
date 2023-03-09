# Auto Pull Phrase Translation

This Github action finds the "phrase.yml" file on your repository, retrieves the latest translations and creates a pull request.

# Usage

```yaml
- name: Auto Pull Phrase Translation
  uses: finalcad/auto-pull-translation@v2
  with:
    path-to-phrase-yml: './MyFolder' # Path to ".phrase.yml" file.
    reviewers: 'user1,user2' # List of reviewers to add to the pull request, comma-separated list (no spaces)
```
