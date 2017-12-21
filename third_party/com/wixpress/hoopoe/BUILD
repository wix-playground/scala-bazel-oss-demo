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
    name = "hoopoe_specs2",
    jar = None,
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/code/findbugs:jsr305",
        "//third_party/com/google/guava",
        "//third_party/joda-time:joda_time",
        "//third_party/org/joda:joda_convert",
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/slf4j:slf4j_api",
        "//third_party/org/specs2:specs2_core_2_11",
        "//third_party/org/specs2:specs2_junit_2_11",
        "//third_party/org/specs2:specs2_matcher_extra_2_11",
        "//third_party/org/specs2:specs2_mock_2_11",
        "//third_party/org/specs2:specs2_scalacheck_2_11",
    ],
)
