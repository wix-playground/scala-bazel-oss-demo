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
    name = "commons_beanutils_core",
    jar = "@commons_beanutils_commons_beanutils_core//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
    # EXCLUDES commons-logging:commons-logging
)

scala_import(
    name = "commons_beanutils",
    jar = "@commons_beanutils_commons_beanutils//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/commons-collections:commons_collections",
        "//third_party/commons-logging:commons_logging",
    ],
)
