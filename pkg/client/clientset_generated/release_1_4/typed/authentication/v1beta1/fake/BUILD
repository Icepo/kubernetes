package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_binary",
    "go_library",
    "go_test",
    "cgo_library",
)

go_library(
    name = "go_default_library",
    srcs = [
        "doc.go",
        "fake_authentication_client.go",
        "fake_tokenreview.go",
    ],
    tags = ["automanaged"],
    deps = [
        "//pkg/client/clientset_generated/release_1_4/typed/authentication/v1beta1:go_default_library",
        "//pkg/client/restclient:go_default_library",
        "//pkg/client/testing/core:go_default_library",
    ],
)
