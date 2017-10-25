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
    name = "protobuf_java_util",
    jar = "@com_google_protobuf_protobuf_java_util//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/code/gson",
        "//third_party/com/google/guava",
        "//third_party/com/google/protobuf:protobuf_java",
    ],
)

scala_import(
    name = "protobuf_java",
    jar = "@com_google_protobuf_protobuf_java//jar:file",
    runtime_deps = [
    ],
    deps = [
    ],
)
