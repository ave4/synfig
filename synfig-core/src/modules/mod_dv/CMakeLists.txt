add_library(mod_dv MODULE "")

target_sources(mod_dv
    PUBLIC
        "${CMAKE_CURRENT_LIST_DIR}/main.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/trgt_dv.cpp"
)

install (
    TARGETS mod_dv
    DESTINATION lib/synfig/modules
)
