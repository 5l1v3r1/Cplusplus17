set(target hex)
set(src hex.cpp)

add_executable(${target} ${src})

target_compile_options(${target} PUBLIC ${DEFAULT_COMPILE_OPTIONS})