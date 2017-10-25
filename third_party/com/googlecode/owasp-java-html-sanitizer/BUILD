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
    name = "owasp_java_html_sanitizer",
    jar = "@com_googlecode_owasp_java_html_sanitizer_owasp_java_html_sanitizer//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/guava",
        "//third_party/commons-codec:commons_codec",
    ],
)
