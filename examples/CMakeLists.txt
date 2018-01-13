# Copyright (c) 2018 Jean-Louis Leroy
# Distributed under the Boost Software License, Version 1.0.
# See accompanying file LICENSE_1_0.txt
# or copy at http://www.boost.org/LICENSE_1_0.txt)

add_executable(synopsis synopsis.cpp)
target_link_libraries (synopsis yomm2)
add_test (synopsis synopsis)

add_executable(matrix matrix.cpp)
target_link_libraries (matrix yomm2)
add_test (matrix matrix)