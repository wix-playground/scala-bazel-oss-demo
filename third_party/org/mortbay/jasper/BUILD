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
    name = "apache_jsp",
    jar = "@org_mortbay_jasper_apache_jsp//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/eclipse/jetty/toolchain:jetty_schemas",
        "//third_party/org/mortbay/jasper:apache_el",
    ],
)

scala_import(
    name = "apache_el",
    jar = "@org_mortbay_jasper_apache_el//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)
