ament_add_gtest(vtest velocity_iterator_test.cpp)

ament_add_gtest(twist_gen_test twist_gen.cpp)
target_link_libraries(twist_gen_test standard_traj_generator)
