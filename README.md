# axisminer

> AXIS miner with OpenCL, CUDA and stratum support

**axisminer** is an ProgPoW GPU mining worker: with axisminer you can mine Axis. This is the actively maintained version of axisminer. It originates from [cpp-ethereum] project (where GPU mining has been discontinued) and builds on the improvements made in [Genoil's fork].

## Features

* OpenCL mining
* Nvidia CUDA mining
* realistic benchmarking against arbitrary epoch/DAG/blocknumber
* on-GPU DAG generation (no more DAG files on disk)
* stratum1 mining without proxy
* OpenCL devices picking
* farm failover (getwork + stratum1)


## Usage

The **axisminer** is a command line program. This means you launch it either
from a Windows command prompt or Linux console, or create shortcuts to
predefined command lines using a Linux Bash script or Windows batch/cmd file.
For a full list of available command, please run:

```sh
axisminer --help
```

## Build

### Building from source

See [docs/BUILD.md](docs/BUILD.md) for build/compilation details.


## License

Licensed under the [GNU General Public License, Version 3](LICENSE).


[Gitter]: https://gitter.im/axis-cash/miner
[Releases]: https://github.com/axis-cash/axisminer/releases
