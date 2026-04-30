cd /workspaces/flashcards

# See what's changed
git status

# Stage everything
git add .

# Commit
git commit -m "add flashcard feature"

# Push to GitHub
git push origin main
cd /workspaces/flashcards

# Overwrite README with proper content
cat > README.md << 'EOF'
# Flashcards

Music theory flashcard feature for Groovelab — a browser-based bass guitar learning app.

## Overview

Adaptive flashcard drilling for chords, scales, and note positions across all 12 keys.

## Development

```bash
npm install
npm run dev
```

EOF

git add README.md
git commit -m "fix README content"
git push origin main
ls -la /workspaces/flashcards/
