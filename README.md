# Blender Render Job Template

This Nosana job renders a `.blend` file using Blender's headless rendering mode.

## What It Does

- Uses Blender 3.6.0 to render a frame from `sample.blend`
- Outputs the image to a `render/` folder
- Demonstrates GPU capability for creative workloads

## Usage

1. Add your own `.blend` file to the root of this template.
2. Modify the script in `job-definition.json` to fit your scene (e.g., render frames `1-10` or animation).
3. Push your job to Nosana and check the `render/` folder for output.

## Output

- `render/frame_00001.png` (or more if you render a sequence)

## Requirements

- A valid `.blend` file in the root directory.
- GPU runner recommended for faster rendering.

## Resources

- [Blender CLI Docs](https://docs.blender.org/manual/en/latest/advanced/command_line.html)
