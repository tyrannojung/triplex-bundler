# triplex-bundler

triplex-bundler is a simple bundler service.

## Installation and Setup

1. Install dependencies and preprocess:

```
yarn && yarn preprocess
```

2. Create configuration files:
   Use the example files as references to create actual configuration files:

```
/packages/bundler/localconfig/bundler.config.json.example → bundler.config.json
/packages/bundler/localconfig/mnemonic.txt.example → mnemonic.txt
```

Note: These files are included in .gitignore.

## Running

For standard execution:

```
yarn run bundler (or yarn run bundler --unsafe, if working with "hardhat node")
```
