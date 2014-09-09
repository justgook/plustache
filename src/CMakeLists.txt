
# Submodule CMake integration (ie., not standalone)

include_directories(
  ${PROJECT_SOURCE_DIR}/plustache/include
)

set(plustache_srcs
  context.cpp
  template.cpp
)

add_library(plustache STATIC
  ${plustache_srcs}
)
