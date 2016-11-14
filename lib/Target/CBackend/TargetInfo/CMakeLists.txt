include_directories( ${CMAKE_CURRENT_BINARY_DIR}/.. ${CMAKE_CURRENT_SOURCE_DIR}/.. )

ADD_LIBRARY(LLVMCBackendInfo
  CBackendTargetInfo.cpp
  )
