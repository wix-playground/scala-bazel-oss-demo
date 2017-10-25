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
    name = "json_path",
    jar = "@com_jayway_jsonpath_json_path//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/commons-lang:commons_lang",
        "//third_party/net/minidev:json_smart",
    ],
)
