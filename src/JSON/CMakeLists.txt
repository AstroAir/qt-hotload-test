set(SOURCES
    JSONUILoader.cpp
)

add_library(JSON
    ${SOURCES}
    JSONUILoader.hpp
    JSONParser.hpp
    JSONValidator.hpp
    ComponentRegistry.hpp
)
target_include_directories(JSON PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
