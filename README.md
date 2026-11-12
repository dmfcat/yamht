# yamht

A minimalist website theme for Hugo.

## Features

- Minimalist monochrome design with an accent colour.
- Automatic light/dark theme switching between two Catppuccin pastel themes.
- Responsive layout, with a hamburger menu on mobile devices.
- Shortcodes for embedding videos and images.
- Support for blog posts
- Dedicated page for browsing posts by tag.

## Getting Started

Make sure you have [Hugo](https://gohugo.io/installation/) and [Git](https://git-scm.com/install/) installed.

1. Create a new project

```bash
hugo new project website-name
cd website-name
```

2. Clone this repo into your projects `themes` directory

```bash
git clone https://github.com/dmfcat/yamht themes
```

3. Add yamht to your `hugo.toml`

```bash
echo "theme = yamht" >> hugo.toml
```

4. Start a development server, and click the `localhost` link to view the theme

```bash
hugo serve
```

You can optionally copy the example site provided with the theme into your project directory

```bash
cp -r themes/yamht/exampleSite/* ./
```

## Licence

[MIT](LICENCE)
