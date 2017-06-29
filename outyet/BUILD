load("@io_bazel_rules_go//go:def.bzl", "go_binary", "go_test", "go_library")

go_library(
    name = "outyetlib",
    srcs = ["main.go"],
)
    
go_binary(
    name = "outyet",
    library = ":outyetlib",
    visibility = ["//visibility:public"],
)


go_test(
    name = "outyet_test",
    srcs = ["main_test.go"],
    library = ":outyetlib",
)
