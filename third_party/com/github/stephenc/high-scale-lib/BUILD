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
    name = "high_scale_lib",
    jar = "@com_github_stephenc_high_scale_lib_high_scale_lib//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)
