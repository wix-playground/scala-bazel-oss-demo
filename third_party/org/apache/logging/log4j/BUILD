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
    name = "log4j_core",
    jar = "@org_apache_logging_log4j_log4j_core//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/logging/log4j:log4j_api",
    ],
)

scala_import(
    name = "log4j_api",
    jar = "@org_apache_logging_log4j_log4j_api//jar:file",
    runtime_deps = [
    ],
    deps = [
    ],
)
