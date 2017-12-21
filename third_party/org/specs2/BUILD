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
    name = "specs2_matcher_extra_2_11",
    jar = "@org_specs2_specs2_matcher_extra_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/specs2:specs2_analysis_2_11",
        "//third_party/org/specs2:specs2_matcher_2_11",
    ],
)

scala_import(
    name = "specs2_scalacheck_2_11",
    jar = "@org_specs2_specs2_scalacheck_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/scalacheck:scalacheck_2_11",
        "//third_party/org/specs2:specs2_core_2_11",
    ],
)

scala_import(
    name = "specs2_core_2_11",
    jar = "@org_specs2_specs2_core_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/scala-lang:scala_reflect",
        "//third_party/org/specs2:specs2_matcher_2_11",
    ],
)

scala_import(
    name = "specs2_common_2_11",
    jar = "@org_specs2_specs2_common_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/scala-lang:scala_reflect",
        "//third_party/org/scala-lang/modules:scala_parser_combinators_2_11",
        "//third_party/org/scala-lang/modules:scala_xml_2_11",
        "//third_party/org/scalaz:scalaz_concurrent_2_11",
        "//third_party/org/scalaz:scalaz_core_2_11",
        "//third_party/org/scalaz:scalaz_effect_2_11",
        "//third_party/org/specs2:specs2_codata_2_11",
    ],
)

scala_import(
    name = "specs2_junit_2_11",
    jar = "@org_specs2_specs2_junit_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/junit",
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/specs2:specs2_core_2_11",
    ],
)

scala_import(
    name = "specs2_codata_2_11",
    jar = "@org_specs2_specs2_codata_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/scalaz:scalaz_concurrent_2_11",
        "//third_party/org/scalaz:scalaz_core_2_11",
        "//third_party/org/scalaz:scalaz_effect_2_11",
    ],
)

scala_import(
    name = "specs2_matcher_2_11",
    jar = "@org_specs2_specs2_matcher_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/specs2:specs2_common_2_11",
    ],
)

scala_import(
    name = "classycle",
    jar = "@org_specs2_classycle//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "specs2_analysis_2_11",
    jar = "@org_specs2_specs2_analysis_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_compiler",
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/specs2:classycle",
        "//third_party/org/specs2:specs2_core_2_11",
        "//third_party/org/specs2:specs2_matcher_2_11",
    ],
)

scala_import(
    name = "specs2_mock_2_11",
    jar = "@org_specs2_specs2_mock_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/hamcrest:hamcrest_core",
        "//third_party/org/mockito:mockito_core",
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/specs2:specs2_core_2_11",
    ],
)
