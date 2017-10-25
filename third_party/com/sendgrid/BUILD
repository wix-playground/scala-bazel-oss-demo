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
    name = "sendgrid_java",
    jar = "@com_sendgrid_sendgrid_java//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/fasterxml/jackson/core:jackson_annotations",
        "//third_party/com/fasterxml/jackson/core:jackson_core",
        "//third_party/com/fasterxml/jackson/core:jackson_databind",
        "//third_party/com/sendgrid:java_http_client",
    ],
)

scala_import(
    name = "java_http_client",
    jar = "@com_sendgrid_java_http_client//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/httpcomponents:httpclient",
        "//third_party/org/apache/httpcomponents:httpcore",
        "//third_party/org/mockito:mockito_core",
    ],
)
