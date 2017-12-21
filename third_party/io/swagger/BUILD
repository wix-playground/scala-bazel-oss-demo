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
    name = "swagger_models",
    jar = "@io_swagger_swagger_models//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/fasterxml/jackson/core:jackson_annotations",
        "//third_party/io/swagger:swagger_annotations",
        "//third_party/org/slf4j:slf4j_api",
    ],
)

scala_import(
    name = "swagger_annotations",
    jar = "@io_swagger_swagger_annotations//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)
