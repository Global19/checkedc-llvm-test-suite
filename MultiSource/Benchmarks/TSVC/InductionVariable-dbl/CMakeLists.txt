list(APPEND LDFLAGS -lm)
list(APPEND CFLAGS -std=gnu99)
set(RUN_OPTIONS 9100 14)
llvm_multisource(InductionVariable-dbl)
