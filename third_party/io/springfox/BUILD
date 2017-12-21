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
    name = "springfox_swagger2",
    jar = "@io_springfox_springfox_swagger2//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/fasterxml:classmate",
        "//third_party/com/google/guava",
        "//third_party/io/springfox:springfox_schema",
        "//third_party/io/springfox:springfox_spi",
        "//third_party/io/springfox:springfox_spring_web",
        "//third_party/io/springfox:springfox_swagger_common",
        "//third_party/io/swagger:swagger_annotations",
        "//third_party/io/swagger:swagger_models",
        "//third_party/org/mapstruct",
        "//third_party/org/slf4j:slf4j_api",
        "//third_party/org/springframework/plugin:spring_plugin_core",
        "//third_party/org/springframework/plugin:spring_plugin_metadata",
    ],
)

scala_import(
    name = "springfox_schema",
    jar = "@io_springfox_springfox_schema//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/io/springfox:springfox_core",
        "//third_party/io/springfox:springfox_spi",
    ],
)

scala_import(
    name = "springfox_spring_web",
    jar = "@io_springfox_springfox_spring_web//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/fasterxml:classmate",
        "//third_party/com/google/guava",
        "//third_party/io/springfox:springfox_spi",
        "//third_party/org/reflections",
        "//third_party/org/slf4j:slf4j_api",
        "//third_party/org/springframework/plugin:spring_plugin_core",
        "//third_party/org/springframework/plugin:spring_plugin_metadata",
    ],
)

scala_import(
    name = "springfox_swagger_common",
    jar = "@io_springfox_springfox_swagger_common//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/fasterxml:classmate",
        "//third_party/com/google/guava",
        "//third_party/io/springfox:springfox_schema",
        "//third_party/io/springfox:springfox_spi",
        "//third_party/io/springfox:springfox_spring_web",
        "//third_party/io/swagger:swagger_annotations",
        "//third_party/io/swagger:swagger_models",
        "//third_party/org/slf4j:slf4j_api",
        "//third_party/org/springframework/plugin:spring_plugin_core",
        "//third_party/org/springframework/plugin:spring_plugin_metadata",
    ],
)

scala_import(
    name = "springfox_core",
    jar = "@io_springfox_springfox_core//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/fasterxml:classmate",
        "//third_party/com/google/guava",
        "//third_party/net/bytebuddy:byte_buddy",
        "//third_party/org/slf4j:slf4j_api",
        "//third_party/org/springframework/plugin:spring_plugin_core",
        "//third_party/org/springframework/plugin:spring_plugin_metadata",
    ],
)

scala_import(
    name = "springfox_spi",
    jar = "@io_springfox_springfox_spi//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/io/springfox:springfox_core",
    ],
)
