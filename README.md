# Welcome to Xardian node operator software download page

## Installation
To install the Xardian node operator software, download it from this page. We currently offer versions for Windows x86-64, macOS Intel, macOS Apple Silicon, and CLI. We are working on releases for additional architectures. Download links are below:

### Xardian UI

[MacOS Apple Silicon version](https://github.com/xprotocol-org/xardian/releases/download/v0.0.2/Xardian.app.arm64.zip)

[MacOS Intel version](https://github.com/xprotocol-org/xardian/releases/download/v0.0.2/Xardian.app.x86-64.zip)

[Windows x86_64 version](https://github.com/xprotocol-org/xardian/releases/download/v0.0.2/Xardian.x86-64.exe) 

### Xardian CLI

[MacOS Apple Silicon](https://github.com/xprotocol-org/xardian/releases/download/v0.0.2/runner.darwin.amd64)

[MacOS Intel](https://github.com/xprotocol-org/xardian/releases/download/v0.0.2/runner.darwin.arm64)

[Linux x86_64](https://github.com/xprotocol-org/xardian/releases/download/v0.0.2/runner.linux.amd64)

[Linux ARM64](https://github.com/xprotocol-org/xardian/releases/download/v0.0.2/runner.linux.arm64)

[Windows x86_64](https://github.com/xprotocol-org/xardian/releases/download/v0.0.2/runner.windows.amd64.exe)

[Windows ARM64](https://github.com/xprotocol-org/xardian/releases/download/v0.0.2/runner.windows.arm64.exe)

After downloading, unzip the macOS version and execute the following command in Terminal:

```bash
xattr -c /path/to/Xardian.app
```

Replace /path/to/Xardian.app with the actual path where you downloaded the app. Then, you can double-click the Xardian app to start.

For Windows version, start the application by double-clicking it.

For CLI versions, first you will need to enable execution bit on it by `chmod +x runner.linux.amd64`. Then you can launch them by triggering them in the command line. 
For settings up, you will need to do delegation first by 

```bash
runner.linux.amd64 delegate
```
and follow instructions of the program. Then you can run the CLI version to receive reward using:

```bash
runner.linux.amd64 run
```

Replace `runner.linux.amd64` with your chosen version.

For detailed instructions on using the software, refer to: https://docs.xprotocol.org/x-protocol-litepaper/overview/xardian-nodes/how-to-run-nodes
