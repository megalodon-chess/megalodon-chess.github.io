# Megalodon Chess

Open source chess engine and GUI.

## Megalodon

Megalodon is a chess engine written in C++.

* [Source code][megalodon]
* [Documentation][megalodon-docs]

## Hammerhead

Hammerhead is a chess GUI writte in Python.
It uses the Pygame module to generate the graphics.

* [Source code][hammerhead]

## Contributing

### Editing the Code

Please fork one of the repositories, make your changes, and create a pull request.

Our team will review the changes and may merge them to the main repository.

You can also develop your own technologies using Megalodon as a starting point.

### Tuning Evaluation

Megalodon's evaluation function contains many areas,
such as material, kings, pawns, etc.

These have weights to them, but they are not tuned yet.
You can help tune them by having Megalodon play against itself
on your computer.

This is done using the [Sharktest][sharktest] system.

The Megalodon team has plans to implement neural networks into Megalodon
in the future, which will require even more tuning!

[megalodon]: https://github.com/megalodon-chess/megalodon
[megalodon-docs]: https://megalodon-chess.github.io/megalodon
[hammerhead]: https://github.com/megalodon-chess/hammerhead
[sharktest]: https://github.com/megalodon-chess/sharktest
