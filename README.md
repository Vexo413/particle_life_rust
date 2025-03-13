# Particle Life Rust

## Description

Particle Life was originally created by the computer scientist Jeffrey Ventrella, where it was first called 'Clusters'.
There have been many different implementations of it and now is more commonly referred to as 'Particle Life'.
This is my implementation of Particle Life in Rust and Bevy, with the goal of high customization.

The simulation is quite simple, each particle color, or species has it's own special relation to every other color, which can be defined in a table. If the relation is 1 the particle will have a full velocity towards that particle, if it is -1 it will have a full velocity going away from that particle. Then all of these velocitys would be added together to get the output velocity at which the particle moves. There is also min distance, beta so that they don't group into a single point and a max distance, gamma.



## Installation

First make sure you have rust installed.

[1]: https://www.rust-lang.org/learn/get-started

Download rust [here][1].

To get the files, either use git,

```
git clone https://github.com/Vexo413/particle_life_rust.git
```

[2]: https://github.com/Vexo413/particle_life_rust/releases/tag/v0.2.2

Or download the zip file from the github page [here][2].

Then go to the project directory in your terminal and run:

```
cargo run --release
```

## Controls

`WASD`: Move camera

`↑`: Zoom in

`↓`: Zoom out

`Left Click`: Add particle

`Right Click`: Add 100 particles


## Links

[3]: https://www.rust-lang.org/

- [Rust][3]

[4]: https://bevyengine.org/

- [Bevy][4]

[5]: https://particle-life.com/

- [Particle-life][5]
