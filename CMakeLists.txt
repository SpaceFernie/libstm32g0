file(GLOB FILES *.c *.h)

add_library(libstm32g0 ${FILES})

target_include_directories(libstm32g0 PUBLIC ../src/)
