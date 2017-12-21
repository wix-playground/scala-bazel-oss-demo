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
    name = "javassist",
    jar = "@org_javassist_javassist//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)
