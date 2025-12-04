add_library(ripser-static STATIC
    ripser.cpp
)

target_include_directories(ripser-static
    PUBLIC
        ${CMAKE_CURRENT_SOURCE_DIR}
)

target_compile_features(ripser-static PUBLIC cxx_std_11)
