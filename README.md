# Getting Started

## Tailwind Command

The `tailwind` command is used to process Tailwind CSS files. It takes an input CSS file, processes it with Tailwind CSS, and outputs the result to a specified file. The `--watch` flag ensures that the command continues to run and updates the output file whenever the input file changes.

### Usage

To run the `tailwind` command, use the following:

```sh
npx tailwindcss -i ./css-src/styles.css -o ./css/tailwind-styles.css --watch
```