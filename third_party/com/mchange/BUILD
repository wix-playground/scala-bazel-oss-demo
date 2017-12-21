licenses(["reciprocal"])

package(default_visibility = ["//visibility:public"])

load(
    "@io_bazel_rules_scala//scala:scala.bzl",
    "scala_binary",
    "scala_library",
    "scala_test",
    "scala_macro_library",
    "scala_specs2_junit_test",
)
load("//third_party:scala_import.bzl", "scala_import")

scala_import(
    name = "c3p0",
    jar = "@com_mchange_c3p0//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/mchange:mchange_commons_java",
    ],
)

scala_import(
    name = "mchange_commons_java",
    jar = "@com_mchange_mchange_commons_java//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)
