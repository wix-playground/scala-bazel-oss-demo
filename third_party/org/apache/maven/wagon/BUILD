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
    name = "wagon_http_shared",
    jar = "@org_apache_maven_wagon_wagon_http_shared//jar:file",
    runtime_deps = [
        "//third_party/jtidy",
        "//third_party/org/apache/maven/wagon:wagon_provider_api",
    ],
    deps = [
    ],
)

scala_import(
    name = "wagon_ssh",
    jar = "@org_apache_maven_wagon_wagon_ssh//jar:file",
    runtime_deps = [
        "//third_party/com/jcraft:jsch",
        "//third_party/org/apache/maven/wagon:wagon_provider_api",
        "//third_party/org/apache/maven/wagon:wagon_ssh_common",
        "//third_party/org/codehaus/plexus:plexus_interactivity_api",
        "//third_party/org/codehaus/plexus:plexus_utils",
    ],
    deps = [
    ],
)

scala_import(
    name = "wagon_ssh_external",
    jar = "@org_apache_maven_wagon_wagon_ssh_external//jar:file",
    runtime_deps = [
        "//third_party/org/apache/maven/wagon:wagon_provider_api",
        "//third_party/org/apache/maven/wagon:wagon_ssh_common",
        "//third_party/org/codehaus/plexus:plexus_utils",
    ],
    deps = [
    ],
)

scala_import(
    name = "wagon_file",
    jar = "@org_apache_maven_wagon_wagon_file//jar:file",
    runtime_deps = [
        "//third_party/org/apache/maven/wagon:wagon_provider_api",
    ],
    deps = [
    ],
)

scala_import(
    name = "wagon_provider_api",
    jar = "@org_apache_maven_wagon_wagon_provider_api//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/codehaus/plexus:plexus_utils",
    ],
)

scala_import(
    name = "wagon_ssh_common",
    jar = "@org_apache_maven_wagon_wagon_ssh_common//jar:file",
    runtime_deps = [
        "//third_party/org/apache/maven/wagon:wagon_provider_api",
        "//third_party/org/codehaus/plexus:plexus_interactivity_api",
        "//third_party/org/codehaus/plexus:plexus_utils",
    ],
    deps = [
    ],
)

scala_import(
    name = "wagon_webdav",
    jar = "@org_apache_maven_wagon_wagon_webdav//jar:file",
    runtime_deps = [
        "//third_party/org/apache/maven/wagon:wagon_provider_api",
        "//third_party/slide:slide_webdavlib",
    ],
    deps = [
        "//third_party/commons-logging:commons_logging",
    ],
)

scala_import(
    name = "wagon_http_lightweight",
    jar = "@org_apache_maven_wagon_wagon_http_lightweight//jar:file",
    runtime_deps = [
        "//third_party/org/apache/maven/wagon:wagon_http_shared",
        "//third_party/org/apache/maven/wagon:wagon_provider_api",
        "//third_party/xml-apis:xml_apis",
    ],
    deps = [
    ],
)
