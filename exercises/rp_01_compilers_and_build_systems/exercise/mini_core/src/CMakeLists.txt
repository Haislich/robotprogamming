# This comand defines a target for cmake
file(GLOB UTILSCPP "utils/*.cpp")
file(GLOB MESSAGESCPP "messages/*.cpp")
add_library(core_library SHARED
  ${UTILSCPP}
  ${MESSAGESCPP}
)
