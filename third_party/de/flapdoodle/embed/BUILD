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
    name = "de_flapdoodle_embed_process",
    jar = "@de_flapdoodle_embed_de_flapdoodle_embed_process//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/commons-io:commons_io",
        "//third_party/net/java/dev/jna",
        "//third_party/net/java/dev/jna:jna_platform",
        "//third_party/org/apache/commons:commons_compress",
        "//third_party/org/apache/commons:commons_lang3",
        "//third_party/org/slf4j:slf4j_api",
    ],
)

scala_import(
    name = "de_flapdoodle_embed_mongo",
    jar = "@de_flapdoodle_embed_de_flapdoodle_embed_mongo//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/de/flapdoodle/embed:de_flapdoodle_embed_process",
    ],
)
