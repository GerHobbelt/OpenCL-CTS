set(MODULE_NAME COMMONFNS)

set(${MODULE_NAME}_SOURCES
    main.cpp
    test_clamp.cpp
    test_unary_fn.cpp
    test_mix.cpp
    test_step.cpp
    test_smoothstep.cpp
    test_binary_fn.cpp
)

set_gnulike_module_compile_flags("-Wno-format")

include(../CMakeCommon.txt)
