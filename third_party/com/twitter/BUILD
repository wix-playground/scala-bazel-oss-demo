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
    name = "util_function_2_11",
    jar = "@com_twitter_util_function_2_11//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "util_core_2_11",
    jar = "@com_twitter_util_core_2_11//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/twitter:util_function_2_11",
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/scala-lang:scala_reflect",
        "//third_party/org/scala-lang/modules:scala_parser_combinators_2_11",
    ],
)
