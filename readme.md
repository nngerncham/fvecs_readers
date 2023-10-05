# `fvecs` reader for Rust

I've been working with the SIFT1M data set and its siblings quite a lot recently but the way we read their `.fvecs` files are not the most straightforward. So, I've implemented this so that I don't have to rewrite/copy over the file reader every time I need to do something with that data set again.

## Quick Round-up of Functions(?)

- `load_fvecs`: It's basically the only function in this _thing_. It takes in the following parameters:
    - `file_name` specifies the path to the file as a string
    - `d` specifies the dimension of the vector data
    - `n` specifies how many vectors is in the data set

## Disclaimer

This library(?) isn't really written to be robust. Still, feel free to open issues or pull requests to change it!
