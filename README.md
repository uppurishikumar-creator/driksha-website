# Driksha — See Beyond

Website for **Driksha**, a website development & digital marketing studio founded by Rishi, Dhruthi and Kishore.

Live: https://driksha-website-mt52.vercel.app/


## Structure
```
index.html            the whole website (HTML + CSS + JS)
assets/img/           photos (team, founders, brand)
assets/video/         Instagram & YouTube screen recordings
assets/logo/          Driksha logo files (PNG + SVG)
```

## How to update
| What | Where in `index.html` |
|---|---|
| Founder links (LinkedIn / GitHub) | search `const TEAM` and paste links between the quotes |
| Add a project to "Our Work" | search `class="works3"` and copy an `<article class="work">` block |
| Contact email | search `drikshaseebeyond@gmail.com` |
| Services / FAQ text | search the heading text and edit |

New photos go in `assets/img/` and are used as `src="assets/img/your-photo.jpg"`.

## Deploy
Connected to Vercel — every push to `main` goes live automatically in about 30 seconds.
