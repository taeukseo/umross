# UMRoss Beamer Theme

An unofficial Beamer presentation theme for the Stephen M. Ross School of Business at the University of Michigan.

## Quick Start

1. Copy `beamerthemeUMRoss.sty` to your presentation directory
2. Use the template in `slides.tex` as a starting point
3. Compile with your LaTeX editor

## Basic Usage

In your `.tex` file:

```latex
\documentclass[aspectratio=169]{beamer}
\usetheme{UMRoss}

\title{Your Presentation Title}
\author{Your Name}
\date{\today}

\begin{document}
\begin{frame}[plain]
    \titlepage
\end{frame}

% Your content slides here

\end{document}
```

## Features

- Official UMRoss colors (maize and blue color scheme)
- Clean and professional design
- Customizable title page
- Support for blocks, alerts, and standard Beamer features
- Ross logo in footer

## Customization

### Fonts
The template uses FiraSans by default. To use different fonts, modify the preamble:

```latex
\usepackage[sfdefault]{YourFont}
\usepackage[T1]{fontenc}
```

### Images
Place your images in an `images/` folder and set the path:

```latex
\graphicspath{{images/}}
```

## Files

- `beamerthemeUMRoss.sty` - Complete theme file (colors, fonts, layout)
- `slides.tex` - Example template to get started
- `images/rosslogo.png` - Ross logo for footer

## Acknowledgements

This theme was developed on the basis of the *Saarland* theme by Kailash Budhathoki: https://github.com/kailashbuki/beamerthemesaarland

Special thanks to James Caldera for valuable comments. 