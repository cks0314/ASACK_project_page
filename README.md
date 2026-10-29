# SACK project page

Static site for GitHub Pages. Push this folder's contents to the repo root (or a `docs/` folder) and enable Pages.

Still to fill in (search `TODO` in index.html): arXiv, Code and Video links.

Adding the experiment videos later:
- FR3 videos are in (tabbed: nominal / resistive torque; Gazebo render on top, path plot below).
- The TurtleBot3 hardware section has a commented-out `compare-grid` block right above a
  "coming soon" placeholder. Drop the .mp4 files into `static/videos/`, uncomment the block, set the `src`s,
  and delete the placeholder `<div class="video-placeholder">`.
- For small, web-friendly files: `ffmpeg -i in.mp4 -an -c:v libx264 -preset veryfast -crf 23 -pix_fmt yuv420p -movflags +faststart out.mp4`

Video naming used here: NK = *_base, NAK = *_adap_neur, AcK = *_adap_active_edmd, SACK = *_constrained_active_lyap.
