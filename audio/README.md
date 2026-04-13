# Audio Files

Place audio files here for articles with radio/podcast versions.

## Requirements

- **Format**: MP3 (`.mp3`)
- **Recommended bitrate**: 128-192 kbps (balances quality and file size)
- **Max file size**: Keep under 50MB for reasonable load times

## Usage

1. Add your audio file to this folder (e.g., `my-story.mp3`)
2. In your article's frontmatter, add:
   ```yaml
   audio: '/audio/my-story.mp3'
   ```
3. The audio player will appear automatically on the article page
4. An "Audio" badge will show on the article card

## Example

```yaml
---
title: 'My Radio Story'
excerpt: 'This story aired on KQED...'
category: 'Environment'
date: 'February 1, 2026'
publication: 'KQED'
image: 'https://example.com/image.jpg'
audio: '/audio/my-radio-story.mp3'
---
```

## Notes

- Audio files are served directly by the browser (no streaming server needed)
- Larger files work fine but will be slower to load on mobile
- Consider editing/trimming audio to reduce file size if needed
