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
    name = "reporter_config",
    jar = "@com_addthis_metrics_reporter_config//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/yammer/metrics:metrics_core",
        "//third_party/org/hibernate:hibernate_validator",
        "//third_party/org/slf4j:slf4j_api",
        "//third_party/org/yaml:snakeyaml",
    ],
)
