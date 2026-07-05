# Daily Learning
## Morning Planning
<img alt="Cloudy morning" src="https://octodex.github.com/images/cloud.jpg" width="100" align="right">

- [ ] 話題のアイデアを探すために [github blog](https://github.blog/) をチェックする。
- [ ] [GitHub Pages](https://skills.github.com/#first-day-on-github) について学ぶ。
- [ ] 最初のブログ記事を実際のウェブページに変換する。
## Review
Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
