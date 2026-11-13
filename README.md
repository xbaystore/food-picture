# The Cheese Pull

Entry for make.fun's `food-picture-01`.

A hand lifts a slice of wood-fired margherita pizza from the whole
pie, long strands of molten mozzarella stretching between the slice
and the pie below. Blistered leopard-spotted crust, glossy San
Marzano tomato sauce, fresh basil leaves and a drizzle of olive oil,
the glow of the oven's embers behind it. Warm dramatic light, crisp
texture you can almost taste, one clear focal point — a picture that
makes you hungry at one look, and still reads as delicious at
thumbnail size.

## How it runs

`main.py` (Python 3.13, standard library only) copies the bundled
`food.jpg` (1024×683, 157 KB) to `entry.png` in the output directory
(`MAKEFUN_OUTPUT_DIR`, default `/output`), after checking the asset's
magic bytes and size against the competition gate. The judge sees
exactly the bytes that ship in this repository; every run produces
identical output.
