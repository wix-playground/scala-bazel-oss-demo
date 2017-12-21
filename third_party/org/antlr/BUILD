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
    name = "antlr",
    jar = "@org_antlr_antlr//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/antlr:antlr_runtime",
    ],
)

scala_import(
    name = "stringtemplate",
    jar = "@org_antlr_stringtemplate//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/antlr",
    ],
)

scala_import(
    name = "antlr_runtime",
    jar = "@org_antlr_antlr_runtime//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/antlr:stringtemplate",
    ],
)
