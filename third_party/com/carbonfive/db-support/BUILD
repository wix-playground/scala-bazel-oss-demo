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
    name = "db_support",
    jar = "@com_carbonfive_db_support_db_support//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/commons-lang:commons_lang",
        "//third_party/org/slf4j:jcl_over_slf4j",
        "//third_party/org/slf4j:slf4j_api",
    ],
)

scala_import(
    name = "db_migration",
    jar = "@com_carbonfive_db_support_db_migration//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/carbonfive/db-support:db_support",
        "//third_party/commons-collections:commons_collections",
        "//third_party/commons-io:commons_io",
        "//third_party/commons-lang:commons_lang",
        "//third_party/org/slf4j:slf4j_api",
    ],
)
