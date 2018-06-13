licenses(["notice"])

exports_files(["LICENSE.txt"])

package(default_visibility = ["//visibility:public"])

cc_library(
  name = "nanopb",
  visibility = ["//visibility:public"],
  hdrs = [
    "pb.h",
    "pb_common.h",
    "pb_decode.h",
    "pb_encode.h",
  ],
  srcs = [
    "pb_common.c",
    "pb_decode.c",
    "pb_encode.c",
  ],
)

filegroup(
  name = 'headers',
  srcs = [
    "pb.h",
    "pb_common.h",
    "pb_decode.h",
    "pb_encode.h",
  ],
)

filegroup(
  name = 'sources',
  srcs = [
    "pb_common.c",
    "pb_decode.c",
    "pb_encode.c",
  ],
)

filegroup(
  name = 'generator_files',
  srcs = glob([
    'generator/**',
  ])
)
