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
    name = "google_auth_library_oauth2_http",
    jar = "@com_google_auth_google_auth_library_oauth2_http//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/auth:google_auth_library_credentials",
        "//third_party/com/google/guava",
        "//third_party/com/google/http-client:google_http_client",
        "//third_party/com/google/http-client:google_http_client_jackson2",
    ],
    # EXCLUDES com.google.guava:guava-jdk5
)

scala_import(
    name = "google_auth_library_credentials",
    jar = "@com_google_auth_google_auth_library_credentials//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)
