package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_library",
    "go_test",
)

go_library(
    name = "go_default_library",
    srcs = ["checks.go"],
    tags = ["automanaged"],
)

go_test(
    name = "go_default_test",
    srcs = ["checks_test.go"],
    library = ":go_default_library",
    tags = ["automanaged"],
    deps = ["//vendor/k8s.io/apimachinery/pkg/util/wait:go_default_library"],
)
