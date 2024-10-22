cmake_minimum_required(VERSION 3.25 FATAL_ERROR)

# Определить проект
project(ImageSteganography)

# Подключить модули
add_subdirectory(modules/BuildToolkit)

# Подключить исходники
add_subdirectory(src)
