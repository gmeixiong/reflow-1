load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "common.go",
        "container.go",
        "network.go",
        "node.go",
        "secret.go",
        "service.go",
        "swarm.go",
        "task.go",
    ],
    importmap = "grail/go/src/vendor/github.com/docker/docker/api/types/swarm",
    importpath = "github.com/docker/docker/api/types/swarm",
    visibility = ["//visibility:public"],
    deps = [
        "//go/src/vendor/github.com/docker/docker/api/types/container:go_default_library",
        "//go/src/vendor/github.com/docker/docker/api/types/mount:go_default_library",
    ],
)
