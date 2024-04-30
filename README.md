# dotfiles

These dotfiles are managed with Chezmoi

## Quick Start

1. Fork this repo
2. `brew install chezmoi`
3. `~/.config/chezmoi/chezmoi.yaml`
   ```yaml
   data:
     email: [YOUR_EMAIL]
   ```
4. `chezmoi init --apply --verbose https://github.com/[GITHUB_USERNAME]/dotfiles.git`
5. See how to make your own customization with [Chezmoi How-To](https://www.chezmoi.io/docs/how-to/)
