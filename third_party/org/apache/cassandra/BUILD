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
    name = "cassandra_all",
    jar = "@org_apache_cassandra_cassandra_all//jar:file",
    tags = ["manual"],
    runtime_deps = [
        "//third_party/org/slf4j:slf4j_log4j12",
    ],
    deps = [
        "//third_party/com/addthis/metrics:reporter_config",
        "//third_party/com/github/stephenc:jamm",
        "//third_party/com/github/stephenc/high-scale-lib:high_scale_lib",
        "//third_party/com/google/guava",
        "//third_party/com/googlecode/concurrentlinkedhashmap:concurrentlinkedhashmap_lru",
        "//third_party/com/googlecode/json-simple:json_simple",
        "//third_party/com/ning:compress_lzf",
        "//third_party/com/thinkaurelius/thrift:thrift_server",
        "//third_party/com/yammer/metrics:metrics_core",
        "//third_party/commons-cli:commons_cli",
        "//third_party/commons-codec:commons_codec",
        "//third_party/edu/stanford/ppl:snaptree",
        "//third_party/io/netty",
        "//third_party/jline",
        "//third_party/log4j",
        "//third_party/net/jpountz/lz4",
        "//third_party/net/sf/supercsv:super_csv",
        "//third_party/org/antlr",
        "//third_party/org/apache/cassandra:cassandra_thrift",
        "//third_party/org/apache/commons:commons_lang3",
        "//third_party/org/apache/thrift:libthrift",
        "//third_party/org/codehaus/jackson:jackson_core_asl",
        "//third_party/org/codehaus/jackson:jackson_mapper_asl",
        "//third_party/org/mindrot:jbcrypt",
        "//third_party/org/slf4j:slf4j_api",
        "//third_party/org/xerial/snappy:snappy_java",
        "//third_party/org/yaml:snakeyaml",
    ],
)

scala_import(
    name = "cassandra_thrift",
    jar = "@org_apache_cassandra_cassandra_thrift//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/commons:commons_lang3",
        "//third_party/org/apache/thrift:libthrift",
        "//third_party/org/slf4j:slf4j_api",
    ],
)
