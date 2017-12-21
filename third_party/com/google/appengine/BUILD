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
    name = "appengine_jsr107cache",
    jar = "@com_google_appengine_appengine_jsr107cache//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "appengine_api_1_0_sdk",
    jar = "@com_google_appengine_appengine_api_1_0_sdk//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "appengine_endpoints",
    jar = "@com_google_appengine_appengine_endpoints//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/appengine:appengine_api_1_0_sdk",
    ],
)

scala_import(
    name = "appengine_api_labs",
    jar = "@com_google_appengine_appengine_api_labs//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)
