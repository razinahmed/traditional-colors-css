# Traditional Colors CSS

![CSS](https://img.shields.io/badge/CSS-Colors-blue)
![Design](https://img.shields.io/badge/Design-Tokens-purple)
![License](https://img.shields.io/badge/License-MIT-green)

A CSS color palette library drawn from Kerala's traditional art forms, festivals, and natural landscapes. Provides design tokens as CSS custom properties for building culturally inspired interfaces.

## Features

- Curated color palette based on Kerala traditions (temple gold, banana leaf green, monsoon grey, etc.)
- CSS custom properties for easy integration into any project
- Dark theme foundation with vibrant accent colors
- Framework-agnostic -- works with React, Vue, Angular, or plain HTML
- Minimal footprint with no dependencies

## Tech Stack

| Technology | Purpose              |
|------------|----------------------|
| CSS3       | Color definitions    |
| Make       | Build automation     |

## Quick Start

1. Clone the repository:

```bash
git clone https://github.com/razinahmed/traditional-colors-css.git
cd traditional-colors-css
```

2. Include the stylesheet:

```html
<link rel="stylesheet" href="styles/theme.css" />
```

3. Use the color variables:

```css
.banner {
  background-color: var(--background);
  color: var(--primary);
}
```

## Color Palette

| Variable       | Value     | Inspiration          |
|----------------|-----------|----------------------|
| `--primary`    | `#00d4aa` | Tropical green       |
| `--background` | `#1e1e2e` | Twilight sky         |

Additional colors and extended palettes can be added following the same custom property pattern.

## Usage with Frameworks

```jsx
// React example
<div style={{ color: 'var(--primary)' }}>
  Kerala-themed content
</div>
```

## Build

```bash
make build
make test
```

## Project Structure

```
traditional-colors-css/
  styles/
    theme.css       # Core color definitions
  Makefile          # Build commands
  LICENSE           # MIT License
```

## Contributing

Contributions are welcome. If you have color suggestions rooted in Kerala or Indian traditions, please open an issue or pull request.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
