# CDLinC Library
This library enables you to send and receive CLD messages using simple C.

Check [here](https://github.com/programmerman69) for tutorials and more information.

## Version - 1.00

## Installation
1. Navigate to the [Releases](https://github.com/programmerman69) page.
2. Download the latest release.
3. Extract the zip file
4. Move the "CLDinC" folder that has been extracted to your libraries directory.

## Usage

We get a lot of support for different device types. To keep the size of the library manageable we're moving to a model where different device types use a #define statement, for instance:

```#define SHARP```

You'd put this at the top of your sketch to include the sendSharp() and decodeSharp() methods in your code. This way your sketch only uses the Sharp functions but not the LG, JVC, Sony, etc functions, thus saving you program space that you might want to use for other things. This allows us to support lots of devices without making the library too big.

## Contributing
If you want to contribute to this project:
- Report bugs and errors
- Ask for enhancements
- Create issues and pull requests
- Tell other people about this library

## Contributors
Check [here](Contributors.md)

## Copyright
Copyright 2009-2012 Ken Shirriff
