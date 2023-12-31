```
██╗  ██╗███████╗██╗  ██╗██╗   ██╗██████╗ ██╗      ██████╗  █████╗ ██████╗ 
██║ ██╔╝██╔════╝██║ ██╔╝██║   ██║██╔══██╗██║     ██╔═══██╗██╔══██╗██╔══██╗
█████╔╝ █████╗  █████╔╝ ██║   ██║██████╔╝██║     ██║   ██║███████║██║  ██║
██╔═██╗ ██╔══╝  ██╔═██╗ ██║   ██║██╔═══╝ ██║     ██║   ██║██╔══██║██║  ██║
██║  ██╗███████╗██║  ██╗╚██████╔╝██║     ███████╗╚██████╔╝██║  ██║██████╔╝
╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝ ╚═════╝ ╚═╝     ╚══════╝ ╚═════╝ ╚═╝  ╚═╝╚═════╝ 
kekupload-server
```

![](https://tokei.rs/b1/github/GamePowerX/kekupload-server)
![](https://tokei.rs/b1/github/GamePowerX/kekupload-server?category=blanks)
![](https://tokei.rs/b1/github/GamePowerX/kekupload-server?category=code)
![](https://tokei.rs/b1/github/GamePowerX/kekupload-server?category=comments)
![](https://tokei.rs/b1/github/GamePowerX/kekupload-server?category=files)

A backend providing a HTTP REST like interface for uploading files written in [rust](https://www.rust-lang.org/).

<br>

[API Documentation](https://gamepowerx.com/kekupload-server/docs/api/)

<br>

## License
This project is licensed under the [Mit License](https://mit-license.org/)

<hr>
<br>

## Features
1. Rest api
2. Chunked uploading
3. Embeds

<hr>
<br>

## Clients
- [kekupload-client client (svelte)](https://github.com/GamePowerX/kekupload-client)
- [KekUploadCLIClient (C#)](https://github.com/CraftingDragon007/KekUploadCLIClient)

<br>

## Libraries
- [kekupload-lib-ts (typescript)](https://github.com/GamePowerX/kekupload-lib-ts)
- [KekUploadLibrary (C#)](https://github.com/CraftingDragon007/KekUploadLibrary)

<br>

You have created your own client/library for [kekupload-server](https://gamepowerx.com/kekupload-server)? Great! Just submit an client request in the issues tab of github or write us an email at [info@gamepowerx.com](mailto:info@gamepowerx.com).

<hr>
<br>

## Usage

### Docker
Get a prebuilt image [here](https://github.com/GamePowerX/kekupload-server/pkgs/container/uploadserver)

<br>

or build it yourself:
```
docker build -t uploadserver:latest
```

<br>
<br>

**Running**

prebuilt:
```
sudo docker run -ti ghcr.io/kotwoss/uploadserver:main
```

selfbuilt:
```
sudo docker run -ti uploadserver:latest
```

<br>

### Prerequirements

- Rust Nightly <br>
You need [rustup](https://rustup.rs/) to run this.

```sh
rustup default nightly
```

<br>

### Configuration
Copy default.env to .env and change the settings in .env.

<br>

### Building
```sh
cargo build --release
```

The executable will be located at `target/release/uploadserver`

<br>

### Testing
If you are developing and don't want to rebuild and run the client to release mode use
```sh
cargo run
```

<hr>
<br>

## Goals

- Image compression

<br>

If you have aditional ideas how to make this tool better please create a feature request in the issues tab.

<hr>
<br>

## Contributing
More information [here](https://gamepowerx.com/kekupload-server/CONTRIBUTE).
