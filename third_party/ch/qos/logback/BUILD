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
    name = "logback_classic",
    jar = "@ch_qos_logback_logback_classic//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/ch/qos/logback:logback_core",
        "//third_party/org/slf4j:slf4j_api",
    ],
)

scala_import(
    name = "logback_core",
    jar = "@ch_qos_logback_logback_core//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)
