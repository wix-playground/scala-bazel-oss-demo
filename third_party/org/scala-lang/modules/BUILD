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
    name = "scala_java8_compat_2_11",
    jar = "@org_scala_lang_modules_scala_java8_compat_2_11//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "scala_xml_2_11",
    jar = "@org_scala_lang_modules_scala_xml_2_11//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "scala_parser_combinators_2_11",
    jar = "@org_scala_lang_modules_scala_parser_combinators_2_11//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_library",
    ],
)
