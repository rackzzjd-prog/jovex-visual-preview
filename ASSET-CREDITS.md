# Asset sources and implementation provenance

## Actual photographs

1. **Falcon 9 / DSCOVR at the launch pad, SpaceX.**
   - Local asset: `assets/rocket.jpg` (640 × 427).
   - Retrieved from: https://raw.githubusercontent.com/scikit-image/scikit-image/v0.19.3/skimage/data/rocket.jpg
   - Original source documented by scikit-image: https://www.flickr.com/photos/spacexphotos/16511594820/in/photostream/
   - Its `rocket()` documentation identifies SpaceX as the photographer and states that the image was released into the public domain. This is a pre-launch still photograph, not footage of a moving launch.
2. **Eileen Collins, NASA.**
   - Local asset: `assets/astronaut.png` (512 × 512).
   - Retrieved from: https://raw.githubusercontent.com/scikit-image/scikit-image/v0.19.3/skimage/data/astronaut.png
   - Original source documented by scikit-image: NASA Great Images, https://flic.kr/p/r9qvLn
   - Its `astronaut()` documentation states “No known copyright restrictions, released into the public domain.” The portrait is used as an editorial image study, not a JOVEX team member, client, or endorsement.

Provenance text inspected at: https://raw.githubusercontent.com/scikit-image/scikit-image/v0.19.3/skimage/data/_fetchers.py

These small public-domain image fixtures keep the experiment portable. They demonstrate composition and layered UI; they are not proposed final-resolution production image selections. No AI image generation was used for this showcase.

## Original UI and graphics

The layouts, geometric posters, device casing, service graphics, interface fixtures, and CSS treatments were created for this independent lab. They do not contain Orbital Studio, Agencera, Flow Ninja, or earlier JOVEX components, proprietary models, template code, or client assets. Browser/system fonts avoid external font requests. No new package is needed to run the showcase.
