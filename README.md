## Inverse Problems in NeuroMANCER

In computational imaging, such as microscopy, reconstructing a 3D scene from incomplete 2D measurements is a critical but challenging task due to the lack of sufficient data. Instead of relying on direct inversion, optimization methods are employed to efficiently find sparse and non-negative solutions. Traditional approaches are often too slow for large-scale problems, so the process is optimized in Fourier space and further simplified using auxiliary variables. The ADMM algorithm is particularly effective in dividing the problem into smaller, more manageable parts.

I have explored how the NeuroMANCER library addresses inverse problems involving non-smooth regularizers. I focus on solving these inverse problems using the NeuroMANCER library and emphasize that the library requires fine-tuning to effectively handle non-smooth regularizers.

Check out the .pdf report file, which outlines in detail the work mentioned above.
