set(TARGET_NAME OpenfoldersBaseProject)

find_package(fmt CONFIG REQUIRED)

add_executable( ${TARGET_NAME} )

target_include_directories( ${TARGET_NAME}
    PUBLIC
        ${CMAKE_CURRENT_SOURCE_DIR}
)

file( GLOB_RECURSE TARGET_SOURCES CONFIGURE_DEPENDS *.cpp *.hpp *.h )

target_sources( ${TARGET_NAME} 
    PRIVATE 
        ${TARGET_SOURCES}
)

target_link_libraries( ${TARGET_NAME}
    PUBLIC
        fmt::fmt
)
