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
    name = "google_maps_services",
    jar = "@com_google_maps_google_maps_services//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/code/gson",
        "//third_party/com/squareup/okhttp3:okhttp",
        "//third_party/joda-time:joda_time",
        "//third_party/org/slf4j:slf4j_api",
    ],
)
