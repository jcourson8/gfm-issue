# solid-markdown remarkGfm Issue

This repository demonstrates an issue with using the `remarkGfm` plugin with the `solid-markdown` library.

## Steps to Reproduce

1. Clone this repository.
2. Install the dependencies by running `npm install` or `yarn install`.
3. Run the development server using `npm run dev` or `yarn dev`.
4. Open the browser and observe the console error.

## Expected Behavior

The markdown should be rendered correctly with GitHub Flavored Markdown support.

## Actual Behavior

An error is thrown in the console when the `remarkGfm` plugin is included in the `remarkPlugins` prop of the `SolidMarkdown` component.

## Environment

- solid-markdown version: 2.0.13
- remark-gfm version: 4.0.0
- SolidJS version: 1.4.7

## Additional Information

The issue occurs specifically when using the `remarkGfm` plugin with `solid-markdown`. Removing the plugin resolves the error but loses the GitHub Flavored Markdown functionality.
