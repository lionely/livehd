#  This file is distributed under the BSD 3-Clause License. See LICENSE for details.
cc_library(
    name = "simlib",
    srcs = glob(["*.cpp"],exclude=["*test*.cpp"]),
    hdrs = glob(["*.hpp"]),
    visibility = ["//visibility:public"],
    includes = ["."],
    deps = [
        "@iassert//:iassert",
        ],
    )

cc_library(
    name = "headers",
    hdrs = glob(["*.hpp"]),
    visibility = ["//visibility:public"],
    includes = ["."],
)

