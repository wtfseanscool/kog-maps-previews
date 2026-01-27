# KoG Maps Previews

Map preview images for the [KoG Map Downloader](https://github.com/wtfseanscool/kog-map-downloader).

## Structure

- `thumbnails/` - 360x160 PNG thumbnails for grid view
- `full/` - 1920x1080 PNG full HD previews

## Usage

Images are accessed via raw GitHub URLs:
- Thumbnail: `https://raw.githubusercontent.com/wtfseanscool/kog-maps-previews/main/thumbnails/{mapname}.png`
- Full HD: `https://raw.githubusercontent.com/wtfseanscool/kog-maps-previews/main/full/{mapname}.png`

## Generation

Previews are generated using [twgpu-map-photography](https://gitlab.com/ddnet-rs/twgpu).

## Stats

- Total maps: 1046
- Generated previews: 1026
- Failed (map parsing issues): 20
