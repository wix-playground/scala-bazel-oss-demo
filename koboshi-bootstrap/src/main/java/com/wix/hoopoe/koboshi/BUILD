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
    name = "agg=cache+cache/persistence+cache/transience+marshaller+registry+remote",
    srcs = glob(["cache/*.java"]) + glob(["cache/*.scala"]) + glob(["cache/persistence/*.java"]) + glob(["cache/persistence/*.scala"]) + glob(["cache/transience/*.java"]) + glob(["cache/transience/*.scala"]) + glob(["marshaller/*.java"]) + glob(["marshaller/*.scala"]) + glob(["registry/*.java"]) + glob(["registry/*.scala"]) + glob(["remote/*.java"]) + glob(["remote/*.scala"]),
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
        "//koboshi-bootstrap/src/main/java/com/wix/hoopoe/koboshi/namespace",
        "//koboshi-bootstrap/src/main/java/com/wix/hoopoe/koboshi/report",
        "//koboshi-bootstrap/src/main/java/com/wix/hoopoe/koboshi/scheduler",
        "//third_party/com/fasterxml/jackson/core:jackson_annotations",
        "//third_party/com/fasterxml/jackson/core:jackson_core",
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
