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
    name = "wiremock",
    jar = "@com_github_tomakehurst_wiremock//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/fasterxml/jackson/core:jackson_annotations",
        "//third_party/com/fasterxml/jackson/core:jackson_core",
        "//third_party/com/fasterxml/jackson/core:jackson_databind",
        "//third_party/com/google/guava",
        "//third_party/com/jayway/jsonpath:json_path",
        "//third_party/net/sf/jopt-simple:jopt_simple",
        "//third_party/org/apache/httpcomponents:httpclient",
        "//third_party/org/mortbay/jetty",
        "//third_party/org/skyscreamer:jsonassert",
        "//third_party/org/slf4j:slf4j_api",
        "//third_party/xmlunit",
    ],
)
