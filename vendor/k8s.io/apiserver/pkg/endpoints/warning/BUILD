load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["warning.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/apiserver/pkg/endpoints/warning",
    importpath = "k8s.io/apiserver/pkg/endpoints/warning",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/emicklei/go-restful:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/warning:go_default_library",
    ],
)
