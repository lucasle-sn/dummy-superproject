add_executable(dummy-exe
  src/main.cc
)
target_link_libraries(dummy-exe PRIVATE dummy-lib)
