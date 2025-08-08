add_executable(
  main
  main.cpp
)

target_link_libraries(
    main
    PRIVATE
    HPX::hpx
    HPX::wrap_main
    HPX::iostreams_component
)
