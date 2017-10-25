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
    name = "google_api_services_dns",
    jar = "@com_google_apis_google_api_services_dns//jar:file",
    runtime_deps = [
    ],
    deps = [
    ],
    # EXCLUDES com.google.guava:guava-jdk5
    # EXCLUDES com.google.api-client:google-api-client
)

scala_import(
    name = "google_api_services_compute",
    jar = "@com_google_apis_google_api_services_compute//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/api-client:google_api_client",
    ],
    # EXCLUDES com.google.guava:guava-jdk5
)

scala_import(
    name = "google_api_services_translate",
    jar = "@com_google_apis_google_api_services_translate//jar:file",
    runtime_deps = [
    ],
    deps = [
    ],
    # EXCLUDES com.google.guava:guava-jdk5
    # EXCLUDES com.google.api-client:google-api-client
)

scala_import(
    name = "google_api_services_cloudresourcemanager",
    jar = "@com_google_apis_google_api_services_cloudresourcemanager//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/api-client:google_api_client",
    ],
    # EXCLUDES com.google.guava:guava-jdk5
)

scala_import(
    name = "google_api_services_storage",
    jar = "@com_google_apis_google_api_services_storage//jar:file",
    runtime_deps = [
    ],
    deps = [
    ],
    # EXCLUDES com.google.guava:guava-jdk5
    # EXCLUDES com.google.api-client:google-api-client
)

scala_import(
    name = "google_api_services_bigquery",
    jar = "@com_google_apis_google_api_services_bigquery//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/api-client:google_api_client",
    ],
    # EXCLUDES com.google.guava:guava-jdk5
)
