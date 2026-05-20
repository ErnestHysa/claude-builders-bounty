# Changelog Generator — README

## Quick Start (3 Steps)

```bash
# 1. Save changelog.sh to your project root
curl -O https://raw.githubusercontent.com/ErnestHysa/changelog-skill/main/changelog.sh

# 2. Run it
bash changelog.sh

# 3. Your CHANGELOG.md is ready
cat CHANGELOG.md
```

## Setup as a Git Alias

```bash
echo 'alias changelog="bash /path/to/changelog.sh"' >> ~/.bashrc
source ~/.bashrc
changelog
```

## What It Does

- Reads commits since your last git tag
- Categorizes: Added / Fixed / Changed / Removed
- Outputs a clean `CHANGELOG.md`

## Test It Now

```bash
git clone https://github.com/ErnestHysa/changelog-skill.git
cd changelog-skill
bash changelog.sh
cat CHANGELOG.md
```