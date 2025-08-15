# hpack-common

Nifty common hpack configuration for Haskell projects

## Usage

- Add this repo as Git submodule
- Import in your `package.yaml` file:
  ```yaml
  defaults:
    - local: ./hpack-common/defaults/main.yaml
    - local: ./hpack-common/defaults/relude.yaml
  ```
