# Rubber ball

- [Mixing Vellum Constraints | SideFX](https://www.sidefx.com/tutorials/mixing-vellum-constrains/)

## Encoding

```sh
ffmpeg -apply_trc iec61966_2_1 -r 24 -i "render/rubber.karmarendersettings.%04d.exr" -c:v libx264 -profile:v baseline -crf 2 -pix_fmt yuv420p -r 24 out.mp4
```
