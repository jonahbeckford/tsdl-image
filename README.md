Tsdl\_image — SDL2\_Image bindings for OCaml with Tsdl
------------------------------------------------------

Tsdl\_image provides bindings to
[SDL2_Image](https://www.libsdl.org/projects/SDL_image/) intended to
be used with [Tsdl](http://erratique.ch/software/tsdl).

It has as siblings [tsdl-mixer](https://github.com/sanette/tsdl-mixer)
and [tsdl-ttf](https://github.com/sanette/tsdl-ttf).

Note that these bindings are at an early stage and have only been used
minimally.  The interface may change.  Comments and bug reports are
welcome through the [github page](https://github.com/sanette/tsdl-image).

## Installation

Via [opam](https://opam.ocaml.org/):

    opam install tsdl-image

## Example

See [test/test.ml](https://github.com/sanette/tsdl-image/blob/master/test/test.ml)

## Documentation

Documentation is
[here](https://sanette.github.io/tsdl-image/Image/index.html). It can
be generated with `dune build @doc`, but the binding follows the
SDL2_image interface closely, so it may be sufficient to consult
[its documentation](https://www.libsdl.org/projects/SDL_image/docs/index.html).

Starting from version 0.3, the library is usable in a toplevel (with
`#require "tsdl-image"`).

## WARNING V0.3 Breaking change

Starting from 0.3, the library name is the same as the opam package
name `tsdl-image`. (The library name used to be `tsdl_image`, which
was confusing).

## CI

https://ci.ocamllabs.io/github/sanette/tsdl-image
