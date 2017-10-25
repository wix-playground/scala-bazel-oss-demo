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
    name = "woodstox_core_asl",
    jar = "@org_codehaus_woodstox_woodstox_core_asl//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/javax/xml/stream:stax_api",
        "//third_party/org/codehaus/woodstox:stax2_api",
    ],
)

scala_import(
    name = "stax2_api",
    jar = "@org_codehaus_woodstox_stax2_api//jar:file",
    runtime_deps = [
    ],
    deps = [
    ],
)
