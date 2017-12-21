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
    name = "jackson_datatype_joda",
    jar = "@com_fasterxml_jackson_datatype_jackson_datatype_joda//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/fasterxml/jackson/core:jackson_annotations",
        "//third_party/com/fasterxml/jackson/core:jackson_core",
    ],
    # EXCLUDES com.fasterxml.jackson.core:jackson-databind
    # EXCLUDES joda-time:joda-time
)

scala_import(
    name = "jackson_datatype_jsr310",
    jar = "@com_fasterxml_jackson_datatype_jackson_datatype_jsr310//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/fasterxml/jackson/core:jackson_annotations",
        "//third_party/com/fasterxml/jackson/core:jackson_core",
        "//third_party/com/fasterxml/jackson/core:jackson_databind",
    ],
)

scala_import(
    name = "jackson_datatype_guava",
    jar = "@com_fasterxml_jackson_datatype_jackson_datatype_guava//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/fasterxml/jackson/core:jackson_core",
        "//third_party/com/fasterxml/jackson/core:jackson_databind",
    ],
    # EXCLUDES com.google.guava:guava
)

scala_import(
    name = "jackson_datatype_jdk8",
    jar = "@com_fasterxml_jackson_datatype_jackson_datatype_jdk8//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/fasterxml/jackson/core:jackson_core",
        "//third_party/com/fasterxml/jackson/core:jackson_databind",
    ],
)
