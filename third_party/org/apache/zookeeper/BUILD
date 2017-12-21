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
    name = "zookeeper",
    jar = "@org_apache_zookeeper_zookeeper//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/io/netty",
        "//third_party/jline",
        "//third_party/org/slf4j:slf4j_api",
    ],
    # EXCLUDES org.slf4j:slf4j-log4j12
    # EXCLUDES log4j:log4j
)
