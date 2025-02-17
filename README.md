# Skådis Board Generator

Skådis Board Generator is a lightweight, web-based tool that generates customizable SVG layouts for Skådis boards. This project allows you to create an accurate digital representation of a Skådis board with configurable dimensions, hole parameters, spacing, and row offset options. It's ideal for applications such as laser cutting, CNC machining, or prototyping.

You can try on [this](https://harcerz.github.io/skadis-gen/)

## Features

- **Configurable Board Dimensions:** Set the overall width and height of the board.
- **Adjustable Hole Parameters:** Customize hole width, hole height, and corner radii for both the holes and the board.
- **Custom Spacing:** Define horizontal spacing and vertical gaps. Margins are automatically calculated based on half the hole size plus the gap.
- **Row Offset Options:** Optionally reverse the row offset so that the first row is shifted relative to the second, mimicking the original Skådis board layout.
- **SVG Export:** Generate and download the board design as an SVG file for further use in various design or fabrication processes.
- **Responsive Interface:** A simple and user-friendly interface built with HTML, CSS, and vanilla JavaScript.

## How It Works

1. **Input Parameters:**  
   Enter the board dimensions, hole dimensions, spacing, and corner roundness using the web form.

2. **Dynamic SVG Generation:**  
   The tool calculates the number of rows and columns based on the provided parameters and generates an SVG with precise placement of the holes.

3. **Download:**  
   Preview the generated SVG and download it for fabrication or further editing.

## Usage

1. Open the `index.html` file in your web browser.
2. Adjust the parameters (board size, hole spacing, hole dimensions, etc.) using the provided controls.
3. Click the **"Generate"** button to preview your customized Skådis board.
4. Click the **"Download SVG"** button to save the generated SVG file.

## Installation

No installation is required. Simply clone the repository and open the `index.html` file in any modern web browser:

```bash
git clone https://github.com/yourusername/skadis-board-generator.git
