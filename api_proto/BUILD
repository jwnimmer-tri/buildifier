load("@io_bazel_rules_go//proto:go_proto_library.bzl", "go_proto_library")
load("//core:build_defs.bzl", "genfile_check_test")

genfile_check_test(
    src = "api.gen.pb.go",
    gen = "api.pb.go",
)

go_proto_library(
    name = "go_default_library",
    srcs = ["api.proto"],
    visibility = ["//visibility:public"],
)
