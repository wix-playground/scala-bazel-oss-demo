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
    name = "json4s_scalap_2_11",
    jar = "@org_json4s_json4s_scalap_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "json4s_ast_2_11",
    jar = "@org_json4s_json4s_ast_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "json4s_mongo_2_11",
    jar = "@org_json4s_json4s_mongo_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/json4s:json4s_core_2_11",
        "//third_party/org/mongodb:mongo_java_driver",
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "json4s_ext_2_11",
    jar = "@org_json4s_json4s_ext_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/joda-time:joda_time",
        "//third_party/org/joda:joda_convert",
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "json4s_native_2_11",
    jar = "@org_json4s_json4s_native_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/json4s:json4s_core_2_11",
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "json4s_jackson_2_11",
    jar = "@org_json4s_json4s_jackson_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/fasterxml/jackson/core:jackson_databind",
        "//third_party/org/json4s:json4s_core_2_11",
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "json4s_core_2_11",
    jar = "@org_json4s_json4s_core_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/thoughtworks/paranamer",
        "//third_party/org/json4s:json4s_ast_2_11",
        "//third_party/org/json4s:json4s_scalap_2_11",
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/scala-lang/modules:scala_xml_2_11",
    ],
)
