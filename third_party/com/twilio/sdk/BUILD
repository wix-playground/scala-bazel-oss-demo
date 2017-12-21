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
    name = "twilio",
    jar = "@com_twilio_sdk_twilio//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/fasterxml/jackson/core:jackson_annotations",
        "//third_party/com/fasterxml/jackson/core:jackson_core",
        "//third_party/com/fasterxml/jackson/core:jackson_databind",
        "//third_party/com/google/guava",
        "//third_party/io/jsonwebtoken:jjwt",
        "//third_party/javax/xml/bind:jaxb_api",
        "//third_party/joda-time:joda_time",
        "//third_party/org/apache/httpcomponents:httpclient",
        "//third_party/org/apache/httpcomponents:httpcore",
    ],
)
