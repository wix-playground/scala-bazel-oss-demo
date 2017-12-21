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
    name = "cassandra_driver_core",
    jar = "@com_datastax_cassandra_cassandra_driver_core//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/guava",
        "//third_party/io/netty:netty_handler",
    ],
    # EXCLUDES com.codahale.metrics:metrics-core
)
