# Daily Learning

## Morning Planning
<img alt="Cloudy morning" src="https://octodex.github.com/images/cloud.jpg" width="100" align="right">

- [ ] Check out the [github blog](https://github.blog/) for topic ideas.
- [ ] Learn about [GitHub Pages](https://skills.github.com/#first-day-on-github).
- [ ] Convert my first blog post into an actual webpage.
## Review
Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
Absolute path to an image online
```
![Mona the Octocat](https://octodex.github.com/images/original.png)
```
Relative path to an image in repo
```
![Mona the Octocat](myrepo/original.png)
```
HTML configuration
```
<img alt="Cloudy morning" src="https://octodex.github.com/images/cloud.jpg" width="100" align="right">
```
