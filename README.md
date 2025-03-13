# Google AI Studio Starter Applets

This repository contains the source code for Google AI Studio's
[starter apps](https://aistudio.google.com/app/starter-apps) — a collection of
small apps that demonstrate how Gemini can be used to create interactive
experiences. These apps are built to run inside AI Studio, but the versions
included here can run standalone using the
[Gemini API](https://ai.google.dev/gemini-api/docs).

## Spatial Understanding

[Spatial Understanding](/spatial/)
([live demo](https://aistudio.google.com/app/starter-apps/spatial)) is a simple
demonstration of Gemini's 2D and 3D spatial understanding and reasoning
capabilities. It was built with React.

This example should give you an idea of how to get started with spatial analysis
using Gemini. Check out [Prompt.tsx](/spatial/src/Prompt.tsx) to see how
bounding box parsing is implemented. To dive deeper into Gemini's spatial
reasoning capabilities, check out this
[Colab notebook](https://github.com/google-gemini/cookbook/blob/main/gemini-2/spatial_understanding.ipynb).

To develop locally, insert your Gemini API key in the `.env` file.

### Contributors

- [@bencobley](https://github.com/bencobley)
- [@dmotz](https://github.com/dmotz)
- [@grantcuster](https://github.com/grantcuster)
- [@hapticdata](https://github.com/hapticdata)
