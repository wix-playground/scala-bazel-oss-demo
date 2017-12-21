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
    name = "geronimo_jta_1_0_1B_spec",
    jar = "@org_apache_geronimo_specs_geronimo_jta_1_0_1B_spec//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "geronimo_jms_1_1_spec",
    jar = "@org_apache_geronimo_specs_geronimo_jms_1_1_spec//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "geronimo_j2ee_management_1_1_spec",
    jar = "@org_apache_geronimo_specs_geronimo_j2ee_management_1_1_spec//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)
