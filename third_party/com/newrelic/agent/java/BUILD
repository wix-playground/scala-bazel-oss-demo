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
    name = "newrelic_api",
    jar = "@com_newrelic_agent_java_newrelic_api//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "newrelic_agent",
    jar = "@com_newrelic_agent_java_newrelic_agent//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)
