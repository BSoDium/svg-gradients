![alt text](assets/banner.png)

# SVG Gradients

This repository contains a collection of experiments with SVG turbulence-based gradients.

## Usage

The `LinearGradient` component is designed to be used as a drop-in replacement for the standard `linearGradient` element in SVG. Its expected usage is thoroughly documented in the source code, along with a few examples, which can be found in the `examples` directory.

## Installation

To set up the demo, clone the repository and run the following commands:

```sh
yarn install
yarn dev
```

## Examples

The following examples demonstrate possible use cases for the `LinearGradient` component:

- [Banner](./src/examples/Banner.tsx) - a simple material you banner with a gradient background
- [Linear debug animation](./src/examples/DebugAnimationLinear.tsx) - a debug animation that visualizes the linear turbulence field and its boundaries
- [Radial debug animation](./src/examples/DebugAnimationRadial.tsx) - a similar debug animation for the radial turbulence field
- [Flower](./src/examples/Flower.tsx) - a flower-like primitive shape with a gradient background
- [Multiple layers](./src/examples/MultipleLayers.tsx) - a composition of multiple layers with different turbulence settings and colors
- [Sparkle](./src/examples/Sparkle.tsx) - a simple sparkle animation with a gradient background
- [Text](./src/examples/Text.tsx) - a text element with a gradient background
- [Arch](./src/examples/Arch.tsx) - a more artistic composition with advanced masking techniques, featuring a transparent gradient background
- [Torus](./src/examples/Torus.tsx) - a torus-like primitive shape built with multiple layered gradients
- [Abstract](./src/examples/Abstract.tsx) - an abstract composition featuring a mix of masks, gradients, and shapes, showcasing the full potential of the `LinearGradient` and `RadialGradient` components