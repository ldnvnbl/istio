package(default_visibility = ["//visibility:public"])

load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["spyadapter.go"],
    deps = [
        "//mixer/pkg/adapter:go_default_library",
        "//mixer/test/template/report:go_default_library",
        "@com_github_gogo_protobuf//types:go_default_library",
    ],
)
