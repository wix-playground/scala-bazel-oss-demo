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
    name = "velocity_tools",
    jar = "@org_apache_velocity_velocity_tools//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/velocity",
    ],
    # EXCLUDES dom4j:dom4j
    # EXCLUDES commons-lang:commons-lang
    # EXCLUDES commons-beanutils:commons-beanutils
    # EXCLUDES commons-digester:commons-digester
    # EXCLUDES org.apache.struts:struts-taglib
    # EXCLUDES commons-logging:commons-logging
    # EXCLUDES sslext:sslext
    # EXCLUDES commons-collections:commons-collections
    # EXCLUDES oro:oro
    # EXCLUDES org.apache.struts:struts-core
    # EXCLUDES commons-chain:commons-chain
    # EXCLUDES commons-validator:commons-validator
    # EXCLUDES org.apache.struts:struts-tiles
)

scala_import(
    name = "velocity",
    jar = "@org_apache_velocity_velocity//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/commons-collections:commons_collections",
        "//third_party/commons-lang:commons_lang",
    ],
)
