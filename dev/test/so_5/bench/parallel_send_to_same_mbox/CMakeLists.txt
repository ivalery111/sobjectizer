set(BENCHMARK _test.bench.so_5.parallel_send_to_same_mbox)
add_executable(${BENCHMARK} main.cpp)
target_link_libraries(${BENCHMARK} sobjectizer::SharedLib)
install(TARGETS ${BENCHMARK} DESTINATION bin)
