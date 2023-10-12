# atomic-tests
Small (atomic-size) C unit tests CMake facility utilising [`cmocka`](https://cmocka.org/) test library.

## How to use it
Just include this test facility directory in your project and enjoy cmocka functionality.

```cmake
include(${CMAKE_CURRENT_LIST_DIR}/<path to atomic-tests>/cmake/atomic-tests.cmake)

atomic_tests_add(<test_name> ${CMAKE_CURRENT_SOURCE_DIR}/<test_source>.c <tested_library>)
```
## Copyright
This library was written by G2Labs Grzegorz Grzęda, and is distributed under MIT Licence. Check the `LICENSE` file for
more details.