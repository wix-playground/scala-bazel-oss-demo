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
    name = "jetty",
    jar = "@org_mortbay_jetty_jetty//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/mortbay/jetty:jetty_util",
        "//third_party/org/mortbay/jetty:servlet_api",
    ],
)

scala_import(
    name = "jetty_util",
    jar = "@org_mortbay_jetty_jetty_util//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "servlet_api",
    jar = "@org_mortbay_jetty_servlet_api//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)
