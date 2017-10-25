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
    name = "async_http_client",
    jar = "@com_ning_async_http_client//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/io/netty",
        "//third_party/org/slf4j:slf4j_api",
    ],
)

scala_import(
    name = "compress_lzf",
    jar = "@com_ning_compress_lzf//jar:file",
    runtime_deps = [
    ],
    deps = [
    ],
)
