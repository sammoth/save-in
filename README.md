# save-in

[Download beta release](https://github.com/gyng/save-in/releases/)

![Screenshot](docs/screenshot.png)

A web extension (Chrome, Firefox) for saving images, videos, audio, and links into specified directories.

Will only save into directories relative to the default download directory but symlinks can be used to get around this limitation.

See the options page for more information.

## Development

1. Install dev dependencies `yarn install`
2. Develop
3. `yarn lint` and/or `yarn lint:fix`
4. `yarn package` to create a zip in the `build` directory for Firefox
