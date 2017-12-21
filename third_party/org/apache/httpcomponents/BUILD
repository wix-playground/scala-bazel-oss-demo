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
    name = "httpcore",
    jar = "@org_apache_httpcomponents_httpcore//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "httpmime",
    jar = "@org_apache_httpcomponents_httpmime//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/httpcomponents:httpclient",
    ],
)

scala_import(
    name = "httpclient",
    jar = "@org_apache_httpcomponents_httpclient//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/commons-codec:commons_codec",
        "//third_party/commons-logging:commons_logging",
        "//third_party/org/apache/httpcomponents:httpcore",
    ],
)
