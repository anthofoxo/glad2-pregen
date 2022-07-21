# Glad2 Pregenerated Files
This repo is a small repo wiith branches will some pregenerated configurations of glad2.

## Branch naming
<api_version><core|compat>_<ext_args>

## ext_args
* y = all extensions
* n = no extensions
* c = noncore extensions
* p = remove EXT in favor of ARB (doesn't affect `EXT_texture_filter_anisotropic`)
For example: `EXT_direct_state_access` is removed since `ARB_direct_state_access` exists.

## Note
This is not gonna be fully accurate and branches may be updated or added in the future.