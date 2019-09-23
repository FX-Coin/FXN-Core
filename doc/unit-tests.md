Compiling/running unit tests
------------------------------------

Unit tests will be automatically compiled if dependencies were met in configure
and tests weren't explicitly disabled.

After configuring, they can be run with 'make check'.

To run the fxnd tests manually, launch src/test/test_fxn .

To add more fxnd tests, add `BOOST_AUTO_TEST_CASE` functions to the existing
.cpp files in the test/ directory or add new .cpp files that
implement new BOOST_AUTO_TEST_SUITE sections.

To run the fxn-qt tests manually, launch src/qt/test/fxn-qt_test

To add more fxn-qt tests, add them to the `src/qt/test/` directory and
the `src/qt/test/test_main.cpp` file.
