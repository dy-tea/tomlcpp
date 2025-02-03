project(
  'tomlcpp',
  'cpp',
  'c'
)

include = include_directories('.')

tomlcpp_lib = static_library(
  'tomlcpp',
  sources: [
    'toml.c',
    'tomlcpp.cpp',
  ],
  include_directories: include
)

tomlcpp_dep = declare_dependency(
  link_with: tomlcpp_lib,
  include_directories: include
)