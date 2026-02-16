# ZMK config: Sofle Choc Wireless (rev.2) – modern user-config style

This repo is a **user-config** style ZMK configuration for **Sofle Choc Wireless rev.2**
using **nice!nano v2** controllers.

## What’s included
- `build.yaml` for GitHub Actions matrix builds
- A minimal `sofle.keymap`
- Split config (`sofle_left.conf` = central + Studio, `sofle_right.conf` = peripheral)
- Shield definitions under `config/boards/shields/sofle_choc/` derived from the upstream
  ZMK `sofle` shield used by the original db-ok config approach.

## Build targets
- `nice_nano_v2 + sofle_choc_left`
- `nice_nano_v2 + sofle_choc_right`
- `nice_nano_v2 + settings_reset`
