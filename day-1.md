# Daily Learning

## Morning Planning

- https://github.blog/ for topic ideas.
- https://skills.github.com/#first-day-on-github.
- [ ] Convert my first blog post into an actual webpage.

### Review

- [ ] Convert media from dark mode to light mode

Convert an image or video from dark mode to light mode using https://www.ffmpeg.org

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
