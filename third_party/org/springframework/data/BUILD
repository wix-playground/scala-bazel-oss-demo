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
    name = "spring_data_mongodb",
    jar = "@org_springframework_data_spring_data_mongodb//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/mongodb:mongo_java_driver",
        "//third_party/org/slf4j:jcl_over_slf4j",
        "//third_party/org/slf4j:slf4j_api",
        "//third_party/org/springframework:spring_beans",
        "//third_party/org/springframework:spring_context",
        "//third_party/org/springframework:spring_core",
        "//third_party/org/springframework:spring_expression",
        "//third_party/org/springframework:spring_tx",
        "//third_party/org/springframework/data:spring_data_commons",
    ],
)

scala_import(
    name = "spring_data_commons",
    jar = "@org_springframework_data_spring_data_commons//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/slf4j:jcl_over_slf4j",
        "//third_party/org/slf4j:slf4j_api",
        "//third_party/org/springframework:spring_beans",
        "//third_party/org/springframework:spring_core",
    ],
)
