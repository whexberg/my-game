# MyGame

## Setup

```sh
# Setup build system for debug
cmake -DCMAKE_BUILD_TYPE=Debug -B .debug
```

```sh
# Setup build system for release
cmake -DCMAKE_BUILD_TYPE=Release -B .release
```

## Build

```sh
# Build the debug version
cmake --build .debug
```

```sh
# Build the release version
cmake --build .release --clean-first
```

## Run

```sh
# Run the debug version
.debug/MyGame
```

```sh
# Run the release version
.release/MyGame
```