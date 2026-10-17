# Third-party notices (this fork)

## gpui-liquid-glass

The Liquid Glass shading in `crates/gpui_macos/src/shaders.metal` (`shade_liquid_glass`)
and the material parameters in `crates/gpui/src/window.rs` (`Window::paint_liquid_glass`)
are ported from [gpui-liquid-glass](https://github.com/1234igor/gpui-liquid-glass) by
1234igor: rounded-rect SDF normals, edge lensing, light and dark rims and the inner glow.
Its project code is under the MIT License:

> MIT License
>
> Copyright (c) 2026 1234igor
>
> Permission is hereby granted, free of charge, to any person obtaining a copy of this
> software and associated documentation files (the "Software"), to deal in the Software
> without restriction, including without limitation the rights to use, copy, modify,
> merge, publish, distribute, sublicense, and/or sell copies of the Software, and to
> permit persons to whom the Software is furnished to do so, subject to the following
> conditions:
>
> The above copyright notice and this permission notice shall be included in all copies
> or substantial portions of the Software.
>
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED,
> INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A
> PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
> HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF
> CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR
> THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Its shaders live in that project's modified copy of GPUI, which is Apache-2.0 (as is
GPUI here; see LICENSE-APACHE).
