load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "conversion.go",
        "doc.go",
        "generated.pb.go",
        "register.go",
        "types.go",
        "zz_generated.conversion.go",
        "zz_generated.deepcopy.go",
        "zz_generated.defaults.go",
        "zz_generated.prerelease-lifecycle.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/apiserver/pkg/apis/audit/v1alpha1",
    importpath = "k8s.io/apiserver/pkg/apis/audit/v1alpha1",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/gogo/protobuf/proto:go_default_library",
        "//vendor/github.com/gogo/protobuf/sortkeys:go_default_library",
        "//vendor/k8s.io/api/authentication/v1:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/conversion:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/runtime:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/runtime/schema:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/types:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/apis/audit:go_default_library",
    ],
)
