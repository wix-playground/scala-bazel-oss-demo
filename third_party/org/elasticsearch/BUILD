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
    name = "elasticsearch",
    jar = "@org_elasticsearch_elasticsearch//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/lucene:lucene_analyzers_common",
        "//third_party/org/apache/lucene:lucene_codecs",
        "//third_party/org/apache/lucene:lucene_core",
        "//third_party/org/apache/lucene:lucene_grouping",
        "//third_party/org/apache/lucene:lucene_highlighter",
        "//third_party/org/apache/lucene:lucene_join",
        "//third_party/org/apache/lucene:lucene_memory",
        "//third_party/org/apache/lucene:lucene_misc",
        "//third_party/org/apache/lucene:lucene_queries",
        "//third_party/org/apache/lucene:lucene_queryparser",
        "//third_party/org/apache/lucene:lucene_sandbox",
        "//third_party/org/apache/lucene:lucene_spatial",
        "//third_party/org/apache/lucene:lucene_suggest",
    ],
)
