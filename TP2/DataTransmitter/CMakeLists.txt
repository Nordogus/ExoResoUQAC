﻿# CMakeList.txt : projet CMake pour DataTransmitter, incluez la source et définissez
# la logique spécifique au projet ici.
#
cmake_minimum_required (VERSION 3.8)

set(CMAKE_CXX_STANDARD 17)

project ("DataTransmitter")

# Ajoutez une source à l'exécutable de ce projet.
add_executable (DataTransmitter "Serializer.h" "Serializer.cpp" "DataTransmitter.cpp" "DataTransmitter.h"  "framework.h" "Player.h"  "Player.cpp" "Deserializer.cpp" "Deserializer.h" "Vector3.h" "Quaternion.h")

# TODO: Ajoutez des tests et installez des cibles si nécessaire.
