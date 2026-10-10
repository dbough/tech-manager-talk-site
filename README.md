# Tech Manager Talk site

Static Jekyll site for techmanagertalk.com, hosted on GitHub Pages.

## Change things

- Links, email, and the intro video: edit `_config.yml`. Put the YouTube video ID in `intro_video_id` to swap the placeholder for the video.
- Page content: `index.html`
- Colors and fonts: `assets/css/style.css` (colors are variables at the top)

## Preview locally (optional)

```
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.

## Deploy

Push to the `main` branch. In the repo, go to Settings, then Pages, and set the source to "Deploy from a branch" with `main` and `/ (root)`. The `CNAME` file already holds techmanagertalk.com.
