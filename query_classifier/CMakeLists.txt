add_library(query_classifier SHARED query_classifier.cc)
install(TARGETS query_classifier DESTINATION lib)
if(BUILD_TESTS)
  add_subdirectory(test)
endif()
