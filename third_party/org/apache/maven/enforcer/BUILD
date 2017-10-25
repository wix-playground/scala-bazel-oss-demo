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
    name = "enforcer_api",
    jar = "@org_apache_maven_enforcer_enforcer_api//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/maven:maven_plugin_api",
        "//third_party/org/codehaus/plexus:plexus_container_default",
    ],
)
