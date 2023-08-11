load("@rules_cc//cc:defs.bzl", "cc_binary", "cc_library")
load("//:new_rule.bzl","write_new_file")

write_new_file(
  name = "write_new_file_test",
)
cc_library(
  name = "lib",
  srcs = ["lib.cpp"],
  hdrs = ["lib.h"],
)


cc_binary(
  name = "main",
  srcs = ["main.cpp"],
  deps = [
    ":lib"
  ],
)
