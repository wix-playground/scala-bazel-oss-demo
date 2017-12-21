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
    name = "lucene_core",
    jar = "@org_apache_lucene_lucene_core//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "lucene_spatial",
    jar = "@org_apache_lucene_lucene_spatial//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/spatial4j",
        "//third_party/org/apache/lucene:lucene_core",
        "//third_party/org/apache/lucene:lucene_queries",
    ],
)

scala_import(
    name = "lucene_queries",
    jar = "@org_apache_lucene_lucene_queries//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/lucene:lucene_core",
    ],
)

scala_import(
    name = "lucene_grouping",
    jar = "@org_apache_lucene_lucene_grouping//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/lucene:lucene_core",
        "//third_party/org/apache/lucene:lucene_queries",
    ],
)

scala_import(
    name = "lucene_misc",
    jar = "@org_apache_lucene_lucene_misc//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/lucene:lucene_core",
    ],
)

scala_import(
    name = "lucene_queryparser",
    jar = "@org_apache_lucene_lucene_queryparser//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/lucene:lucene_core",
        "//third_party/org/apache/lucene:lucene_queries",
        "//third_party/org/apache/lucene:lucene_sandbox",
    ],
)

scala_import(
    name = "lucene_highlighter",
    jar = "@org_apache_lucene_lucene_highlighter//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/lucene:lucene_core",
        "//third_party/org/apache/lucene:lucene_memory",
        "//third_party/org/apache/lucene:lucene_queries",
    ],
)

scala_import(
    name = "lucene_suggest",
    jar = "@org_apache_lucene_lucene_suggest//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/lucene:lucene_analyzers_common",
        "//third_party/org/apache/lucene:lucene_core",
        "//third_party/org/apache/lucene:lucene_misc",
        "//third_party/org/apache/lucene:lucene_queries",
    ],
)

scala_import(
    name = "lucene_codecs",
    jar = "@org_apache_lucene_lucene_codecs//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/lucene:lucene_core",
    ],
)

scala_import(
    name = "lucene_memory",
    jar = "@org_apache_lucene_lucene_memory//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/lucene:lucene_core",
    ],
)

scala_import(
    name = "lucene_analyzers_common",
    jar = "@org_apache_lucene_lucene_analyzers_common//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/lucene:lucene_core",
    ],
)

scala_import(
    name = "lucene_sandbox",
    jar = "@org_apache_lucene_lucene_sandbox//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/lucene:lucene_core",
    ],
    # EXCLUDES jakarta-regexp:jakarta-regexp
)

scala_import(
    name = "lucene_join",
    jar = "@org_apache_lucene_lucene_join//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/lucene:lucene_core",
        "//third_party/org/apache/lucene:lucene_grouping",
    ],
)
