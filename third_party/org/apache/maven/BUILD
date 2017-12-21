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
    name = "maven_settings",
    jar = "@org_apache_maven_maven_settings//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/maven:maven_model",
        "//third_party/org/codehaus/plexus:plexus_container_default",
        "//third_party/org/codehaus/plexus:plexus_interpolation",
        "//third_party/org/codehaus/plexus:plexus_utils",
    ],
)

scala_import(
    name = "maven_plugin_api",
    jar = "@org_apache_maven_maven_plugin_api//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "maven_plugin_registry",
    jar = "@org_apache_maven_maven_plugin_registry//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/codehaus/plexus:plexus_container_default",
        "//third_party/org/codehaus/plexus:plexus_utils",
    ],
)

scala_import(
    name = "maven_repository_metadata",
    jar = "@org_apache_maven_maven_repository_metadata//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/codehaus/plexus:plexus_utils",
    ],
)

scala_import(
    name = "maven_error_diagnostics",
    jar = "@org_apache_maven_maven_error_diagnostics//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/codehaus/plexus:plexus_container_default",
    ],
)

scala_import(
    name = "maven_artifact_manager",
    jar = "@org_apache_maven_maven_artifact_manager//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/maven:maven_artifact",
        "//third_party/org/apache/maven:maven_repository_metadata",
        "//third_party/org/apache/maven/wagon:wagon_provider_api",
        "//third_party/org/codehaus/plexus:plexus_container_default",
        "//third_party/org/codehaus/plexus:plexus_utils",
    ],
)

scala_import(
    name = "maven_core",
    jar = "@org_apache_maven_maven_core//jar:file",
    tags = ["manual"],
    runtime_deps = [
        "//third_party/org/apache/maven/wagon:wagon_file",
        "//third_party/org/apache/maven/wagon:wagon_http_lightweight",
        "//third_party/org/apache/maven/wagon:wagon_ssh",
        "//third_party/org/apache/maven/wagon:wagon_ssh_external",
        "//third_party/org/apache/maven/wagon:wagon_webdav",
    ],
    deps = [
        "//third_party/classworlds",
        "//third_party/commons-cli:commons_cli",
        "//third_party/org/apache/maven:maven_artifact",
        "//third_party/org/apache/maven:maven_artifact_manager",
        "//third_party/org/apache/maven:maven_error_diagnostics",
        "//third_party/org/apache/maven:maven_model",
        "//third_party/org/apache/maven:maven_monitor",
        "//third_party/org/apache/maven:maven_plugin_api",
        "//third_party/org/apache/maven:maven_plugin_descriptor",
        "//third_party/org/apache/maven:maven_plugin_parameter_documenter",
        "//third_party/org/apache/maven:maven_profile",
        "//third_party/org/apache/maven:maven_project",
        "//third_party/org/apache/maven:maven_repository_metadata",
        "//third_party/org/apache/maven:maven_settings",
        "//third_party/org/apache/maven/reporting:maven_reporting_api",
        "//third_party/org/apache/maven/wagon:wagon_provider_api",
        "//third_party/org/codehaus/plexus:plexus_container_default",
        "//third_party/org/codehaus/plexus:plexus_interactivity_api",
        "//third_party/org/codehaus/plexus:plexus_utils",
    ],
)

scala_import(
    name = "maven_project",
    jar = "@org_apache_maven_maven_project//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/maven:maven_artifact",
        "//third_party/org/apache/maven:maven_artifact_manager",
        "//third_party/org/apache/maven:maven_model",
        "//third_party/org/apache/maven:maven_plugin_registry",
        "//third_party/org/apache/maven:maven_profile",
        "//third_party/org/apache/maven:maven_settings",
        "//third_party/org/codehaus/plexus:plexus_container_default",
        "//third_party/org/codehaus/plexus:plexus_interpolation",
        "//third_party/org/codehaus/plexus:plexus_utils",
    ],
)

scala_import(
    name = "maven_builder_support",
    jar = "@org_apache_maven_maven_builder_support//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/commons:commons_lang3",
        "//third_party/org/codehaus/plexus:plexus_utils",
    ],
)

scala_import(
    name = "maven_model_builder",
    jar = "@org_apache_maven_maven_model_builder//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/guava",
        "//third_party/org/apache/commons:commons_lang3",
        "//third_party/org/apache/maven:maven_artifact",
        "//third_party/org/apache/maven:maven_builder_support",
        "//third_party/org/apache/maven:maven_model",
        "//third_party/org/codehaus/plexus:plexus_component_annotations",
        "//third_party/org/codehaus/plexus:plexus_interpolation",
        "//third_party/org/codehaus/plexus:plexus_utils",
    ],
)

scala_import(
    name = "maven_plugin_descriptor",
    jar = "@org_apache_maven_maven_plugin_descriptor//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/maven:maven_artifact",
        "//third_party/org/apache/maven:maven_plugin_api",
        "//third_party/org/codehaus/plexus:plexus_container_default",
    ],
)

scala_import(
    name = "maven_plugin_parameter_documenter",
    jar = "@org_apache_maven_maven_plugin_parameter_documenter//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/codehaus/plexus:plexus_container_default",
        "//third_party/org/codehaus/plexus:plexus_utils",
    ],
)

scala_import(
    name = "maven_monitor",
    jar = "@org_apache_maven_maven_monitor//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "maven_model",
    jar = "@org_apache_maven_maven_model//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/commons:commons_lang3",
        "//third_party/org/codehaus/plexus:plexus_utils",
    ],
)

scala_import(
    name = "maven_artifact",
    jar = "@org_apache_maven_maven_artifact//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/codehaus/plexus:plexus_utils",
    ],
)

scala_import(
    name = "maven_profile",
    jar = "@org_apache_maven_maven_profile//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/maven:maven_model",
        "//third_party/org/codehaus/plexus:plexus_container_default",
        "//third_party/org/codehaus/plexus:plexus_utils",
    ],
)
