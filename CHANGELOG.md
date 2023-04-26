# v6.0
- print time-elapsed stats when done
- replace cursed regex
- drop `kernelcleaner` as it was basically just a crappy `eclean-kernel` wrapper

# v5.0
- default to no clean
- enable clean with explicit `--clean` or `--mrproper`

# v4.0
- add `--skip-clean` option
- add `--version`
- fix menuconfig default

# v3.0
- add `--verbose` option
- allow choosing config tool via `--config-tool`

# v2.0
- Allow passing different flags to the build process.
  These include {CPP,A,C,RUST}FLAGS and 
  a general `--makeopts` switch
- show rustc path

# v1.1
- Supported terminals now display status in the title

# v1.0
- Initial release
