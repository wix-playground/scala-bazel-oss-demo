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
    name = "dirgra",
    jar = "@org_jruby_dirgra//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "jruby_stdlib",
    jar = "@org_jruby_jruby_stdlib//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "jruby",
    jar = "@org_jruby_jruby//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/jruby:jruby_core",
        "//third_party/org/jruby:jruby_stdlib",
    ],
)

scala_import(
    name = "jruby_core",
    jar = "@org_jruby_jruby_core//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/github/jnr:jffi",
        "//third_party/com/github/jnr:jnr_constants",
        "//third_party/com/github/jnr:jnr_enxio",
        "//third_party/com/github/jnr:jnr_netdb",
        "//third_party/com/github/jnr:jnr_posix",
        "//third_party/com/github/jnr:jnr_unixsocket",
        "//third_party/com/github/jnr:jnr_x86asm",
        "//third_party/com/headius:invokebinder",
        "//third_party/com/headius:options",
        "//third_party/com/jcraft:jzlib",
        "//third_party/com/martiansoftware:nailgun_server",
        "//third_party/joda-time:joda_time",
        "//third_party/org/jruby:dirgra",
        "//third_party/org/jruby/extras:bytelist",
        "//third_party/org/jruby/jcodings",
        "//third_party/org/jruby/joni",
    ],
)
