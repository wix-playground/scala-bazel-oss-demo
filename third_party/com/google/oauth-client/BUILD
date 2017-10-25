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
    name = "google_oauth_client_appengine",
    jar = "@com_google_oauth_client_google_oauth_client_appengine//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/http-client:google_http_client_appengine",
        "//third_party/com/google/oauth-client:google_oauth_client",
        "//third_party/com/google/oauth-client:google_oauth_client_servlet",
        "//third_party/javax/servlet:servlet_api",
    ],
)

scala_import(
    name = "google_oauth_client",
    jar = "@com_google_oauth_client_google_oauth_client//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/code/findbugs:jsr305",
        "//third_party/com/google/http-client:google_http_client",
    ],
)

scala_import(
    name = "google_oauth_client_servlet",
    jar = "@com_google_oauth_client_google_oauth_client_servlet//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/http-client:google_http_client_jdo",
        "//third_party/com/google/oauth-client:google_oauth_client",
        "//third_party/javax/jdo:jdo2_api",
        "//third_party/javax/servlet:servlet_api",
    ],
)
