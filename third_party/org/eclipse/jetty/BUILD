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
    name = "apache_jstl",
    jar = "@org_eclipse_jetty_apache_jstl//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/taglibs:taglibs_standard_impl",
        "//third_party/org/apache/taglibs:taglibs_standard_spec",
    ],
)

scala_import(
    name = "jetty_alpn_client",
    jar = "@org_eclipse_jetty_jetty_alpn_client//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/eclipse/jetty:jetty_io",
    ],
)

scala_import(
    name = "jetty_xml",
    jar = "@org_eclipse_jetty_jetty_xml//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/eclipse/jetty:jetty_util",
    ],
)

scala_import(
    name = "jetty_io",
    jar = "@org_eclipse_jetty_jetty_io//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/eclipse/jetty:jetty_util",
    ],
)

scala_import(
    name = "jetty_continuation",
    jar = "@org_eclipse_jetty_jetty_continuation//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "jetty_plus",
    jar = "@org_eclipse_jetty_jetty_plus//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/eclipse/jetty:jetty_jndi",
        "//third_party/org/eclipse/jetty:jetty_webapp",
    ],
)

scala_import(
    name = "apache_jsp",
    jar = "@org_eclipse_jetty_apache_jsp//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/javax/servlet:javax_servlet_api",
        "//third_party/org/eclipse/jdt/core/compiler:ecj",
        "//third_party/org/eclipse/jetty:jetty_util",
        "//third_party/org/eclipse/jetty/toolchain:jetty_schemas",
        "//third_party/org/mortbay/jasper:apache_jsp",
    ],
)

scala_import(
    name = "jetty_client",
    jar = "@org_eclipse_jetty_jetty_client//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/eclipse/jetty:jetty_http",
        "//third_party/org/eclipse/jetty:jetty_io",
    ],
)

scala_import(
    name = "jetty_webapp",
    jar = "@org_eclipse_jetty_jetty_webapp//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/eclipse/jetty:jetty_servlet",
        "//third_party/org/eclipse/jetty:jetty_xml",
    ],
)

scala_import(
    name = "jetty_annotations",
    jar = "@org_eclipse_jetty_jetty_annotations//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/javax/annotation:javax_annotation_api",
        "//third_party/org/eclipse/jetty:jetty_plus",
        "//third_party/org/eclipse/jetty:jetty_webapp",
        "//third_party/org/ow2/asm",
        "//third_party/org/ow2/asm:asm_commons",
    ],
)

scala_import(
    name = "jetty_http",
    jar = "@org_eclipse_jetty_jetty_http//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/eclipse/jetty:jetty_util",
    ],
)

scala_import(
    name = "jetty_jmx",
    jar = "@org_eclipse_jetty_jetty_jmx//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/eclipse/jetty:jetty_util",
    ],
)

scala_import(
    name = "jetty_util",
    jar = "@org_eclipse_jetty_jetty_util//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "jetty_security",
    jar = "@org_eclipse_jetty_jetty_security//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/eclipse/jetty:jetty_server",
    ],
)

scala_import(
    name = "jetty_server",
    jar = "@org_eclipse_jetty_jetty_server//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/javax/servlet:javax_servlet_api",
        "//third_party/org/eclipse/jetty:jetty_http",
        "//third_party/org/eclipse/jetty:jetty_io",
    ],
)

scala_import(
    name = "jetty_servlets",
    jar = "@org_eclipse_jetty_jetty_servlets//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/eclipse/jetty:jetty_continuation",
        "//third_party/org/eclipse/jetty:jetty_http",
        "//third_party/org/eclipse/jetty:jetty_io",
        "//third_party/org/eclipse/jetty:jetty_util",
    ],
)

scala_import(
    name = "jetty_servlet",
    jar = "@org_eclipse_jetty_jetty_servlet//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/eclipse/jetty:jetty_security",
    ],
)

scala_import(
    name = "jetty_jndi",
    jar = "@org_eclipse_jetty_jetty_jndi//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/eclipse/jetty:jetty_util",
    ],
)
