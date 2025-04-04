cmake_minimum_required(VERSION 3.10)
project(hello)  # 项目名称

# 设置 C++ 标准
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# 添加可执行文件
add_executable(${PROJECT_NAME} hello.cpp)  # 源文件列表

# 可选：添加库或依赖项
# target_link_libraries(${PROJECT_NAME} PRIVATE some_library)