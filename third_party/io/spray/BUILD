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
    name = "spray_client_2_11",
    jar = "@io_spray_spray_client_2_11//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/io/spray:spray_can_2_11",
        "//third_party/io/spray:spray_http_2_11",
        "//third_party/io/spray:spray_httpx_2_11",
        "//third_party/io/spray:spray_util_2_11",
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "spray_util_2_11",
    jar = "@io_spray_spray_util_2_11//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "spray_http_2_11",
    jar = "@io_spray_spray_http_2_11//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/io/spray:spray_util_2_11",
        "//third_party/org/parboiled:parboiled_scala_2_11",
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "spray_can_2_11",
    jar = "@io_spray_spray_can_2_11//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/io/spray:spray_http_2_11",
        "//third_party/io/spray:spray_io_2_11",
        "//third_party/io/spray:spray_util_2_11",
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "spray_routing_2_11",
    jar = "@io_spray_spray_routing_2_11//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/chuusai:shapeless_2_11",
        "//third_party/io/spray:spray_http_2_11",
        "//third_party/io/spray:spray_httpx_2_11",
        "//third_party/io/spray:spray_util_2_11",
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "spray_io_2_11",
    jar = "@io_spray_spray_io_2_11//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/io/spray:spray_http_2_11",
        "//third_party/io/spray:spray_util_2_11",
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "spray_httpx_2_11",
    jar = "@io_spray_spray_httpx_2_11//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/io/spray:spray_http_2_11",
        "//third_party/io/spray:spray_util_2_11",
        "//third_party/org/jvnet/mimepull",
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/scala-lang/modules:scala_xml_2_11",
    ],
)
