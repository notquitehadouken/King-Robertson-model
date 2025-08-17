cmake_minimum_required(VERSION 3.30)
project(KingRobertsonModel CUDA)

set(CMAKE_CUDA_STANDARD 20)

add_executable(KingRobertsonModel main.cu)

set_target_properties(KingRobertsonModel PROPERTIES
                      CUDA_SEPARABLE_COMPILATION ON)
