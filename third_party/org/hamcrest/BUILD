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
    name = "hamcrest_all",
    jar = "@org_hamcrest_hamcrest_all//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "hamcrest_core",
    jar = "@org_hamcrest_hamcrest_core//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "hamcrest_library",
    jar = "@org_hamcrest_hamcrest_library//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/hamcrest:hamcrest_core",
    ],
)
