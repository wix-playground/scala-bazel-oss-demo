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
    name = "scalikejdbc_interpolation_2_11",
    jar = "@org_scalikejdbc_scalikejdbc_interpolation_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/scalikejdbc:scalikejdbc_core_2_11",
        "//third_party/org/scalikejdbc:scalikejdbc_interpolation_macro_2_11",
        "//third_party/org/slf4j:slf4j_api",
    ],
)

scala_import(
    name = "scalikejdbc_core_2_11",
    jar = "@org_scalikejdbc_scalikejdbc_core_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/joda-time:joda_time",
        "//third_party/org/apache/commons:commons_dbcp2",
        "//third_party/org/joda:joda_convert",
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/scala-lang:scala_reflect",
        "//third_party/org/scala-lang/modules:scala_parser_combinators_2_11",
        "//third_party/org/slf4j:slf4j_api",
    ],
)

scala_import(
    name = "scalikejdbc_test_2_11",
    jar = "@org_scalikejdbc_scalikejdbc_test_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/scalikejdbc:scalikejdbc_2_11",
        "//third_party/org/slf4j:slf4j_api",
    ],
)

scala_import(
    name = "scalikejdbc_interpolation_macro_2_11",
    jar = "@org_scalikejdbc_scalikejdbc_interpolation_macro_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/scala-lang:scala_reflect",
        "//third_party/org/scalikejdbc:scalikejdbc_core_2_11",
    ],
)

scala_import(
    name = "scalikejdbc_2_11",
    jar = "@org_scalikejdbc_scalikejdbc_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/scalikejdbc:scalikejdbc_core_2_11",
        "//third_party/org/scalikejdbc:scalikejdbc_interpolation_2_11",
    ],
)
