# Dave Verano: Portfolio Website

Source for my personal portfolio site: a short introduction, project write-ups and contact details.

## Projects featured

| Page | Project |
|---|---|
| [`LaneDetection.html`](LaneDetection.html) | **Lane Detection** (Python, OpenCV): highlights road lanes in dash-cam images from the Berkeley DeepDrive dataset by denoising, masking white/yellow lines and finding edges, then using SIFT + KNN to keep the edges that are lane lines |
| [`EagleEye.html`](EagleEye.html) | **EagleEye** (Python): desktop app that tracks ticket price and volume on Ticketmaster and StubHub, with charts, formulas and change notifications |
| [`Roxanne.html`](Roxanne.html) | **Roxanne** (C++): autonomous competition robot built by a 4-person team on a Proteus (ARM Cortex-M4) controller; I was the main programmer ([code](https://github.com/davecverano/fehroxanne-Robot)) |

## Stack

Static HTML, CSS and JavaScript (jQuery), with styles written in Sass (`assets/sass`) and compiled to `assets/css/main.css`. Images and video live in `images/` and `videos/`.

## Running locally

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```

`index.php` and `composer.json` let the same static files be served on a PHP host such as Heroku. GitHub Pages ignores them.
