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
    name = "scalatest_2_11",
    jar = "@org_scalatest_scalatest_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/scala-lang:scala_reflect",
        "//third_party/org/scala-lang/modules:scala_xml_2_11",
    ],
)
