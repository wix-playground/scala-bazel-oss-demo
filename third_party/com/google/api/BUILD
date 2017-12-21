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
    name = "api_common",
    jar = "@com_google_api_api_common//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/auto/value:auto_value",
        "//third_party/com/google/code/findbugs:jsr305",
        "//third_party/com/google/guava",
        "//third_party/com/google/inject:guice",
        "//third_party/joda-time:joda_time",
    ],
)

scala_import(
    name = "gax",
    jar = "@com_google_api_gax//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/api/grpc:grpc_google_common_protos",
        "//third_party/com/google/auth:google_auth_library_oauth2_http",
        "//third_party/com/google/auto/value:auto_value",
        "//third_party/com/google/code/findbugs:jsr305",
        "//third_party/com/google/guava",
        "//third_party/com/google/inject:guice",
        "//third_party/joda-time:joda_time",
    ],
    # EXCLUDES io.grpc:grpc-all
)
