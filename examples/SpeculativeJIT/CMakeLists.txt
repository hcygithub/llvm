set(LLVM_LINK_COMPONENTS
  Core
  IRReader
  OrcJIT
  ExecutionEngine
  Support
  nativecodegen
  Analysis
  Passes
  )

add_llvm_example(SpeculativeJIT
  SpeculativeJIT.cpp
  )
