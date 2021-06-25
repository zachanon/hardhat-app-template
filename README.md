# hardhat-app-template
A template for creating hardhat based solidity apps.

### Using with docker

First build the image with

```
docker build . -t <name>:<tag>
```

To compile and run tests,

```
docker run <name>:<tag> npx hardhat test
```