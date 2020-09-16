# evio-gnbuild

gn gen out/test1 --args='enable_iterator_debugging=false is_debug=false use_lld=true target_sysroot_dir="/path/to/external/sysroot"'
ninja -C out/rel tincan
