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
    name = "bval_jsr303",
    jar = "@org_apache_bval_bval_jsr303//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/bval:bval_core",
        "//third_party/org/slf4j:slf4j_api",
    ],
)

scala_import(
    name = "bval_core",
    jar = "@org_apache_bval_bval_core//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/commons-beanutils:commons_beanutils_core",
        "//third_party/commons-lang:commons_lang",
        "//third_party/org/slf4j:slf4j_api",
    ],
)
