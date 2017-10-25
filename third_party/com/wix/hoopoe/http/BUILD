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
    name = "http_testkit_2_11",
    jar = "@com_wix_hoopoe_http_http_testkit_2_11//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/io/spray:spray_client_2_11",
        "//third_party/org/scala-lang:scala_library",
    ],
)
