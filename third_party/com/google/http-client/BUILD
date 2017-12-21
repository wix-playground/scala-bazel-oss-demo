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
    name = "google_http_client_protobuf",
    jar = "@com_google_http_client_google_http_client_protobuf//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/http-client:google_http_client",
        "//third_party/com/google/protobuf:protobuf_java",
    ],
)

scala_import(
    name = "google_http_client_jackson",
    jar = "@com_google_http_client_google_http_client_jackson//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/http-client:google_http_client",
        "//third_party/org/codehaus/jackson:jackson_core_asl",
    ],
    # EXCLUDES com.google.guava:guava-jdk5
)

scala_import(
    name = "google_http_client_jdo",
    jar = "@com_google_http_client_google_http_client_jdo//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/http-client:google_http_client",
        "//third_party/javax/jdo:jdo2_api",
    ],
)

scala_import(
    name = "google_http_client_appengine",
    jar = "@com_google_http_client_google_http_client_appengine//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/http-client:google_http_client",
    ],
)

scala_import(
    name = "google_http_client_jackson2",
    jar = "@com_google_http_client_google_http_client_jackson2//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/fasterxml/jackson/core:jackson_core",
        "//third_party/com/google/http-client:google_http_client",
    ],
)

scala_import(
    name = "google_http_client",
    jar = "@com_google_http_client_google_http_client//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/code/findbugs:jsr305",
        "//third_party/org/apache/httpcomponents:httpclient",
    ],
)
