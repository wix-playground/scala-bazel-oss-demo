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
    name = "jnr_posix",
    jar = "@com_github_jnr_jnr_posix//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/github/jnr:jnr_constants",
    ],
    # EXCLUDES com.github.jnr:jnr-ffi
)

scala_import(
    name = "jnr_netdb",
    jar = "@com_github_jnr_jnr_netdb//jar:file",
    runtime_deps = [
    ],
    deps = [
    ],
    # EXCLUDES com.github.jnr:jnr-ffi
)

scala_import(
    name = "jffi",
    jar = "@com_github_jnr_jffi//jar:file",
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "jnr_constants",
    jar = "@com_github_jnr_jnr_constants//jar:file",
    runtime_deps = [
    ],
    deps = [
    ],
    # EXCLUDES com.github.jnr:jnr-ffi
)

scala_import(
    name = "jnr_x86asm",
    jar = "@com_github_jnr_jnr_x86asm//jar:file",
    runtime_deps = [
    ],
    deps = [
    ],
    # EXCLUDES com.github.jnr:jnr-ffi
)

scala_import(
    name = "jnr_enxio",
    jar = "@com_github_jnr_jnr_enxio//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/github/jnr:jnr_constants",
    ],
    # EXCLUDES com.github.jnr:jnr-ffi
)

scala_import(
    name = "jnr_unixsocket",
    jar = "@com_github_jnr_jnr_unixsocket//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/github/jnr:jnr_constants",
        "//third_party/com/github/jnr:jnr_enxio",
        "//third_party/com/github/jnr:jnr_posix",
    ],
    # EXCLUDES com.github.jnr:jnr-ffi
)
