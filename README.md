# dear imgui wgpu-rs renderer

> This is a fork of [https://github.com/Yatekii/imgui-wgpu-rs](Yatekii/imgui-wgpu-rs) to support
> the latest version of wgpu and imgui.

Draw dear imgui UIs as a wgpu render pass. Based on [imgui-gfx-renderer](https://github.com/Gekkio/imgui-rs/tree/master/imgui-gfx-renderer) from [imgui-rs](https://github.com/Gekkio/imgui-rs).

![screenshot](doc/img/screenshot.png)

# Usage

For usage, please have a look at the [example](examples/hello-world.rs).

# Example

Run the example with
```
cargo run --release --example hello-world
```

# Status

Supports version 0.20 of wgpu and the latest GitHub version of imgui.

Contributions are very welcome.
