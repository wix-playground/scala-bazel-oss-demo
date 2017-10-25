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
    name = "spring_plugin_core",
    jar = "@org_springframework_plugin_spring_plugin_core//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/slf4j:slf4j_api",
        "//third_party/org/springframework:spring_aop",
        "//third_party/org/springframework:spring_beans",
        "//third_party/org/springframework:spring_context",
    ],
)

scala_import(
    name = "spring_plugin_metadata",
    jar = "@org_springframework_plugin_spring_plugin_metadata//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/slf4j:slf4j_api",
        "//third_party/org/springframework/plugin:spring_plugin_core",
    ],
)
