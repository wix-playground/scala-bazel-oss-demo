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
    name = "commons_validator",
    jar = "@commons_validator_commons_validator//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/commons-beanutils:commons_beanutils",
        "//third_party/commons-collections:commons_collections",
        "//third_party/commons-digester:commons_digester",
        "//third_party/commons-logging:commons_logging",
    ],
)
