﻿# CMakeList.txt: projekt CMake dla elementu Jenkins_PROST, dołącz źródło i zdefiniuj
# tutaj logikę specyficzną dla projektu.
#
cmake_minimum_required (VERSION 3.8)

project ("Jenkins_PROST")

# Dodaj źródło do pliku wykonywalnego tego projektu.
add_executable (Jenkins_PROST "Jenkins_PROST.cpp" "Jenkins_PROST.h")

# TODO: Dodaj testy i zainstaluj elementy docelowe w razie potrzeby.
