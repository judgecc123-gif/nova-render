project (render)
add_library(render STATIC render.cpp)

target_include_directories(
    render
    PUBLIC ./
)

target_link_libraries(render PUBLIC common) 