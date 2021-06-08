# TENTSLP Token Icons

A hosted repository of all known TENTSLP token icons. All tokens added here will be served via a censorship resistant endpoint located at https://tokens.tent.app

## Want to add a NFT token icon?

NFT token icons will not be accepted (there are too many).

## Adding your icon

Create a version of your icon in 32x32, 64x64, 128x128 and "original" (more than or equal to 128px) and add them to their respective folders in a pull request. If you have a SVG file, feel free to add that to (though SVG's will not be served from the endpoint). After adding your icon and made the pull request please contact us on [Discord](https://discord.gg/78rVJcH).

## Endpoint Usage

The endpoint will automatically resize and losslessly optimize the photos it serves.

Your icon will be available from https://tokens.tent.app/ `{size}` / `{txid}` . `{format}`

* `{size}` can be any number from 1-1700 (or "original" for the biggest version available)

* `{txid}` is the transaction id of the token genesis transaction (aka token id)

* `{format}` can be png, jpg, tiff or webp (endpoint will properly convert from png)

## Examples

`https://tokens.tent.app/256/4ac91a7245936cda41cfa616c342cbcd111a72a60bf37fdf8e556926cbaa7b28.png`

`https://tokens.tent.app/original/4ac91a7245936cda41cfa616c342cbcd111a72a60bf37fdf8e556926cbaa7b28.png`

## Services using tentslp-token-icons

[slp.tent.app](https://slp.tent.app) [mint.tent.app](https://mint.tent.app)
