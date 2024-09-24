# Reproduction for different canvas rendering across macOS Intel and Apple Silicon

Issue: https://issues.chromium.org/u/1/issues/369223554

## Steps to reproduce

1. `npm install`
1. `node screenshot.mjs`
1. Run it via GitHub Actions, so it runs across different architectures
1. Compare it via `npx -y pixelmatch ../../../Downloads/screenshot1.png ../../../Downloads/screenshot2.png diff.png``
