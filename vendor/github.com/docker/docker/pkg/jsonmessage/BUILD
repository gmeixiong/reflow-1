load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["jsonmessage.go"],
    importmap = "grail/go/src/vendor/github.com/docker/docker/pkg/jsonmessage",
    importpath = "github.com/docker/docker/pkg/jsonmessage",
    visibility = ["//visibility:public"],
    deps = [
        "//go/src/vendor/github.com/docker/docker/pkg/jsonlog:go_default_library",
        "//go/src/vendor/github.com/docker/docker/pkg/term:go_default_library",
        "//go/src/vendor/github.com/docker/go-units:go_default_library",
    ],
)
