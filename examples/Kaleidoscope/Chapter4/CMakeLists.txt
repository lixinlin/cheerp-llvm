set(LLVM_LINK_COMPONENTS
  Analysis
  Core
  ExecutionEngine
  InstCombine
  MC
  ScalarOpts
  Support
  native
  mcjit
  )

add_kaleidoscope_chapter(Kaleidoscope-Ch4
  toy.cpp
  )
