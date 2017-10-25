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
    name = "build_link",
    jar = "@com_typesafe_play_build_link//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/typesafe/play:play_exceptions",
    ],
)

scala_import(
    name = "play_streams_2_11",
    jar = "@com_typesafe_play_play_streams_2_11//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/typesafe/akka:akka_stream_2_11",
        "//third_party/org/reactivestreams:reactive_streams",
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/scala-lang/modules:scala_java8_compat_2_11",
    ],
)

scala_import(
    name = "play_netty_utils",
    jar = "@com_typesafe_play_play_netty_utils//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/slf4j:jcl_over_slf4j",
        "//third_party/org/slf4j:jul_to_slf4j",
        "//third_party/org/slf4j:slf4j_api",
    ],
)

scala_import(
    name = "twirl_api_2_11",
    jar = "@com_typesafe_play_twirl_api_2_11//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/scala-lang/modules:scala_xml_2_11",
    ],
)

scala_import(
    name = "play_exceptions",
    jar = "@com_typesafe_play_play_exceptions//jar:file",
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "play_functional_2_11",
    jar = "@com_typesafe_play_play_functional_2_11//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "play_iteratees_2_11",
    jar = "@com_typesafe_play_play_iteratees_2_11//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/typesafe:config",
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/scala-stm:scala_stm_2_11",
    ],
)

scala_import(
    name = "play_2_11",
    jar = "@com_typesafe_play_play_2_11//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/fasterxml/jackson/core:jackson_annotations",
        "//third_party/com/fasterxml/jackson/core:jackson_core",
        "//third_party/com/fasterxml/jackson/core:jackson_databind",
        "//third_party/com/fasterxml/jackson/datatype:jackson_datatype_jdk8",
        "//third_party/com/fasterxml/jackson/datatype:jackson_datatype_jsr310",
        "//third_party/com/google/guava",
        "//third_party/com/typesafe/akka:akka_actor_2_11",
        "//third_party/com/typesafe/akka:akka_slf4j_2_11",
        "//third_party/com/typesafe/play:build_link",
        "//third_party/com/typesafe/play:play_json_2_11",
        "//third_party/com/typesafe/play:play_netty_utils",
        "//third_party/com/typesafe/play:play_streams_2_11",
        "//third_party/com/typesafe/play:twirl_api_2_11",
        "//third_party/commons-codec:commons_codec",
        "//third_party/io/jsonwebtoken:jjwt",
        "//third_party/javax/inject:javax_inject",
        "//third_party/javax/transaction:jta",
        "//third_party/org/apache/commons:commons_lang3",
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/scala-lang:scala_reflect",
        "//third_party/org/scala-lang/modules:scala_java8_compat_2_11",
        "//third_party/org/scala-lang/modules:scala_parser_combinators_2_11",
        "//third_party/org/slf4j:jcl_over_slf4j",
        "//third_party/org/slf4j:jul_to_slf4j",
        "//third_party/org/slf4j:slf4j_api",
    ],
)

scala_import(
    name = "play_json_2_11",
    jar = "@com_typesafe_play_play_json_2_11//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/fasterxml/jackson/core:jackson_annotations",
        "//third_party/com/fasterxml/jackson/core:jackson_core",
        "//third_party/com/fasterxml/jackson/core:jackson_databind",
        "//third_party/com/fasterxml/jackson/datatype:jackson_datatype_jdk8",
        "//third_party/com/fasterxml/jackson/datatype:jackson_datatype_jsr310",
        "//third_party/com/typesafe/play:play_functional_2_11",
        "//third_party/joda-time:joda_time",
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/scala-lang:scala_reflect",
        "//third_party/org/typelevel:macro_compat_2_11",
    ],
)
