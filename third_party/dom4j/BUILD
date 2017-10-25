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
    name = "dom4j",
    jar = "@dom4j_dom4j//jar:file",
    runtime_deps = [
    ],
    deps = [
    ],
    # EXCLUDES msv:relaxngDatatype
    # EXCLUDES pull-parser:pull-parser
    # EXCLUDES stax:stax-ri
    # EXCLUDES xalan:xalan
    # EXCLUDES stax:stax-api
    # EXCLUDES xpp3:xpp3
    # EXCLUDES jaxme:jaxme-api
    # EXCLUDES xml-apis:xml-apis
    # EXCLUDES jaxen:jaxen
    # EXCLUDES junitperf:junitperf
    # EXCLUDES msv:xsdlib
)
