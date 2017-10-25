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
    name = "google_api_client_servlet",
    jar = "@com_google_api_client_google_api_client_servlet//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/api-client:google_api_client",
        "//third_party/com/google/oauth-client:google_oauth_client_servlet",
        "//third_party/javax/jdo:jdo2_api",
        "//third_party/javax/servlet:servlet_api",
    ],
)

scala_import(
    name = "google_api_client_appengine",
    jar = "@com_google_api_client_google_api_client_appengine//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/api-client:google_api_client",
        "//third_party/com/google/api-client:google_api_client_servlet",
        "//third_party/com/google/http-client:google_http_client_appengine",
        "//third_party/com/google/oauth-client:google_oauth_client_appengine",
    ],
    # EXCLUDES com.google.guava:guava-jdk5
)

scala_import(
    name = "google_api_client",
    jar = "@com_google_api_client_google_api_client//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/http-client:google_http_client_jackson2",
        "//third_party/com/google/oauth-client:google_oauth_client",
    ],
)
