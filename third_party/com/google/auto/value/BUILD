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
    name = "auto_value",
    jar = "@com_google_auto_value_auto_value//jar:file",
    runtime_deps = [
    ],
    deps = [
    ],
    # EXCLUDES com.google.guava:guava-jdk5
)
