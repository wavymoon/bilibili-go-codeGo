package(default_visibility = ["//visibility:public"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_library",
)

go_library(
    name = "go_default_library",
    srcs = [
        "contribute.go",
        "mine.go",
        "space.go",
    ],
    importpath = "go-common/app/interface/main/app-interface/model/space",
    tags = ["automanaged"],
    visibility = ["//visibility:public"],
    deps = [
        "//app/interface/main/app-interface/model:go_default_library",
        "//app/interface/main/app-interface/model/audio:go_default_library",
        "//app/interface/main/app-interface/model/bangumi:go_default_library",
        "//app/interface/main/app-interface/model/bplus:go_default_library",
        "//app/interface/main/app-interface/model/community:go_default_library",
        "//app/interface/main/app-interface/model/elec:go_default_library",
        "//app/interface/main/app-interface/model/favorite:go_default_library",
        "//app/interface/main/tag/model:go_default_library",
        "//app/interface/openplatform/article/model:go_default_library",
        "//app/service/main/account/api:go_default_library",
        "//app/service/main/account/model:go_default_library",
        "//app/service/main/archive/api:go_default_library",
        "//library/time:go_default_library",
    ],
)

filegroup(
    name = "package-srcs",
    srcs = glob(["**"]),
    tags = ["automanaged"],
    visibility = ["//visibility:private"],
)

filegroup(
    name = "all-srcs",
    srcs = [":package-srcs"],
    tags = ["automanaged"],
    visibility = ["//visibility:public"],
)
