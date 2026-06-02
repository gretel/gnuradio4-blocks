add_ut_test(qa_BasicFileIo)
target_link_libraries(qa_BasicFileIo PRIVATE gr-fileio gr-basic gr-testing)
add_ut_test(qa_WavFile)
target_link_libraries(qa_WavFile PRIVATE gr-fileio gr-testing httplib::httplib)
