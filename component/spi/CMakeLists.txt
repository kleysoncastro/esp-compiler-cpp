idf_component_register(SRCS "spi.cpp"
                    INCLUDE_DIRS "include")
target_include_directories(spi PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
