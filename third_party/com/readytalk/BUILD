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
    name = "metrics3_statsd",
    jar = "@com_readytalk_metrics3_statsd//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/readytalk:metrics_statsd_common",
        "//third_party/org/slf4j:slf4j_api",
    ],
)

scala_import(
    name = "metrics_statsd_common",
    jar = "@com_readytalk_metrics_statsd_common//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/slf4j:slf4j_api",
    ],
)
