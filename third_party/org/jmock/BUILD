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
    name = "jmock_junit4",
    jar = "@org_jmock_jmock_junit4//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/junit",
        "//third_party/org/jmock",
    ],
    # EXCLUDES org.hamcrest:hamcrest-core
    # EXCLUDES org.hamcrest:hamcrest-library
    # EXCLUDES org.hamcrest:hamcrest-unit-test
    # EXCLUDES junit:junit-dep
)

scala_import(
    name = "jmock",
    jar = "@org_jmock_jmock//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/cglib",
        "//third_party/junit",
        "//third_party/org/apache-extras/beanshell:bsh",
        "//third_party/org/hamcrest:hamcrest_library",
        "//third_party/org/jmock:jmock_testjar",
        "//third_party/org/ow2/asm",
    ],
)

scala_import(
    name = "jmock_testjar",
    jar = "@org_jmock_jmock_testjar//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "jmock_legacy",
    jar = "@org_jmock_jmock_legacy//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/jmock",
        "//third_party/org/objenesis",
    ],
)
