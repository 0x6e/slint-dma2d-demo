if (SLINT_BUILD_FROM_SOURCE)
    if (SLINT_TARGET_ARCHITECTURE)
        set(Rust_CARGO_TARGET ${SLINT_TARGET_ARCHITECTURE})
        message(STATUS "Setting Rust_CARGO_TARGET: ${Rust_CARGO_TARGET}")
    endif()

    set(CMAKE_BUILD_TYPE "MinSizeRel")
    set(BUILD_SHARED_LIBS OFF)
    set(SLINT_FEATURE_FREESTANDING ON)
    set(SLINT_FEATURE_RENDERER_SOFTWARE ON)
    set(DEFAULT_SLINT_EMBED_RESOURCES "embed-for-software-renderer")

    add_subdirectory(slint EXCLUDE_FROM_ALL)
endif()