package(default_visibility = ["//visibility:public"])

load(
    "@io_bazel_rules_scala//scala:scala.bzl",
    "scala_binary",
    "scala_library",
    "scala_test",
    "scala_macro_library",
    "scala_specs2_junit_test",
)

scala_library(
    name = "namespace",
    srcs = glob(["*.java"]) + glob(["*.scala"]),
    javacopts = [
        "-g",
        "-deprecation",
        "-XepDisableAllChecks",
    ],
    scalacopts = [
        "-unchecked",
        "-deprecation",
        "-feature",
        "-Xmax-classfile-name",
        "240",
        "-Xlint:missing-interpolator",
        "-Ywarn-unused-import",
        "-Ywarn-unused",
    ],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/fasterxml/jackson/core:jackson_databind",
        "//third_party/com/fasterxml/jackson/datatype:jackson_datatype_joda",
        "//third_party/com/fasterxml/jackson/module:jackson_module_scala_2_11",
        "//third_party/com/google/code/findbugs:jsr305",
        "//third_party/com/google/guava",
        "//third_party/joda-time:joda_time",
        "//third_party/org/joda:joda_convert",
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/slf4j:slf4j_api",
    ],
)
