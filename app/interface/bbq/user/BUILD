filegroup(
    name = "package-srcs",
    srcs = glob(["**"]),
    tags = ["automanaged"],
    visibility = ["//visibility:private"],
)

filegroup(
    name = "all-srcs",
    srcs = [
        ":package-srcs",
        "//app/interface/bbq/user/cmd:all-srcs",
        "//app/interface/bbq/user/internal/dao:all-srcs",
        "//app/interface/bbq/user/internal/model:all-srcs",
        "//app/interface/bbq/user/internal/server/http:all-srcs",
        "//app/interface/bbq/user/internal/service:all-srcs",
    ],
    tags = ["automanaged"],
    visibility = ["//visibility:public"],
)
