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
    name = "json_lib",
    jar = "@net_sf_json_lib_json_lib//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/commons-beanutils:commons_beanutils",
        "//third_party/commons-collections:commons_collections",
        "//third_party/commons-lang:commons_lang",
        "//third_party/commons-logging:commons_logging",
        "//third_party/net/sf/ezmorph",
    ],
)
