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
    name = "jackson_dataformat_xml",
    jar = "@com_fasterxml_jackson_dataformat_jackson_dataformat_xml//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/fasterxml/jackson/core:jackson_annotations",
        "//third_party/com/fasterxml/jackson/core:jackson_core",
        "//third_party/com/fasterxml/jackson/core:jackson_databind",
        "//third_party/com/fasterxml/jackson/module:jackson_module_jaxb_annotations",
        "//third_party/com/fasterxml/woodstox:woodstox_core",
        "//third_party/org/codehaus/woodstox:stax2_api",
    ],
)

scala_import(
    name = "jackson_dataformat_yaml",
    jar = "@com_fasterxml_jackson_dataformat_jackson_dataformat_yaml//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/fasterxml/jackson/core:jackson_core",
        "//third_party/org/yaml:snakeyaml",
    ],
)

scala_import(
    name = "jackson_dataformat_cbor",
    jar = "@com_fasterxml_jackson_dataformat_jackson_dataformat_cbor//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/fasterxml/jackson/core:jackson_core",
    ],
)

scala_import(
    name = "jackson_dataformat_smile",
    jar = "@com_fasterxml_jackson_dataformat_jackson_dataformat_smile//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/fasterxml/jackson/core:jackson_core",
    ],
)
