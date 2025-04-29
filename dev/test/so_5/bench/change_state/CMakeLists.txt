set(BENCHMARK _test.bench.so_5.change_state)
add_executable(${BENCHMARK} main.cpp)
target_link_libraries(${BENCHMARK} sobjectizer::SharedLib)
install(TARGETS ${BENCHMARK} DESTINATION bin)
