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
    name = "ant",
    jar = "@org_apache_ant_ant//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/ant:ant_launcher",
    ],
)

scala_import(
    name = "ant_launcher",
    jar = "@org_apache_ant_ant_launcher//jar:file",
    runtime_deps = [
    ],
    deps = [
    ],
)
