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
    name = "slf4j_api",
    jar = "@org_slf4j_slf4j_api//jar:file",
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "jul_to_slf4j",
    jar = "@org_slf4j_jul_to_slf4j//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/slf4j:slf4j_api",
    ],
)

scala_import(
    name = "slf4j_jdk14",
    jar = "@org_slf4j_slf4j_jdk14//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/slf4j:slf4j_api",
    ],
)

scala_import(
    name = "slf4j_log4j12",
    jar = "@org_slf4j_slf4j_log4j12//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/slf4j:slf4j_api",
    ],
    # EXCLUDES *:netty
    # EXCLUDES *:javax
    # EXCLUDES *:mail
    # EXCLUDES *:jmxri
    # EXCLUDES *:jms
    # EXCLUDES *:jmxtools
    # EXCLUDES *:jline
)

scala_import(
    name = "slf4j_simple",
    jar = "@org_slf4j_slf4j_simple//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/slf4j:slf4j_api",
    ],
)

scala_import(
    name = "jcl_over_slf4j",
    jar = "@org_slf4j_jcl_over_slf4j//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/slf4j:slf4j_api",
    ],
)
