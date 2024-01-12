# Lambda Machine

when implementing lambda calculus as an interpreter,
the depth of the call stack is limited by the hosting language.
To avoid this limitation we should implement lambda calculus by machine like SECD.

## Usages

### Command line tool

Install it by the following command:

```sh
npm install -g @cicada-lang/lambda-machine
```

## Development

```sh
npm install           # Install dependencies
npm run build         # Compile `src/` to `lib/`
npm run build:watch   # Watch the compilation
npm run format        # Format the code
npm run test          # Run test
npm run test:watch    # Watch the testing
```

## Contributions

To make a contribution, fork this project and create a pull request.

Please read the [STYLE-GUIDE.md](STYLE-GUIDE.md) before you change the code.

Remember to add yourself to [AUTHORS](AUTHORS).
Your line belongs to you, you can write a little
introduction to yourself but not too long.

## License

[GPLv3](LICENSE)
