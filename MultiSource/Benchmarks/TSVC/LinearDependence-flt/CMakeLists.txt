list(APPEND LDFLAGS -lm)
list(APPEND CFLAGS -std=gnu99)
set(RUN_OPTIONS 3570 5)
llvm_multisource(LinearDependence-flt)
