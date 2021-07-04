# Keynote Template with Svelte Components

It is a template for online slide powered by [reveal-md](https://github.com/webpro/reveal-md) and [svelte.js](https://svelte.dev/).

You can start up your multi-page online slide easily by this command.

```bash
npx degit whatishappyplanet/keynote-svelte .
```

## What is the difference with [whatishappyplanet/keynote](https://github.com/WhatisHappyPlanet/keynote)?

You can use your svelte components in your markdown. It is a gorgeous feature to customize your oneline slide. For example:

```markdown
<my-element>
    <p>This is some slotted content</p>
</my-element>

# Reveal.js
### The HTML Presentation Framework
```

## Usage

### Development

Then, install dependencies and enjoy your presentation.

```bash
pnpm i
pnpm dev
```

### Deployment

You can deploy the static resource to any platform, such as Vercel.

```bash
pnpm build
```

## License

[MIT](./LICENSE) @ HappyPlanet
