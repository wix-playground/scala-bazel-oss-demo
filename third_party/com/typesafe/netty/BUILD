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
    name = "netty_reactive_streams",
    jar = "@com_typesafe_netty_netty_reactive_streams//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/io/netty:netty_handler",
        "//third_party/org/reactivestreams:reactive_streams",
    ],
)
