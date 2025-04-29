set(BENCHMARK _test.bench.so_5.many_mboxes)
add_executable(${BENCHMARK} main.cpp)
target_link_libraries(${BENCHMARK} sobjectizer::SharedLib)
install(TARGETS ${BENCHMARK} DESTINATION bin)
