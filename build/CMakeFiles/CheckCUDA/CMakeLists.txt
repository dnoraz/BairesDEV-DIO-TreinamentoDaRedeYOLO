cmake_minimum_required(VERSION 3.31.2)
set(CMAKE_MODULE_PATH "C:/DIO/YOLOv3/darknet/cmake/Modules/")
project(CheckCUDA CUDA)
file(WRITE "${CMAKE_CURRENT_BINARY_DIR}/result.cmake"
  "set(CMAKE_CUDA_COMPILER \"${CMAKE_CUDA_COMPILER}\")\n"
  
  )