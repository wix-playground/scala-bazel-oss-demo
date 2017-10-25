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
    name = "joda_time",
    jar = "@joda_time_joda_time//jar:file",
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "joda_time_hibernate",
    jar = "@joda_time_joda_time_hibernate//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/joda-time:joda_time",
        "//third_party/org/hibernate",
    ],
)
