# FrameLab Coach join page

Published with GitHub Pages at https://namrahkram.github.io.

- `.well-known/apple-app-site-association` tells iPhones and iPads that
  links under `/coach/join` belong to FrameLab Coach, so tapping one opens
  the app instead of this website.
- `coach/join/index.html` is what shows if a link opens in a browser
  anyway: an Open in FrameLab Coach button, and help for people who don't
  have the app yet.
- `.nojekyll` makes GitHub Pages publish the `.well-known` folder.

`INSTALL_URL` in `coach/join/index.html` is where people without the app
get it: the TestFlight public link for now, the App Store link later
(change `INSTALL_LABEL` too). The app's `ProgramSharing.installURL` should
match.
