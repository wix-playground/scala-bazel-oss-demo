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
    name = "cglib_nodep",
    jar = "@cglib_cglib_nodep//jar:file",
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "cglib",
    jar = "@cglib_cglib//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/ant",
        "//third_party/org/ow2/asm",
    ],
)
