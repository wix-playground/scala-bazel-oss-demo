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
    name = "spring_expression",
    jar = "@org_springframework_spring_expression//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/springframework:spring_core",
    ],
)

scala_import(
    name = "spring_jdbc",
    jar = "@org_springframework_spring_jdbc//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/springframework:spring_beans",
        "//third_party/org/springframework:spring_core",
        "//third_party/org/springframework:spring_tx",
    ],
)

scala_import(
    name = "spring_oxm",
    jar = "@org_springframework_spring_oxm//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/springframework:spring_beans",
        "//third_party/org/springframework:spring_core",
    ],
)

scala_import(
    name = "spring_context",
    jar = "@org_springframework_spring_context//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/springframework:spring_aop",
        "//third_party/org/springframework:spring_beans",
        "//third_party/org/springframework:spring_core",
        "//third_party/org/springframework:spring_expression",
    ],
)

scala_import(
    name = "spring_tx",
    jar = "@org_springframework_spring_tx//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/springframework:spring_beans",
        "//third_party/org/springframework:spring_core",
    ],
)

scala_import(
    name = "spring_web",
    jar = "@org_springframework_spring_web//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/springframework:spring_aop",
        "//third_party/org/springframework:spring_beans",
        "//third_party/org/springframework:spring_context",
        "//third_party/org/springframework:spring_core",
    ],
)

scala_import(
    name = "spring_context_support",
    jar = "@org_springframework_spring_context_support//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/springframework:spring_beans",
        "//third_party/org/springframework:spring_context",
        "//third_party/org/springframework:spring_core",
    ],
)

scala_import(
    name = "spring_core",
    jar = "@org_springframework_spring_core//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/commons-logging:commons_logging",
    ],
)

scala_import(
    name = "spring_messaging",
    jar = "@org_springframework_spring_messaging//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/springframework:spring_beans",
        "//third_party/org/springframework:spring_context",
        "//third_party/org/springframework:spring_core",
    ],
)

scala_import(
    name = "spring_webmvc",
    jar = "@org_springframework_spring_webmvc//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/springframework:spring_aop",
        "//third_party/org/springframework:spring_beans",
        "//third_party/org/springframework:spring_context",
        "//third_party/org/springframework:spring_core",
        "//third_party/org/springframework:spring_expression",
        "//third_party/org/springframework:spring_web",
    ],
)

scala_import(
    name = "spring_orm",
    jar = "@org_springframework_spring_orm//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/springframework:spring_beans",
        "//third_party/org/springframework:spring_core",
        "//third_party/org/springframework:spring_jdbc",
        "//third_party/org/springframework:spring_tx",
    ],
)

scala_import(
    name = "spring_jms",
    jar = "@org_springframework_spring_jms//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/springframework:spring_aop",
        "//third_party/org/springframework:spring_beans",
        "//third_party/org/springframework:spring_context",
        "//third_party/org/springframework:spring_core",
        "//third_party/org/springframework:spring_messaging",
        "//third_party/org/springframework:spring_tx",
    ],
)

scala_import(
    name = "spring_beans",
    jar = "@org_springframework_spring_beans//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/springframework:spring_core",
    ],
)

scala_import(
    name = "spring_aop",
    jar = "@org_springframework_spring_aop//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/springframework:spring_beans",
        "//third_party/org/springframework:spring_core",
    ],
)

scala_import(
    name = "spring_test",
    jar = "@org_springframework_spring_test//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/springframework:spring_core",
    ],
)
