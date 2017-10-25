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
    name = "guice",
    jar = "@com_google_inject_guice//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/aopalliance",
        "//third_party/com/google/guava",
        "//third_party/javax/inject:javax_inject",
    ],
    # EXCLUDES com.google.guava:guava-jdk5
)
