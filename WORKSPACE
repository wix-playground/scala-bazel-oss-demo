
workspace(name = "koboshi")
rules_scala_version="4666a7e4efa6f7c9eaedf10863af23ce184111d3" # update this as needed

http_archive(
             name = "io_bazel_rules_scala",
             url = "https://github.com/wix/rules_scala/archive/%s.zip"%rules_scala_version,
             type = "zip",
             strip_prefix= "rules_scala-%s" % rules_scala_version
)
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_repositories")
scala_repositories()
load("@io_bazel_rules_scala//specs2:specs2_junit.bzl","specs2_junit_repositories")
specs2_junit_repositories()

maven_jar(
    name = "com_wix_hoopoe_http_http_testkit_2_11",
    artifact = "com.wix.hoopoe.http:http-testkit_2.11:0.0.1",
)

maven_jar(
    name = "jimfs",
    artifact = "com.google.jimfs:jimfs:1.1",
)

maven_jar(
    name = "guava",
    artifact = "com.google.guava:guava:18.0",
)

maven_jar(
    name = "commonsio",
    artifact = "commons-io:commons-io:jar:2.5",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_codebuild",
    artifact = "com.amazonaws:aws-java-sdk-codebuild:1.11.192",
)


maven_jar(
    name = "com_github_scopt_scopt_2_11",
    artifact = "com.github.scopt:scopt_2.11:3.7.0",
)


maven_jar(
    name = "org_mortbay_jetty_jetty",
    artifact = "org.mortbay.jetty:jetty:6.1.26",
)


maven_jar(
    name = "com_thoughtworks_paranamer_paranamer",
    artifact = "com.thoughtworks.paranamer:paranamer:2.8",
)


maven_jar(
    name = "com_google_api_grpc_grpc_google_common_protos",
    artifact = "com.google.api.grpc:grpc-google-common-protos:0.1.3",
)


maven_jar(
    name = "com_lmax_disruptor",
    artifact = "com.lmax:disruptor:3.0.1",
)


maven_jar(
    name = "mysql_mysql_connector_java",
    artifact = "mysql:mysql-connector-java:5.1.44",
)


maven_jar(
    name = "io_springfox_springfox_schema",
    artifact = "io.springfox:springfox-schema:2.7.0",
)


maven_jar(
    name = "org_springframework_spring_jms",
    artifact = "org.springframework:spring-jms:4.3.10.RELEASE",
)


maven_jar(
    name = "com_fasterxml_jackson_module_jackson_module_jaxb_annotations",
    artifact = "com.fasterxml.jackson.module:jackson-module-jaxb-annotations:2.8.8",
)


maven_jar(
    name = "com_github_jnr_jnr_constants",
    artifact = "com.github.jnr:jnr-constants:0.9.2",
)


maven_jar(
    name = "org_eclipse_jetty_jetty_servlets",
    artifact = "org.eclipse.jetty:jetty-servlets:9.3.17.v20170317",
)


maven_jar(
    name = "org_codehaus_jackson_jackson_mapper_asl",
    artifact = "org.codehaus.jackson:jackson-mapper-asl:1.9.13",
)


maven_jar(
    name = "org_apache_httpcomponents_httpclient",
    artifact = "org.apache.httpcomponents:httpclient:4.5.2",
)


maven_jar(
    name = "org_jmock_jmock_legacy",
    artifact = "org.jmock:jmock-legacy:2.8.3",
)


maven_jar(
    name = "org_mortbay_jetty_servlet_api",
    artifact = "org.mortbay.jetty:servlet-api:2.5-20081211",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_dms",
    artifact = "com.amazonaws:aws-java-sdk-dms:1.11.192",
)


maven_jar(
    name = "com_google_protobuf_protobuf_java_util",
    artifact = "com.google.protobuf:protobuf-java-util:3.0.0",
)


maven_jar(
    name = "org_springframework_spring_core",
    artifact = "org.springframework:spring-core:4.3.10.RELEASE",
)


maven_jar(
    name = "com_typesafe_play_play_streams_2_11",
    artifact = "com.typesafe.play:play-streams_2.11:2.6.3",
)


maven_jar(
    name = "com_google_api_client_google_api_client_appengine",
    artifact = "com.google.api-client:google-api-client-appengine:1.21.0",
)


maven_jar(
    name = "org_antlr_antlr",
    artifact = "org.antlr:antlr:3.2",
)


maven_jar(
    name = "antlr_antlr",
    artifact = "antlr:antlr:2.7.7",
)


maven_jar(
    name = "org_jmock_jmock_junit4",
    artifact = "org.jmock:jmock-junit4:2.8.3",
)


maven_jar(
    name = "io_dropwizard_metrics_metrics_core",
    artifact = "io.dropwizard.metrics:metrics-core:3.2.4",
)


maven_jar(
    name = "org_mongodb_mongo_java_driver",
    artifact = "org.mongodb:mongo-java-driver:3.2.1",
)


maven_jar(
    name = "org_apache_ant_ant_launcher",
    artifact = "org.apache.ant:ant-launcher:1.9.4",
)


maven_jar(
    name = "org_apache_lucene_lucene_misc",
    artifact = "org.apache.lucene:lucene-misc:4.8.1",
)


maven_jar(
    name = "com_google_http_client_google_http_client_jdo",
    artifact = "com.google.http-client:google-http-client-jdo:1.21.0",
)


maven_jar(
    name = "com_fasterxml_jackson_dataformat_jackson_dataformat_smile",
    artifact = "com.fasterxml.jackson.dataformat:jackson-dataformat-smile:2.8.8",
)


maven_jar(
    name = "org_eclipse_jetty_jetty_server",
    artifact = "org.eclipse.jetty:jetty-server:9.3.17.v20170317",
)


maven_jar(
    name = "org_apache_maven_reporting_maven_reporting_api",
    artifact = "org.apache.maven.reporting:maven-reporting-api:2.0.11",
)


maven_jar(
    name = "joda_time_joda_time",
    artifact = "joda-time:joda-time:2.9.9",
)


maven_jar(
    name = "com_google_protobuf_protobuf_java",
    artifact = "com.google.protobuf:protobuf-java:3.0.0",
)


maven_jar(
    name = "org_eclipse_jetty_http2_http2_http_client_transport",
    artifact = "org.eclipse.jetty.http2:http2-http-client-transport:9.3.17.v20170317",
)


maven_jar(
    name = "com_google_api_grpc_grpc_google_iam_v1",
    artifact = "com.google.api.grpc:grpc-google-iam-v1:0.1.3",
)


maven_jar(
    name = "log4j_log4j",
    artifact = "log4j:log4j:1.2.16",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_simpledb",
    artifact = "com.amazonaws:aws-java-sdk-simpledb:1.11.192",
)


maven_jar(
    name = "commons_cli_commons_cli",
    artifact = "commons-cli:commons-cli:1.0",
)


maven_jar(
    name = "slide_slide_webdavlib",
    artifact = "slide:slide-webdavlib:2.1",
)


maven_jar(
    name = "com_fasterxml_jackson_core_jackson_annotations",
    artifact = "com.fasterxml.jackson.core:jackson-annotations:2.8.8",
)


maven_jar(
    name = "org_springframework_spring_tx",
    artifact = "org.springframework:spring-tx:4.3.10.RELEASE",
)


maven_jar(
    name = "org_scala_lang_scala_library",
    artifact = "org.scala-lang:scala-library:2.11.11",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_cloudsearch",
    artifact = "com.amazonaws:aws-java-sdk-cloudsearch:1.11.192",
)


maven_jar(
    name = "com_sendgrid_sendgrid_java",
    artifact = "com.sendgrid:sendgrid-java:4.1.0",
)


maven_jar(
    name = "com_amazonaws_jmespath_java",
    artifact = "com.amazonaws:jmespath-java:1.11.192",
)


maven_jar(
    name = "org_ebaysf_web_cors_filter",
    artifact = "org.ebaysf.web:cors-filter:1.0.0",
)


maven_jar(
    name = "com_headius_invokebinder",
    artifact = "com.headius:invokebinder:1.7",
)


maven_jar(
    name = "org_eclipse_jetty_apache_jstl",
    artifact = "org.eclipse.jetty:apache-jstl:9.3.17.v20170317",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_devicefarm",
    artifact = "com.amazonaws:aws-java-sdk-devicefarm:1.11.192",
)


maven_jar(
    name = "javax_mail_mail",
    artifact = "javax.mail:mail:1.4.7",
)


maven_jar(
    name = "com_google_cloud_google_cloud_language",
    artifact = "com.google.cloud:google-cloud-language:0.8.0",
)


maven_jar(
    name = "com_google_cloud_datastore_datastore_v1_protos",
    artifact = "com.google.cloud.datastore:datastore-v1-protos:1.3.0",
)


maven_jar(
    name = "com_sendgrid_java_http_client",
    artifact = "com.sendgrid:java-http-client:4.1.0",
)


maven_jar(
    name = "commons_validator_commons_validator",
    artifact = "commons-validator:commons-validator:1.6",
)


maven_jar(
    name = "ehcache_ehcache",
    artifact = "ehcache:ehcache:1.1",
)


maven_jar(
    name = "org_springframework_plugin_spring_plugin_core",
    artifact = "org.springframework.plugin:spring-plugin-core:1.2.0.RELEASE",
)


maven_jar(
    name = "org_mongodb_casbah_2_11",
    artifact = "org.mongodb:casbah_2.11:pom:3.1.1",
)


maven_jar(
    name = "com_typesafe_akka_akka_actor_2_11",
    artifact = "com.typesafe.akka:akka-actor_2.11:2.5.4",
)


maven_jar(
    name = "com_twitter_util_core_2_11",
    artifact = "com.twitter:util-core_2.11:7.0.0",
)


maven_jar(
    name = "org_jruby_jruby_core",
    artifact = "org.jruby:jruby-core:9.1.2.0",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_config",
    artifact = "com.amazonaws:aws-java-sdk-config:1.11.192",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_budgets",
    artifact = "com.amazonaws:aws-java-sdk-budgets:1.11.192",
)


maven_jar(
    name = "org_apache_kafka_kafka_clients",
    artifact = "org.apache.kafka:kafka-clients:0.10.2.1",
)


maven_jar(
    name = "org_hamcrest_hamcrest_core",
    artifact = "org.hamcrest:hamcrest-core:1.3",
)


maven_jar(
    name = "org_apache_cassandra_cassandra_all",
    artifact = "org.apache.cassandra:cassandra-all:2.0.17",
)


maven_jar(
    name = "com_google_api_gax",
    artifact = "com.google.api:gax:0.0.25",
)


maven_jar(
    name = "org_scalikejdbc_scalikejdbc_interpolation_2_11",
    artifact = "org.scalikejdbc:scalikejdbc-interpolation_2.11:2.5.2",
)


maven_jar(
    name = "com_typesafe_akka_akka_parsing_2_11",
    artifact = "com.typesafe.akka:akka-parsing_2.11:10.0.10",
)


maven_jar(
    name = "org_json4s_json4s_native_2_11",
    artifact = "org.json4s:json4s-native_2.11:3.5.3",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_ssm",
    artifact = "com.amazonaws:aws-java-sdk-ssm:1.11.192",
)


maven_jar(
    name = "com_google_apis_google_api_services_translate",
    artifact = "com.google.apis:google-api-services-translate:v2-rev47-1.22.0",
)


maven_jar(
    name = "org_mongodb_casbah_core_2_11",
    artifact = "org.mongodb:casbah-core_2.11:3.1.1",
)


maven_jar(
    name = "commons_collections_commons_collections",
    artifact = "commons-collections:commons-collections:3.2.2",
)


maven_jar(
    name = "com_github_stephenc_high_scale_lib_high_scale_lib",
    artifact = "com.github.stephenc.high-scale-lib:high-scale-lib:1.1.2",
)


maven_jar(
    name = "redis_clients_jedis",
    artifact = "redis.clients:jedis:2.9.0",
)


maven_jar(
    name = "javax_annotation_javax_annotation_api",
    artifact = "javax.annotation:javax.annotation-api:1.2",
)


maven_jar(
    name = "org_ow2_asm_asm_tree",
    artifact = "org.ow2.asm:asm-tree:5.0.1",
)


maven_jar(
    name = "com_typesafe_play_play_exceptions",
    artifact = "com.typesafe.play:play-exceptions:2.6.3",
)


maven_jar(
    name = "javax_servlet_jstl",
    artifact = "javax.servlet:jstl:1.2",
)


maven_jar(
    name = "com_yammer_metrics_metrics_core",
    artifact = "com.yammer.metrics:metrics-core:2.2.0",
)


maven_jar(
    name = "org_codehaus_jackson_jackson_core_asl",
    artifact = "org.codehaus.jackson:jackson-core-asl:1.9.2",
)


maven_jar(
    name = "org_specs2_specs2_analysis_2_11",
    artifact = "org.specs2:specs2-analysis_2.11:3.8.6",
)


maven_jar(
    name = "net_minidev_json_smart",
    artifact = "net.minidev:json-smart:1.1.1",
)


maven_jar(
    name = "cglib_cglib",
    artifact = "cglib:cglib:3.2.0",
)


maven_jar(
    name = "com_github_jnr_jnr_unixsocket",
    artifact = "com.github.jnr:jnr-unixsocket:0.12",
)


maven_jar(
    name = "com_typesafe_akka_akka_cluster_metrics_2_11",
    artifact = "com.typesafe.akka:akka-cluster-metrics_2.11:2.5.4",
)


maven_jar(
    name = "org_scala_lang_modules_scala_java8_compat_2_11",
    artifact = "org.scala-lang.modules:scala-java8-compat_2.11:0.7.0",
)


maven_jar(
    name = "org_slf4j_jul_to_slf4j",
    artifact = "org.slf4j:jul-to-slf4j:1.7.25",
)

maven_jar(
    name = "org_springframework_spring_jdbc",
    artifact = "org.springframework:spring-jdbc:4.3.10.RELEASE",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_core",
    artifact = "com.amazonaws:aws-java-sdk-core:1.11.192",
)


maven_jar(
    name = "org_reactivemongo_reactivemongo_bson_2_11",
    artifact = "org.reactivemongo:reactivemongo-bson_2.11:0.10.5.0.akka23",
)


maven_jar(
    name = "org_apache_maven_maven_builder_support",
    artifact = "org.apache.maven:maven-builder-support:3.5.0",
)


maven_jar(
    name = "org_objenesis_objenesis",
    artifact = "org.objenesis:objenesis:2.6",
)


maven_jar(
    name = "org_slf4j_slf4j_simple",
    artifact = "org.slf4j:slf4j-simple:1.7.2",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_emr",
    artifact = "com.amazonaws:aws-java-sdk-emr:1.11.192",
)


maven_jar(
    name = "org_specs2_specs2_matcher_extra_2_11",
    artifact = "org.specs2:specs2-matcher-extra_2.11:3.8.6",
)


maven_jar(
    name = "org_apache_ant_ant",
    artifact = "org.apache.ant:ant:1.9.4",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_workdocs",
    artifact = "com.amazonaws:aws-java-sdk-workdocs:1.11.192",
)


maven_jar(
    name = "org_eclipse_jetty_jetty_alpn_client",
    artifact = "org.eclipse.jetty:jetty-alpn-client:9.3.17.v20170317",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_resourcegroupstaggingapi",
    artifact = "com.amazonaws:aws-java-sdk-resourcegroupstaggingapi:1.11.192",
)


maven_jar(
    name = "io_springfox_springfox_swagger2",
    artifact = "io.springfox:springfox-swagger2:2.7.0",
)


maven_jar(
    name = "ch_qos_logback_logback_core",
    artifact = "ch.qos.logback:logback-core:1.0.13",
)


maven_jar(
    name = "net_sf_jopt_simple_jopt_simple",
    artifact = "net.sf.jopt-simple:jopt-simple:4.9",
)


maven_jar(
    name = "org_bitbucket_b_c_jose4j",
    artifact = "org.bitbucket.b_c:jose4j:0.5.0",
)


maven_jar(
    name = "com_martiansoftware_nailgun_server",
    artifact = "com.martiansoftware:nailgun-server:0.9.1",
)


maven_jar(
    name = "org_apache_maven_wagon_wagon_webdav",
    artifact = "org.apache.maven.wagon:wagon-webdav:1.0-beta-2",
)


maven_jar(
    name = "org_jmock_jmock_testjar",
    artifact = "org.jmock:jmock-testjar:2.8.3",
)


maven_jar(
    name = "org_json4s_json4s_ast_2_11",
    artifact = "org.json4s:json4s-ast_2.11:3.5.3",
)


maven_jar(
    name = "com_h2database_h2",
    artifact = "com.h2database:h2:1.3.176",
)


maven_jar(
    name = "io_grpc_grpc_protobuf_lite",
    artifact = "io.grpc:grpc-protobuf-lite:1.0.1",
)


maven_jar(
    name = "com_google_apis_google_api_services_compute",
    artifact = "com.google.apis:google-api-services-compute:v1-rev103-1.21.0",
)


maven_jar(
    name = "io_springfox_springfox_swagger_common",
    artifact = "io.springfox:springfox-swagger-common:2.7.0",
)


maven_jar(
    name = "org_springframework_spring_expression",
    artifact = "org.springframework:spring-expression:4.3.10.RELEASE",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_dynamodb",
    artifact = "com.amazonaws:aws-java-sdk-dynamodb:1.11.192",
)


maven_jar(
    name = "org_apache_curator_curator_client",
    artifact = "org.apache.curator:curator-client:2.12.0",
)


maven_jar(
    name = "org_aspectj_aspectjrt",
    artifact = "org.aspectj:aspectjrt:1.8.10",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_snowball",
    artifact = "com.amazonaws:aws-java-sdk-snowball:1.11.192",
)


maven_jar(
    name = "com_google_collections_google_collections",
    artifact = "com.google.collections:google-collections:1.0",
)


maven_jar(
    name = "net_sf_json_lib_json_lib",
    artifact = "net.sf.json-lib:json-lib:jar:jdk15:2.4",
)


maven_jar(
    name = "com_google_cloud_google_cloud_compute",
    artifact = "com.google.cloud:google-cloud-compute:0.8.0",
)


maven_jar(
    name = "com_google_api_grpc_grpc_google_cloud_error_reporting_v1beta1",
    artifact = "com.google.api.grpc:grpc-google-cloud-error-reporting-v1beta1:0.1.3",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_directconnect",
    artifact = "com.amazonaws:aws-java-sdk-directconnect:1.11.192",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_directory",
    artifact = "com.amazonaws:aws-java-sdk-directory:1.11.192",
)


maven_jar(
    name = "javax_mail_javax_mail_api",
    artifact = "javax.mail:javax.mail-api:1.6.0",
)


maven_jar(
    name = "com_google_http_client_google_http_client_appengine",
    artifact = "com.google.http-client:google-http-client-appengine:1.21.0",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_inspector",
    artifact = "com.amazonaws:aws-java-sdk-inspector:1.11.192",
)


maven_jar(
    name = "net_sf_supercsv_super_csv",
    artifact = "net.sf.supercsv:super-csv:2.1.0",
)


maven_jar(
    name = "org_asynchttpclient_netty_resolver_dns",
    artifact = "org.asynchttpclient:netty-resolver-dns:2.0.35",
)


maven_jar(
    name = "io_netty_netty_handler",
    artifact = "io.netty:netty-handler:4.0.27.Final",
)


maven_jar(
    name = "com_google_api_grpc_grpc_google_cloud_speech_v1beta1",
    artifact = "com.google.api.grpc:grpc-google-cloud-speech-v1beta1:0.1.3",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_opsworks",
    artifact = "com.amazonaws:aws-java-sdk-opsworks:1.11.192",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_simpleworkflow",
    artifact = "com.amazonaws:aws-java-sdk-simpleworkflow:1.11.192",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_sns",
    artifact = "com.amazonaws:aws-java-sdk-sns:1.11.192",
)


maven_jar(
    name = "com_squareup_okhttp3_okhttp",
    artifact = "com.squareup.okhttp3:okhttp:3.8.1",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_organizations",
    artifact = "com.amazonaws:aws-java-sdk-organizations:1.11.192",
)


maven_jar(
    name = "com_google_maps_google_maps_services",
    artifact = "com.google.maps:google-maps-services:0.2.4",
)


maven_jar(
    name = "io_swagger_swagger_annotations",
    artifact = "io.swagger:swagger-annotations:1.5.13",
)


maven_jar(
    name = "aopalliance_aopalliance",
    artifact = "aopalliance:aopalliance:1.0",
)


maven_jar(
    name = "commons_beanutils_commons_beanutils_core",
    artifact = "commons-beanutils:commons-beanutils-core:1.8.3",
)


maven_jar(
    name = "org_apache_commons_commons_dbcp2",
    artifact = "org.apache.commons:commons-dbcp2:2.1.1",
)


maven_jar(
    name = "org_apache_taglibs_taglibs_standard_impl",
    artifact = "org.apache.taglibs:taglibs-standard-impl:1.2.5",
)


maven_jar(
    name = "com_typesafe_play_play_functional_2_11",
    artifact = "com.typesafe.play:play-functional_2.11:2.6.3",
)


maven_jar(
    name = "oro_oro",
    artifact = "oro:oro:2.0.6",
)


maven_jar(
    name = "com_googlecode_libphonenumber_libphonenumber",
    artifact = "com.googlecode.libphonenumber:libphonenumber:8.8.3",
)


maven_jar(
    name = "org_eclipse_jetty_http2_http2_common",
    artifact = "org.eclipse.jetty.http2:http2-common:9.3.17.v20170317",
)


maven_jar(
    name = "com_typesafe_play_play_2_11",
    artifact = "com.typesafe.play:play_2.11:2.6.3",
)


maven_jar(
    name = "io_springfox_springfox_spring_web",
    artifact = "io.springfox:springfox-spring-web:2.7.0",
)


maven_jar(
    name = "de_heikoseeberger_akka_http_json4s_2_11",
    artifact = "de.heikoseeberger:akka-http-json4s_2.11:1.17.0",
)


maven_jar(
    name = "com_google_apis_google_api_services_dns",
    artifact = "com.google.apis:google-api-services-dns:v1-rev7-1.21.0",
)


maven_jar(
    name = "org_apache_extras_beanshell_bsh",
    artifact = "org.apache-extras.beanshell:bsh:2.0b6",
)


maven_jar(
    name = "com_zaxxer_HikariCP",
    artifact = "com.zaxxer:HikariCP:2.6.3",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_clouddirectory",
    artifact = "com.amazonaws:aws-java-sdk-clouddirectory:1.11.192",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_ses",
    artifact = "com.amazonaws:aws-java-sdk-ses:1.11.192",
)


maven_jar(
    name = "org_mongodb_casbah_query_2_11",
    artifact = "org.mongodb:casbah-query_2.11:3.1.1",
)


maven_jar(
    name = "io_aeron_aeron_driver",
    artifact = "io.aeron:aeron-driver:1.2.5",
)


maven_jar(
    name = "com_carbonfive_db_support_db_support",
    artifact = "com.carbonfive.db-support:db-support:0.9.9-m5",
)


maven_jar(
    name = "org_json4s_json4s_scalap_2_11",
    artifact = "org.json4s:json4s-scalap_2.11:3.5.3",
)


maven_jar(
    name = "com_google_auth_google_auth_library_oauth2_http",
    artifact = "com.google.auth:google-auth-library-oauth2-http:0.6.0",
)


maven_jar(
    name = "com_fasterxml_jackson_datatype_jackson_datatype_jsr310",
    artifact = "com.fasterxml.jackson.datatype:jackson-datatype-jsr310:2.8.8",
)


maven_jar(
    name = "com_google_cloud_google_cloud_datastore",
    artifact = "com.google.cloud:google-cloud-datastore:0.8.0-beta",
)


maven_jar(
    name = "com_readytalk_metrics3_statsd",
    artifact = "com.readytalk:metrics3-statsd:4.1.0",
)


maven_jar(
    name = "org_mortbay_jasper_apache_el",
    artifact = "org.mortbay.jasper:apache-el:8.0.33",
)


maven_jar(
    name = "xmlunit_xmlunit",
    artifact = "xmlunit:xmlunit:1.6",
)


maven_jar(
    name = "edu_stanford_ppl_snaptree",
    artifact = "edu.stanford.ppl:snaptree:0.1",
)


maven_jar(
    name = "hibernate_antlr",
    artifact = "hibernate:antlr:2.7.5H3",
)


maven_jar(
    name = "commons_digester_commons_digester",
    artifact = "commons-digester:commons-digester:1.8.1",
)


maven_jar(
    name = "org_codehaus_plexus_plexus_classworlds",
    artifact = "org.codehaus.plexus:plexus-classworlds:2.5.1",
)


maven_jar(
    name = "org_apache_curator_curator_x_discovery",
    artifact = "org.apache.curator:curator-x-discovery:2.12.0",
)


maven_jar(
    name = "io_springfox_springfox_spi",
    artifact = "io.springfox:springfox-spi:2.7.0",
)


maven_jar(
    name = "org_apache_curator_curator_framework",
    artifact = "org.apache.curator:curator-framework:2.12.0",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_cognitoidp",
    artifact = "com.amazonaws:aws-java-sdk-cognitoidp:1.11.192",
)


maven_jar(
    name = "org_springframework_spring_orm",
    artifact = "org.springframework:spring-orm:4.3.10.RELEASE",
)


maven_jar(
    name = "org_apache_xbean_xbean_reflect",
    artifact = "org.apache.xbean:xbean-reflect:3.7",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_appstream",
    artifact = "com.amazonaws:aws-java-sdk-appstream:1.11.192",
)


maven_jar(
    name = "javax_xml_bind_jaxb_api",
    artifact = "javax.xml.bind:jaxb-api:2.2",
)


maven_jar(
    name = "io_netty_netty_codec_http2",
    artifact = "io.netty:netty-codec-http2:4.1.3.Final",
)


maven_jar(
    name = "org_apache_maven_maven_plugin_api",
    artifact = "org.apache.maven:maven-plugin-api:2.0.11",
)


maven_jar(
    name = "com_orange_redis_embedded_embedded_redis",
    artifact = "com.orange.redis-embedded:embedded-redis:0.6",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_swf_libraries",
    artifact = "com.amazonaws:aws-java-sdk-swf-libraries:1.11.22",
)


maven_jar(
    name = "io_jsonwebtoken_jjwt",
    artifact = "io.jsonwebtoken:jjwt:0.7.0",
)


maven_jar(
    name = "io_netty_netty_transport_native_epoll",
    artifact = "io.netty:netty-transport-native-epoll:jar:linux-x86_64:4.0.51.Final",
)


maven_jar(
    name = "asm_asm",
    artifact = "asm:asm:1.4.3",
)


maven_jar(
    name = "org_scala_lang_modules_scala_parser_combinators_2_11",
    artifact = "org.scala-lang.modules:scala-parser-combinators_2.11:1.0.6",
)


maven_jar(
    name = "com_typesafe_akka_akka_http_core_2_11",
    artifact = "com.typesafe.akka:akka-http-core_2.11:10.0.10",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_efs",
    artifact = "com.amazonaws:aws-java-sdk-efs:1.11.192",
)


maven_jar(
    name = "com_typesafe_akka_akka_slf4j_2_11",
    artifact = "com.typesafe.akka:akka-slf4j_2.11:2.5.4",
)


maven_jar(
    name = "org_springframework_spring_messaging",
    artifact = "org.springframework:spring-messaging:4.3.10.RELEASE",
)


maven_jar(
    name = "org_scala_lang_scala_compiler",
    artifact = "org.scala-lang:scala-compiler:2.11.11",
)


maven_jar(
    name = "com_google_cloud_google_cloud_errorreporting",
    artifact = "com.google.cloud:google-cloud-errorreporting:0.8.0",
)


maven_jar(
    name = "io_grpc_grpc_stub",
    artifact = "io.grpc:grpc-stub:1.0.1",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_importexport",
    artifact = "com.amazonaws:aws-java-sdk-importexport:1.11.192",
)


maven_jar(
    name = "org_org_libs_org_lib_usurper",
    artifact = "org.org-libs:org-lib-usurper:1.1.0",
)


maven_jar(
    name = "net_sf_opencsv_opencsv",
    artifact = "net.sf.opencsv:opencsv:2.3",
)


maven_jar(
    name = "io_spray_spray_util_2_11",
    artifact = "io.spray:spray-util_2.11:1.3.4",
)


maven_jar(
    name = "com_google_api_grpc_grpc_google_cloud_trace_v1",
    artifact = "com.google.api.grpc:grpc-google-cloud-trace-v1:0.1.3",
)


maven_jar(
    name = "org_scalikejdbc_scalikejdbc_test_2_11",
    artifact = "org.scalikejdbc:scalikejdbc-test_2.11:2.5.2",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_lex",
    artifact = "com.amazonaws:aws-java-sdk-lex:1.11.192",
)


maven_jar(
    name = "com_google_cloud_google_cloud_resourcemanager",
    artifact = "com.google.cloud:google-cloud-resourcemanager:0.8.0",
)


maven_jar(
    name = "joda_time_joda_time_hibernate",
    artifact = "joda-time:joda-time-hibernate:1.2",
)


maven_jar(
    name = "com_github_pathikrit_better_files_2_11",
    artifact = "com.github.pathikrit:better-files_2.11:2.17.1",
)


maven_jar(
    name = "com_google_http_client_google_http_client_jackson2",
    artifact = "com.google.http-client:google-http-client-jackson2:1.19.0",
)


maven_jar(
    name = "org_apache_maven_wagon_wagon_ssh_external",
    artifact = "org.apache.maven.wagon:wagon-ssh-external:1.0-beta-2",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_storagegateway",
    artifact = "com.amazonaws:aws-java-sdk-storagegateway:1.11.192",
)


maven_jar(
    name = "com_typesafe_play_twirl_api_2_11",
    artifact = "com.typesafe.play:twirl-api_2.11:1.3.4",
)


maven_jar(
    name = "org_apache_lucene_lucene_highlighter",
    artifact = "org.apache.lucene:lucene-highlighter:4.8.1",
)


maven_jar(
    name = "com_google_cloud_google_cloud_speech",
    artifact = "com.google.cloud:google-cloud-speech:0.8.0",
)


maven_jar(
    name = "com_google_appengine_appengine_api_labs",
    artifact = "com.google.appengine:appengine-api-labs:1.9.57",
)


maven_jar(
    name = "com_google_appengine_appengine_endpoints",
    artifact = "com.google.appengine:appengine-endpoints:1.9.57",
)


maven_jar(
    name = "com_github_jnr_jnr_enxio",
    artifact = "com.github.jnr:jnr-enxio:0.12",
)


maven_jar(
    name = "com_typesafe_akka_akka_cluster_2_11",
    artifact = "com.typesafe.akka:akka-cluster_2.11:2.5.4",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_gamelift",
    artifact = "com.amazonaws:aws-java-sdk-gamelift:1.11.192",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_acm",
    artifact = "com.amazonaws:aws-java-sdk-acm:1.11.192",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_ecs",
    artifact = "com.amazonaws:aws-java-sdk-ecs:1.11.192",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_iam",
    artifact = "com.amazonaws:aws-java-sdk-iam:1.11.192",
)


maven_jar(
    name = "com_github_jnr_jnr_x86asm",
    artifact = "com.github.jnr:jnr-x86asm:1.0.2",
)


maven_jar(
    name = "org_jruby_jruby_stdlib",
    artifact = "org.jruby:jruby-stdlib:9.1.2.0",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_rds",
    artifact = "com.amazonaws:aws-java-sdk-rds:1.11.192",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_lambda",
    artifact = "com.amazonaws:aws-java-sdk-lambda:1.11.192",
)


maven_jar(
    name = "com_typesafe_akka_akka_stream_2_11",
    artifact = "com.typesafe.akka:akka-stream_2.11:2.5.4",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_xray",
    artifact = "com.amazonaws:aws-java-sdk-xray:1.11.192",
)


maven_jar(
    name = "com_datastax_cassandra_cassandra_driver_core",
    artifact = "com.datastax.cassandra:cassandra-driver-core:2.1.9",
)


maven_jar(
    name = "com_google_api_grpc_grpc_google_cloud_logging_v2",
    artifact = "com.google.api.grpc:grpc-google-cloud-logging-v2:0.1.4",
)


maven_jar(
    name = "com_google_auth_google_auth_library_credentials",
    artifact = "com.google.auth:google-auth-library-credentials:0.6.0",
)


maven_jar(
    name = "org_javassist_javassist",
    artifact = "org.javassist:javassist:3.21.0-GA",
)


maven_jar(
    name = "org_scalatest_scalatest_2_11",
    artifact = "org.scalatest:scalatest_2.11:2.2.6",
)


maven_jar(
    name = "com_github_jnr_jffi",
    artifact = "com.github.jnr:jffi:1.2.12",
)


maven_jar(
    name = "commons_fileupload_commons_fileupload",
    artifact = "commons-fileupload:commons-fileupload:1.3.3",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_iot",
    artifact = "com.amazonaws:aws-java-sdk-iot:1.11.192",
)


maven_jar(
    name = "com_fasterxml_jackson_core_jackson_databind",
    artifact = "com.fasterxml.jackson.core:jackson-databind:2.8.8",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_lexmodelbuilding",
    artifact = "com.amazonaws:aws-java-sdk-lexmodelbuilding:1.11.192",
)


maven_jar(
    name = "org_scala_stm_scala_stm_2_10",
    artifact = "org.scala-stm:scala-stm_2.10:0.7",
)


maven_jar(
    name = "io_grpc_grpc_core",
    artifact = "io.grpc:grpc-core:1.0.1",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_codedeploy",
    artifact = "com.amazonaws:aws-java-sdk-codedeploy:1.11.192",
)


maven_jar(
    name = "com_readytalk_metrics_statsd_common",
    artifact = "com.readytalk:metrics-statsd-common:4.1.0",
)


maven_jar(
    name = "org_ow2_asm_asm",
    artifact = "org.ow2.asm:asm:5.2",
)


maven_jar(
    name = "org_ow2_asm_asm_commons",
    artifact = "org.ow2.asm:asm-commons:5.0.1",
)


maven_jar(
    name = "com_squareup_okio_okio",
    artifact = "com.squareup.okio:okio:1.13.0",
)


maven_jar(
    name = "com_googlecode_concurrentlinkedhashmap_concurrentlinkedhashmap_lru",
    artifact = "com.googlecode.concurrentlinkedhashmap:concurrentlinkedhashmap-lru:1.3",
)


maven_jar(
    name = "com_fasterxml_classmate",
    artifact = "com.fasterxml:classmate:1.3.3",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_athena",
    artifact = "com.amazonaws:aws-java-sdk-athena:1.11.192",
)


maven_jar(
    name = "org_json4s_json4s_core_2_11",
    artifact = "org.json4s:json4s-core_2.11:3.5.3",
)


maven_jar(
    name = "javax_transaction_transaction_api",
    artifact = "javax.transaction:transaction-api:1.1",
)


maven_jar(
    name = "com_fasterxml_jackson_datatype_jackson_datatype_jdk8",
    artifact = "com.fasterxml.jackson.datatype:jackson-datatype-jdk8:2.8.8",
)


maven_jar(
    name = "org_hamcrest_hamcrest_all",
    artifact = "org.hamcrest:hamcrest-all:1.3",
)


maven_jar(
    name = "org_json_json",
    artifact = "org.json:json:20151123",
)


maven_jar(
    name = "org_apache_cassandra_cassandra_thrift",
    artifact = "org.apache.cassandra:cassandra-thrift:2.0.17",
)


maven_jar(
    name = "com_mchange_mchange_commons_java",
    artifact = "com.mchange:mchange-commons-java:0.2.11",
)


maven_jar(
    name = "org_apache_maven_maven_repository_metadata",
    artifact = "org.apache.maven:maven-repository-metadata:2.0.11",
)


maven_jar(
    name = "com_github_jnr_jnr_posix",
    artifact = "com.github.jnr:jnr-posix:3.0.29",
)


maven_jar(
    name = "io_netty_netty_tcnative_boringssl_static",
    artifact = "io.netty:netty-tcnative-boringssl-static:1.1.33.Fork19",
)


maven_jar(
    name = "org_apache_maven_maven_artifact_manager",
    artifact = "org.apache.maven:maven-artifact-manager:2.0.11",
)


maven_jar(
    name = "org_scala_sbt_test_interface",
    artifact = "org.scala-sbt:test-interface:1.0",
)


maven_jar(
    name = "org_reactivemongo_reactivemongo_2_11",
    artifact = "org.reactivemongo:reactivemongo_2.11:0.10.5.0.akka23",
)


maven_jar(
    name = "commons_beanutils_commons_beanutils",
    artifact = "commons-beanutils:commons-beanutils:1.9.3",
)


maven_jar(
    name = "com_ning_compress_lzf",
    artifact = "com.ning:compress-lzf:0.8.4",
)


maven_jar(
    name = "org_eclipse_jetty_jetty_jmx",
    artifact = "org.eclipse.jetty:jetty-jmx:9.3.17.v20170317",
)


maven_jar(
    name = "org_eclipse_jetty_jetty_io",
    artifact = "org.eclipse.jetty:jetty-io:9.3.17.v20170317",
)


maven_jar(
    name = "com_google_cloud_google_cloud_vision",
    artifact = "com.google.cloud:google-cloud-vision:0.8.0",
)


maven_jar(
    name = "org_springframework_spring_oxm",
    artifact = "org.springframework:spring-oxm:4.3.10.RELEASE",
)


maven_jar(
    name = "io_netty_netty_codec",
    artifact = "io.netty:netty-codec:4.0.27.Final",
)


maven_jar(
    name = "org_scalaz_scalaz_effect_2_11",
    artifact = "org.scalaz:scalaz-effect_2.11:7.2.7",
)


maven_jar(
    name = "org_skyscreamer_jsonassert",
    artifact = "org.skyscreamer:jsonassert:1.2.3",
)


maven_jar(
    name = "javax_inject_javax_inject",
    artifact = "javax.inject:javax.inject:1",
)


maven_jar(
    name = "com_google_api_api_common",
    artifact = "com.google.api:api-common:0.0.2",
)


maven_jar(
    name = "commons_logging_commons_logging",
    artifact = "commons-logging:commons-logging:1.2",
)


maven_jar(
    name = "org_apache_maven_wagon_wagon_ssh",
    artifact = "org.apache.maven.wagon:wagon-ssh:1.0-beta-2",
)


maven_jar(
    name = "com_mchange_c3p0",
    artifact = "com.mchange:c3p0:0.9.5.2",
)


maven_jar(
    name = "org_apache_maven_wagon_wagon_http_lightweight",
    artifact = "org.apache.maven.wagon:wagon-http-lightweight:1.0-beta-2",
)


maven_jar(
    name = "io_dropwizard_metrics_metrics_graphite",
    artifact = "io.dropwizard.metrics:metrics-graphite:3.2.4",
)


maven_jar(
    name = "org_eclipse_jetty_jetty_plus",
    artifact = "org.eclipse.jetty:jetty-plus:9.3.17.v20170317",
)


maven_jar(
    name = "com_typesafe_ssl_config_core_2_11",
    artifact = "com.typesafe:ssl-config-core_2.11:0.2.1",
)


maven_jar(
    name = "org_specs2_specs2_codata_2_11",
    artifact = "org.specs2:specs2-codata_2.11:3.8.6",
)


maven_jar(
    name = "org_apache_activemq_activemq_jms_pool",
    artifact = "org.apache.activemq:activemq-jms-pool:5.15.0",
)


maven_jar(
    name = "com_google_auto_value_auto_value",
    artifact = "com.google.auto.value:auto-value:1.2",
)


maven_jar(
    name = "org_codehaus_plexus_plexus_interpolation",
    artifact = "org.codehaus.plexus:plexus-interpolation:1.24",
)


maven_jar(
    name = "com_googlecode_json_simple_json_simple",
    artifact = "com.googlecode.json-simple:json-simple:1.1",
)


maven_jar(
    name = "org_apache_geronimo_specs_geronimo_jta_1_0_1B_spec",
    artifact = "org.apache.geronimo.specs:geronimo-jta_1.0.1B_spec:1.0.1",
)


maven_jar(
    name = "org_aspectj_aspectjweaver",
    artifact = "org.aspectj:aspectjweaver:1.8.10",
)


maven_jar(
    name = "com_google_cloud_datastore_datastore_v1_proto_client",
    artifact = "com.google.cloud.datastore:datastore-v1-proto-client:1.3.0",
)


maven_jar(
    name = "com_typesafe_play_play_netty_utils",
    artifact = "com.typesafe.play:play-netty-utils:2.6.3",
)


maven_jar(
    name = "org_eclipse_jdt_core_compiler_ecj",
    artifact = "org.eclipse.jdt.core.compiler:ecj:4.4.2",
)


maven_jar(
    name = "org_eclipse_jetty_http2_http2_hpack",
    artifact = "org.eclipse.jetty.http2:http2-hpack:9.3.17.v20170317",
)


maven_jar(
    name = "com_typesafe_play_play_json_2_11",
    artifact = "com.typesafe.play:play-json_2.11:2.6.3",
)


maven_jar(
    name = "org_apache_lucene_lucene_memory",
    artifact = "org.apache.lucene:lucene-memory:4.8.1",
)


maven_jar(
    name = "org_codehaus_plexus_plexus_utils",
    artifact = "org.codehaus.plexus:plexus-utils:1.5.6",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_workspaces",
    artifact = "com.amazonaws:aws-java-sdk-workspaces:1.11.192",
)


maven_jar(
    name = "com_google_cloud_google_cloud_dns",
    artifact = "com.google.cloud:google-cloud-dns:0.8.0",
)


maven_jar(
    name = "com_googlecode_xmemcached_xmemcached",
    artifact = "com.googlecode.xmemcached:xmemcached:2.3.2",
)


maven_jar(
    name = "org_apache_lucene_lucene_queryparser",
    artifact = "org.apache.lucene:lucene-queryparser:4.8.1",
)


maven_jar(
    name = "org_mongodb_casbah_commons_2_11",
    artifact = "org.mongodb:casbah-commons_2.11:3.1.1",
)


maven_jar(
    name = "org_apache_commons_commons_pool2",
    artifact = "org.apache.commons:commons-pool2:2.4.2",
)


maven_jar(
    name = "com_fasterxml_jackson_core_jackson_core",
    artifact = "com.fasterxml.jackson.core:jackson-core:2.8.8",
)


maven_jar(
    name = "org_specs2_specs2_matcher_2_11",
    artifact = "org.specs2:specs2-matcher_2.11:3.8.6",
)


maven_jar(
    name = "org_mindrot_jbcrypt",
    artifact = "org.mindrot:jbcrypt:0.3m",
)


maven_jar(
    name = "io_netty_netty_codec_http",
    artifact = "io.netty:netty-codec-http:4.0.51.Final",
)


maven_jar(
    name = "com_typesafe_akka_akka_http_2_11",
    artifact = "com.typesafe.akka:akka-http_2.11:10.0.10",
)


maven_jar(
    name = "javax_xml_stream_stax_api",
    artifact = "javax.xml.stream:stax-api:1.0-2",
)


maven_jar(
    name = "com_fasterxml_jackson_dataformat_jackson_dataformat_xml",
    artifact = "com.fasterxml.jackson.dataformat:jackson-dataformat-xml:2.8.8",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_waf",
    artifact = "com.amazonaws:aws-java-sdk-waf:1.11.192",
)


maven_jar(
    name = "commons_jxpath_commons_jxpath",
    artifact = "commons-jxpath:commons-jxpath:1.3",
)


maven_jar(
    name = "xml_apis_xml_apis",
    artifact = "xml-apis:xml-apis:1.0.b2",
)


maven_jar(
    name = "commons_lang_commons_lang",
    artifact = "commons-lang:commons-lang:2.6",
)


maven_jar(
    name = "org_apache_maven_maven_plugin_descriptor",
    artifact = "org.apache.maven:maven-plugin-descriptor:2.0.11",
)


maven_jar(
    name = "org_apache_logging_log4j_log4j_core",
    artifact = "org.apache.logging.log4j:log4j-core:2.0.2",
)


maven_jar(
    name = "com_google_api_grpc_grpc_google_cloud_language_v1",
    artifact = "com.google.api.grpc:grpc-google-cloud-language-v1:0.1.3",
)


maven_jar(
    name = "org_eclipse_jetty_jetty_servlet",
    artifact = "org.eclipse.jetty:jetty-servlet:9.3.17.v20170317",
)


maven_jar(
    name = "org_elasticsearch_elasticsearch",
    artifact = "org.elasticsearch:elasticsearch:1.2.2",
)


maven_jar(
    name = "commons_net_commons_net",
    artifact = "commons-net:commons-net:3.6",
)


maven_jar(
    name = "org_mortbay_jetty_jetty_util",
    artifact = "org.mortbay.jetty:jetty-util:6.1.26",
)


maven_jar(
    name = "org_json4s_json4s_jackson_2_11",
    artifact = "org.json4s:json4s-jackson_2.11:3.5.3",
)


maven_jar(
    name = "com_google_oauth_client_google_oauth_client",
    artifact = "com.google.oauth-client:google-oauth-client:1.21.0",
)


maven_jar(
    name = "com_twilio_sdk_twilio",
    artifact = "com.twilio.sdk:twilio:7.15.1",
)


maven_jar(
    name = "org_apache_maven_maven_profile",
    artifact = "org.apache.maven:maven-profile:2.0.11",
)


maven_jar(
    name = "org_apache_activemq_activemq_openwire_legacy",
    artifact = "org.apache.activemq:activemq-openwire-legacy:5.15.0",
)


maven_jar(
    name = "org_eclipse_jetty_apache_jsp",
    artifact = "org.eclipse.jetty:apache-jsp:9.3.17.v20170317",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_elasticloadbalancing",
    artifact = "com.amazonaws:aws-java-sdk-elasticloadbalancing:1.11.192",
)


maven_jar(
    name = "org_asynchttpclient_netty_resolver",
    artifact = "org.asynchttpclient:netty-resolver:2.0.35",
)


maven_jar(
    name = "org_scalaz_scalaz_core_2_11",
    artifact = "org.scalaz:scalaz-core_2.11:7.2.7",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_pinpoint",
    artifact = "com.amazonaws:aws-java-sdk-pinpoint:1.11.192",
)


maven_jar(
    name = "io_grpc_grpc_protobuf",
    artifact = "io.grpc:grpc-protobuf:1.0.1",
)


maven_jar(
    name = "com_ning_async_http_client",
    artifact = "com.ning:async-http-client:1.9.40",
)


maven_jar(
    name = "com_google_api_grpc_grpc_google_cloud_vision_v1",
    artifact = "com.google.api.grpc:grpc-google-cloud-vision-v1:0.1.3",
)


maven_jar(
    name = "commons_httpclient_commons_httpclient",
    artifact = "commons-httpclient:commons-httpclient:3.1",
)


maven_jar(
    name = "org_xerial_snappy_snappy_java",
    artifact = "org.xerial.snappy:snappy-java:1.0.5",
)


maven_jar(
    name = "com_github_stephenc_jamm",
    artifact = "com.github.stephenc:jamm:0.2.5",
)


maven_jar(
    name = "com_google_apis_google_api_services_storage",
    artifact = "com.google.apis:google-api-services-storage:v1-rev85-1.22.0",
)


maven_jar(
    name = "net_java_dev_jna_jna_platform",
    artifact = "net.java.dev.jna:jna-platform:4.4.0",
)


maven_jar(
    name = "org_apache_maven_maven_error_diagnostics",
    artifact = "org.apache.maven:maven-error-diagnostics:2.0.11",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_elastictranscoder",
    artifact = "com.amazonaws:aws-java-sdk-elastictranscoder:1.11.192",
)


maven_jar(
    name = "com_fasterxml_jackson_module_jackson_module_paranamer",
    artifact = "com.fasterxml.jackson.module:jackson-module-paranamer:2.8.8",
)


maven_jar(
    name = "org_eclipse_jetty_jetty_http",
    artifact = "org.eclipse.jetty:jetty-http:9.3.17.v20170317",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_marketplaceentitlement",
    artifact = "com.amazonaws:aws-java-sdk-marketplaceentitlement:1.11.192",
)


maven_jar(
    name = "org_hsqldb_hsqldb",
    artifact = "org.hsqldb:hsqldb:2.2.4",
)


maven_jar(
    name = "org_codehaus_plexus_plexus_interactivity_api",
    artifact = "org.codehaus.plexus:plexus-interactivity-api:1.0-alpha-4",
)


maven_jar(
    name = "io_springfox_springfox_core",
    artifact = "io.springfox:springfox-core:2.7.0",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_autoscaling",
    artifact = "com.amazonaws:aws-java-sdk-autoscaling:1.11.192",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_cloudtrail",
    artifact = "com.amazonaws:aws-java-sdk-cloudtrail:1.11.192",
)


maven_jar(
    name = "org_mapstruct_mapstruct",
    artifact = "org.mapstruct:mapstruct:1.1.0.Final",
)


maven_jar(
    name = "org_reactivestreams_reactive_streams",
    artifact = "org.reactivestreams:reactive-streams:1.0.1",
)


maven_jar(
    name = "io_spray_spray_routing_2_11",
    artifact = "io.spray:spray-routing_2.11:1.3.4",
)


maven_jar(
    name = "com_typesafe_akka_akka_testkit_2_11",
    artifact = "com.typesafe.akka:akka-testkit_2.11:2.5.4",
)


maven_jar(
    name = "com_google_guava_guava",
    artifact = "com.google.guava:guava:19.0",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_mobile",
    artifact = "com.amazonaws:aws-java-sdk-mobile:1.11.192",
)


maven_jar(
    name = "org_apache_maven_maven_plugin_registry",
    artifact = "org.apache.maven:maven-plugin-registry:2.0.11",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_kinesis",
    artifact = "com.amazonaws:aws-java-sdk-kinesis:1.11.192",
)


maven_jar(
    name = "io_netty_netty_transport",
    artifact = "io.netty:netty-transport:4.0.27.Final",
)


maven_jar(
    name = "com_natpryce_make_it_easy",
    artifact = "com.natpryce:make-it-easy:3.1.6",
)


maven_jar(
    name = "classworlds_classworlds",
    artifact = "classworlds:classworlds:1.1",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_api_gateway",
    artifact = "com.amazonaws:aws-java-sdk-api-gateway:1.11.192",
)


maven_jar(
    name = "com_propensive_rapture_base_2_11",
    artifact = "com.propensive:rapture-base_2.11:2.0.0-M9",
)


maven_jar(
    name = "com_typesafe_netty_netty_reactive_streams",
    artifact = "com.typesafe.netty:netty-reactive-streams:1.0.8",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_kms",
    artifact = "com.amazonaws:aws-java-sdk-kms:1.11.192",
)


maven_jar(
    name = "com_propensive_rapture_core_2_11",
    artifact = "com.propensive:rapture-core_2.11:2.0.0-M9",
)


maven_jar(
    name = "org_apache_thrift_libthrift",
    artifact = "org.apache.thrift:libthrift:0.9.1",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_sqs",
    artifact = "com.amazonaws:aws-java-sdk-sqs:1.11.192",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_shield",
    artifact = "com.amazonaws:aws-java-sdk-shield:1.11.192",
)


maven_jar(
    name = "org_apache_bval_bval_jsr303",
    artifact = "org.apache.bval:bval-jsr303:0.3-incubating",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_logs",
    artifact = "com.amazonaws:aws-java-sdk-logs:1.11.192",
)


maven_jar(
    name = "org_apache_maven_maven_core",
    artifact = "org.apache.maven:maven-core:2.0.11",
)


maven_jar(
    name = "org_springframework_spring_beans",
    artifact = "org.springframework:spring-beans:4.3.10.RELEASE",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_cognitosync",
    artifact = "com.amazonaws:aws-java-sdk-cognitosync:1.11.192",
)


maven_jar(
    name = "jtidy_jtidy",
    artifact = "jtidy:jtidy:4aug2000r7-dev",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_sts",
    artifact = "com.amazonaws:aws-java-sdk-sts:1.11.192",
)


maven_jar(
    name = "org_asynchttpclient_netty_codec_dns",
    artifact = "org.asynchttpclient:netty-codec-dns:2.0.35",
)


maven_jar(
    name = "org_json4s_json4s_ext_2_11",
    artifact = "org.json4s:json4s-ext_2.11:3.5.3",
)


maven_jar(
    name = "org_springframework_data_spring_data_commons",
    artifact = "org.springframework.data:spring-data-commons:1.11.4.RELEASE",
)


maven_jar(
    name = "org_slf4j_jcl_over_slf4j",
    artifact = "org.slf4j:jcl-over-slf4j:1.7.25",
)


maven_jar(
    name = "net_databinder_dispatch_dispatch_json4s_jackson_2_11",
    artifact = "net.databinder.dispatch:dispatch-json4s-jackson_2.11:0.12.0",
)


maven_jar(
    name = "com_github_nscala_time_nscala_time_2_11",
    artifact = "com.github.nscala-time:nscala-time_2.11:2.16.0",
)


maven_jar(
    name = "org_apache_lucene_lucene_sandbox",
    artifact = "org.apache.lucene:lucene-sandbox:4.8.1",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_support",
    artifact = "com.amazonaws:aws-java-sdk-support:1.11.192",
)


maven_jar(
    name = "de_flapdoodle_embed_de_flapdoodle_embed_mongo",
    artifact = "de.flapdoodle.embed:de.flapdoodle.embed.mongo:2.0.0",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_dax",
    artifact = "com.amazonaws:aws-java-sdk-dax:1.11.192",
)


maven_jar(
    name = "org_mortbay_jasper_apache_jsp",
    artifact = "org.mortbay.jasper:apache-jsp:8.0.33",
)


maven_jar(
    name = "io_netty_netty",
    artifact = "io.netty:netty:3.10.5.Final",
)


maven_jar(
    name = "com_google_api_client_google_api_client",
    artifact = "com.google.api-client:google-api-client:1.22.0",
)


maven_jar(
    name = "org_eclipse_jetty_jetty_continuation",
    artifact = "org.eclipse.jetty:jetty-continuation:9.3.17.v20170317",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_elasticsearch",
    artifact = "com.amazonaws:aws-java-sdk-elasticsearch:1.11.192",
)


maven_jar(
    name = "io_spray_spray_http_2_11",
    artifact = "io.spray:spray-http_2.11:1.3.4",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_cognitoidentity",
    artifact = "com.amazonaws:aws-java-sdk-cognitoidentity:1.11.192",
)


maven_jar(
    name = "org_reflections_reflections",
    artifact = "org.reflections:reflections:0.9.9-RC1",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_marketplacemeteringservice",
    artifact = "com.amazonaws:aws-java-sdk-marketplacemeteringservice:1.11.192",
)


maven_jar(
    name = "org_eclipse_jetty_jetty_security",
    artifact = "org.eclipse.jetty:jetty-security:9.3.17.v20170317",
)


maven_jar(
    name = "org_apache_commons_commons_compress",
    artifact = "org.apache.commons:commons-compress:1.14",
)


maven_jar(
    name = "org_apache_httpcomponents_httpcore",
    artifact = "org.apache.httpcomponents:httpcore:4.4.4",
)


maven_jar(
    name = "net_lingala_zip4j_zip4j",
    artifact = "net.lingala.zip4j:zip4j:1.3.2",
)


maven_jar(
    name = "ch_qos_logback_logback_classic",
    artifact = "ch.qos.logback:logback-classic:1.0.13",
)


maven_jar(
    name = "org_apache_lucene_lucene_spatial",
    artifact = "org.apache.lucene:lucene-spatial:4.8.1",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_cloudhsmv2",
    artifact = "com.amazonaws:aws-java-sdk-cloudhsmv2:1.11.192",
)


maven_jar(
    name = "com_typesafe_akka_akka_persistence_2_11",
    artifact = "com.typesafe.akka:akka-persistence_2.11:2.5.4",
)


maven_jar(
    name = "com_typesafe_akka_akka_cluster_tools_2_11",
    artifact = "com.typesafe.akka:akka-cluster-tools_2.11:2.5.4",
)


maven_jar(
    name = "com_fasterxml_jackson_module_jackson_module_scala_2_11",
    artifact = "com.fasterxml.jackson.module:jackson-module-scala_2.11:2.8.8",
)


maven_jar(
    name = "org_jboss_logging_jboss_logging",
    artifact = "org.jboss.logging:jboss-logging:3.1.0.CR2",
)


maven_jar(
    name = "com_google_cloud_google_cloud_translate",
    artifact = "com.google.cloud:google-cloud-translate:0.8.0",
)


maven_jar(
    name = "com_jayway_jsonpath_json_path",
    artifact = "com.jayway.jsonpath:json-path:0.8.1",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_servermigration",
    artifact = "com.amazonaws:aws-java-sdk-servermigration:1.11.192",
)


maven_jar(
    name = "org_apache_geronimo_specs_geronimo_j2ee_management_1_1_spec",
    artifact = "org.apache.geronimo.specs:geronimo-j2ee-management_1.1_spec:1.0.1",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_health",
    artifact = "com.amazonaws:aws-java-sdk-health:1.11.192",
)


maven_jar(
    name = "com_github_jnr_jnr_netdb",
    artifact = "com.github.jnr:jnr-netdb:1.1.5",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_lightsail",
    artifact = "com.amazonaws:aws-java-sdk-lightsail:1.11.192",
)


maven_jar(
    name = "org_apache_curator_curator_recipes",
    artifact = "org.apache.curator:curator-recipes:2.12.0",
)


maven_jar(
    name = "javax_servlet_javax_servlet_api",
    artifact = "javax.servlet:javax.servlet-api:3.1.0",
)


maven_jar(
    name = "org_hibernate_hibernate",
    artifact = "org.hibernate:hibernate:3.0.5",
)


maven_jar(
    name = "org_specs2_classycle",
    artifact = "org.specs2:classycle:1.4.3",
)


maven_jar(
    name = "org_reactivemongo_reactivemongo_bson_macros_2_11",
    artifact = "org.reactivemongo:reactivemongo-bson-macros_2.11:0.10.5.0.akka23",
)


maven_jar(
    name = "org_apache_geronimo_specs_geronimo_jms_1_1_spec",
    artifact = "org.apache.geronimo.specs:geronimo-jms_1.1_spec:1.1.1",
)


maven_jar(
    name = "com_jcraft_jzlib",
    artifact = "com.jcraft:jzlib:1.0.7",
)


maven_jar(
    name = "org_typelevel_macro_compat_2_11",
    artifact = "org.typelevel:macro-compat_2.11:1.1.1",
)


maven_jar(
    name = "org_apache_lucene_lucene_core",
    artifact = "org.apache.lucene:lucene-core:4.8.1",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_servicecatalog",
    artifact = "com.amazonaws:aws-java-sdk-servicecatalog:1.11.192",
)


maven_jar(
    name = "com_headius_options",
    artifact = "com.headius:options:1.4",
)


maven_jar(
    name = "org_eclipse_jetty_jetty_jndi",
    artifact = "org.eclipse.jetty:jetty-jndi:9.3.17.v20170317",
)


maven_jar(
    name = "org_eclipse_jetty_jetty_client",
    artifact = "org.eclipse.jetty:jetty-client:9.3.17.v20170317",
)


maven_jar(
    name = "com_google_cloud_google_cloud",
    artifact = "com.google.cloud:google-cloud:0.8.0",
)


maven_jar(
    name = "org_eclipse_jetty_jetty_xml",
    artifact = "org.eclipse.jetty:jetty-xml:9.3.17.v20170317",
)


maven_jar(
    name = "org_apache_commons_commons_lang3",
    artifact = "org.apache.commons:commons-lang3:3.6",
)


maven_jar(
    name = "net_bytebuddy_byte_buddy",
    artifact = "net.bytebuddy:byte-buddy:1.6.14",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_rekognition",
    artifact = "com.amazonaws:aws-java-sdk-rekognition:1.11.192",
)


maven_jar(
    name = "org_apache_maven_maven_plugin_parameter_documenter",
    artifact = "org.apache.maven:maven-plugin-parameter-documenter:2.0.11",
)


maven_jar(
    name = "io_spray_spray_httpx_2_11",
    artifact = "io.spray:spray-httpx_2.11:1.3.4",
)


maven_jar(
    name = "org_springframework_spring_web",
    artifact = "org.springframework:spring-web:4.3.10.RELEASE",
)


maven_jar(
    name = "com_google_inject_guice",
    artifact = "com.google.inject:guice:4.0",
)


maven_jar(
    name = "org_mockito_mockito_core",
    artifact = "org.mockito:mockito-core:1.10.19",
)


maven_jar(
    name = "org_codehaus_plexus_plexus_container_default",
    artifact = "org.codehaus.plexus:plexus-container-default:1.6",
)


maven_jar(
    name = "org_yaml_snakeyaml",
    artifact = "org.yaml:snakeyaml:1.17",
)


maven_jar(
    name = "org_slf4j_slf4j_jdk14",
    artifact = "org.slf4j:slf4j-jdk14:1.7.25",
)


maven_jar(
    name = "org_eclipse_jetty_http2_http2_client",
    artifact = "org.eclipse.jetty.http2:http2-client:9.3.17.v20170317",
)


maven_jar(
    name = "com_fasterxml_woodstox_woodstox_core",
    artifact = "com.fasterxml.woodstox:woodstox-core:5.0.3",
)


maven_jar(
    name = "commons_codec_commons_codec",
    artifact = "commons-codec:commons-codec:1.10",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_opsworkscm",
    artifact = "com.amazonaws:aws-java-sdk-opsworkscm:1.11.192",
)


maven_jar(
    name = "com_newrelic_agent_java_newrelic_agent",
    artifact = "com.newrelic.agent.java:newrelic-agent:3.42.0",
)


maven_jar(
    name = "com_jcraft_jsch",
    artifact = "com.jcraft:jsch:0.1.27",
)


maven_jar(
    name = "org_apache_logging_log4j_log4j_api",
    artifact = "org.apache.logging.log4j:log4j-api:2.0.2",
)


maven_jar(
    name = "org_apache_maven_maven_settings",
    artifact = "org.apache.maven:maven-settings:2.0.11",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_events",
    artifact = "com.amazonaws:aws-java-sdk-events:1.11.192",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_polly",
    artifact = "com.amazonaws:aws-java-sdk-polly:1.11.192",
)


maven_jar(
    name = "org_scalikejdbc_scalikejdbc_core_2_11",
    artifact = "org.scalikejdbc:scalikejdbc-core_2.11:2.5.2",
)


maven_jar(
    name = "org_scala_stm_scala_stm_2_11",
    artifact = "org.scala-stm:scala-stm_2.11:0.7",
)


maven_jar(
    name = "org_jmock_jmock",
    artifact = "org.jmock:jmock:2.8.3",
)


maven_jar(
    name = "org_springframework_plugin_spring_plugin_metadata",
    artifact = "org.springframework.plugin:spring-plugin-metadata:1.2.0.RELEASE",
)


maven_jar(
    name = "org_springframework_spring_test",
    artifact = "org.springframework:spring-test:4.3.10.RELEASE",
)


maven_jar(
    name = "org_scala_lang_modules_scala_xml_2_11",
    artifact = "org.scala-lang.modules:scala-xml_2.11:1.0.6",
)


maven_jar(
    name = "org_scalikejdbc_scalikejdbc_2_11",
    artifact = "org.scalikejdbc:scalikejdbc_2.11:2.5.2",
)


maven_jar(
    name = "com_google_cloud_google_cloud_storage",
    artifact = "com.google.cloud:google-cloud-storage:0.8.0-beta",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_models",
    artifact = "com.amazonaws:aws-java-sdk-models:1.11.192",
)


maven_jar(
    name = "com_chuusai_shapeless_2_11",
    artifact = "com.chuusai:shapeless_2.11:1.2.4",
)


maven_jar(
    name = "io_spray_spray_can_2_11",
    artifact = "io.spray:spray-can_2.11:1.3.4",
)


maven_jar(
    name = "com_google_api_grpc_grpc_google_cloud_pubsub_v1",
    artifact = "com.google.api.grpc:grpc-google-cloud-pubsub-v1:0.1.3",
)


maven_jar(
    name = "dom4j_dom4j",
    artifact = "dom4j:dom4j:1.6",
)


maven_jar(
    name = "org_apache_activemq_activemq_pool",
    artifact = "org.apache.activemq:activemq-pool:5.15.0",
)


maven_jar(
    name = "org_apache_velocity_velocity_tools",
    artifact = "org.apache.velocity:velocity-tools:2.0",
)


maven_jar(
    name = "commons_configuration_commons_configuration",
    artifact = "commons-configuration:commons-configuration:1.10",
)


maven_jar(
    name = "org_scalaz_scalaz_concurrent_2_11",
    artifact = "org.scalaz:scalaz-concurrent_2.11:7.2.7",
)


maven_jar(
    name = "org_apache_maven_wagon_wagon_http_shared",
    artifact = "org.apache.maven.wagon:wagon-http-shared:1.0-beta-2",
)


maven_jar(
    name = "com_google_code_gson_gson",
    artifact = "com.google.code.gson:gson:2.8.1",
)


maven_jar(
    name = "com_typesafe_akka_akka_remote_2_11",
    artifact = "com.typesafe.akka:akka-remote_2.11:2.5.4",
)


maven_jar(
    name = "javax_servlet_servlet_api",
    artifact = "javax.servlet:servlet-api:2.5",
)


maven_jar(
    name = "software_amazon_ion_ion_java",
    artifact = "software.amazon.ion:ion-java:1.0.2",
)


maven_jar(
    name = "com_101tec_zkclient",
    artifact = "com.101tec:zkclient:0.10",
)


maven_jar(
    name = "org_apache_maven_maven_model",
    artifact = "org.apache.maven:maven-model:3.5.0",
)


maven_jar(
    name = "org_apache_zookeeper_zookeeper",
    artifact = "org.apache.zookeeper:zookeeper:3.4.10",
)


maven_jar(
    name = "org_apache_maven_maven_artifact",
    artifact = "org.apache.maven:maven-artifact:2.0.11",
)


maven_jar(
    name = "org_apache_activemq_activemq_client",
    artifact = "org.apache.activemq:activemq-client:5.15.0",
)


maven_jar(
    name = "org_scalikejdbc_scalikejdbc_interpolation_macro_2_11",
    artifact = "org.scalikejdbc:scalikejdbc-interpolation-macro_2.11:2.5.2",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_migrationhub",
    artifact = "com.amazonaws:aws-java-sdk-migrationhub:1.11.192",
)


maven_jar(
    name = "com_typesafe_play_build_link",
    artifact = "com.typesafe.play:build-link:2.6.3",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_cloudfront",
    artifact = "com.amazonaws:aws-java-sdk-cloudfront:1.11.192",
)


maven_jar(
    name = "org_antlr_stringtemplate",
    artifact = "org.antlr:stringtemplate:3.2",
)


maven_jar(
    name = "de_flapdoodle_embed_de_flapdoodle_embed_process",
    artifact = "de.flapdoodle.embed:de.flapdoodle.embed.process:2.0.1",
)


maven_jar(
    name = "org_apache_lucene_lucene_analyzers_common",
    artifact = "org.apache.lucene:lucene-analyzers-common:4.8.1",
)


maven_jar(
    name = "org_specs2_specs2_common_2_11",
    artifact = "org.specs2:specs2-common_2.11:3.8.6",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_datapipeline",
    artifact = "com.amazonaws:aws-java-sdk-datapipeline:1.11.192",
)


maven_jar(
    name = "org_joda_joda_convert",
    artifact = "org.joda:joda-convert:1.8.3",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_mechanicalturkrequester",
    artifact = "com.amazonaws:aws-java-sdk-mechanicalturkrequester:1.11.192",
)


maven_jar(
    name = "org_apache_lucene_lucene_codecs",
    artifact = "org.apache.lucene:lucene-codecs:4.8.1",
)


maven_jar(
    name = "org_jruby_dirgra",
    artifact = "org.jruby:dirgra:0.3",
)


maven_jar(
    name = "org_apache_activemq_activemq_broker",
    artifact = "org.apache.activemq:activemq-broker:5.15.0",
)


maven_jar(
    name = "com_google_api_client_google_api_client_servlet",
    artifact = "com.google.api-client:google-api-client-servlet:1.21.0",
)


maven_jar(
    name = "org_eclipse_jetty_jetty_annotations",
    artifact = "org.eclipse.jetty:jetty-annotations:9.3.17.v20170317",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_discovery",
    artifact = "com.amazonaws:aws-java-sdk-discovery:1.11.192",
)


maven_jar(
    name = "org_asynchttpclient_async_http_client_netty_utils",
    artifact = "org.asynchttpclient:async-http-client-netty-utils:2.0.35",
)


maven_jar(
    name = "io_netty_netty_common",
    artifact = "io.netty:netty-common:4.0.51.Final",
)


maven_jar(
    name = "org_fusesource_hawtbuf_hawtbuf",
    artifact = "org.fusesource.hawtbuf:hawtbuf:1.11",
)


maven_jar(
    name = "org_codehaus_woodstox_woodstox_core_asl",
    artifact = "org.codehaus.woodstox:woodstox-core-asl:4.4.1",
)


maven_jar(
    name = "javax_transaction_jta",
    artifact = "javax.transaction:jta:1.1",
)


maven_jar(
    name = "de_zeigermann_xml_xml_im_exporter",
    artifact = "de.zeigermann.xml:xml-im-exporter:1.1",
)


maven_jar(
    name = "org_apache_commons_commons_text",
    artifact = "org.apache.commons:commons-text:1.1",
)


maven_jar(
    name = "org_jruby_extras_bytelist",
    artifact = "org.jruby.extras:bytelist:1.0.13",
)


maven_jar(
    name = "org_agrona_agrona",
    artifact = "org.agrona:agrona:0.9.5",
)


maven_jar(
    name = "org_apache_maven_maven_project",
    artifact = "org.apache.maven:maven-project:2.0.11",
)


maven_jar(
    name = "com_google_cloud_google_cloud_trace",
    artifact = "com.google.cloud:google-cloud-trace:0.8.0",
)


maven_jar(
    name = "org_json4s_json4s_mongo_2_11",
    artifact = "org.json4s:json4s-mongo_2.11:3.5.3",
)


maven_jar(
    name = "org_apache_maven_wagon_wagon_provider_api",
    artifact = "org.apache.maven.wagon:wagon-provider-api:1.0-beta-2",
)


maven_jar(
    name = "com_google_http_client_google_http_client",
    artifact = "com.google.http-client:google-http-client:1.23.0",
)


maven_jar(
    name = "org_hamcrest_hamcrest_library",
    artifact = "org.hamcrest:hamcrest-library:1.3",
)


maven_jar(
    name = "org_jvnet_mimepull_mimepull",
    artifact = "org.jvnet.mimepull:mimepull:1.9.5",
)


maven_jar(
    name = "com_fasterxml_jackson_module_jackson_module_jsonSchema",
    artifact = "com.fasterxml.jackson.module:jackson-module-jsonSchema:2.8.8",
)


maven_jar(
    name = "org_apache_kafka_kafka_2_11",
    artifact = "org.apache.kafka:kafka_2.11:0.10.2.1",
)


maven_jar(
    name = "net_jpountz_lz4_lz4",
    artifact = "net.jpountz.lz4:lz4:1.2.0",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_stepfunctions",
    artifact = "com.amazonaws:aws-java-sdk-stepfunctions:1.11.192",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_cloudhsm",
    artifact = "com.amazonaws:aws-java-sdk-cloudhsm:1.11.192",
)


maven_jar(
    name = "io_aeron_aeron_client",
    artifact = "io.aeron:aeron-client:1.2.5",
)


maven_jar(
    name = "com_carbonfive_db_support_db_migration",
    artifact = "com.carbonfive.db-support:db-migration:0.9.9-m5",
)


maven_jar(
    name = "org_specs2_specs2_scalacheck_2_11",
    artifact = "org.specs2:specs2-scalacheck_2.11:3.8.6",
)


maven_jar(
    name = "net_logstash_logback_logstash_logback_encoder",
    artifact = "net.logstash.logback:logstash-logback-encoder:3.6",
)


maven_jar(
    name = "jdom_jdom",
    artifact = "jdom:jdom:1.0",
)


maven_jar(
    name = "io_netty_netty_buffer",
    artifact = "io.netty:netty-buffer:4.0.27.Final",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_s3",
    artifact = "com.amazonaws:aws-java-sdk-s3:1.11.192",
)


maven_jar(
    name = "qdox_qdox",
    artifact = "qdox:qdox:1.6.1",
)


maven_jar(
    name = "org_apache_lucene_lucene_suggest",
    artifact = "org.apache.lucene:lucene-suggest:4.8.1",
)


maven_jar(
    name = "org_apache_velocity_velocity",
    artifact = "org.apache.velocity:velocity:1.7",
)


maven_jar(
    name = "org_springframework_data_spring_data_mongodb",
    artifact = "org.springframework.data:spring-data-mongodb:1.8.4.RELEASE",
)


maven_jar(
    name = "org_scalamacros_resetallattrs_2_11",
    artifact = "org.scalamacros:resetallattrs_2.11:1.0.0",
)


maven_jar(
    name = "org_parboiled_parboiled_core",
    artifact = "org.parboiled:parboiled-core:1.1.7",
)


maven_jar(
    name = "commons_io_commons_io",
    artifact = "commons-io:commons-io:2.5",
)


maven_jar(
    name = "org_apache_lucene_lucene_queries",
    artifact = "org.apache.lucene:lucene-queries:4.8.1",
)


maven_jar(
    name = "com_twitter_util_function_2_11",
    artifact = "com.twitter:util-function_2.11:7.0.0",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_elasticloadbalancingv2",
    artifact = "com.amazonaws:aws-java-sdk-elasticloadbalancingv2:1.11.192",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_codecommit",
    artifact = "com.amazonaws:aws-java-sdk-codecommit:1.11.192",
)


maven_jar(
    name = "org_specs2_specs2_junit_2_11",
    artifact = "org.specs2:specs2-junit_2.11:3.8.6",
)


maven_jar(
    name = "org_springframework_spring_aop",
    artifact = "org.springframework:spring-aop:4.3.10.RELEASE",
)


maven_jar(
    name = "org_springframework_spring_context",
    artifact = "org.springframework:spring-context:4.3.10.RELEASE",
)


maven_jar(
    name = "com_thinkaurelius_thrift_thrift_server",
    artifact = "com.thinkaurelius.thrift:thrift-server:0.3.7",
)


maven_jar(
    name = "org_specs2_specs2_core_2_11",
    artifact = "org.specs2:specs2-core_2.11:3.8.6",
)


maven_jar(
    name = "org_apache_bval_bval_core",
    artifact = "org.apache.bval:bval-core:0.3-incubating",
)


maven_jar(
    name = "net_databinder_dispatch_dispatch_core_2_11",
    artifact = "net.databinder.dispatch:dispatch-core_2.11:0.12.0",
)


maven_jar(
    name = "org_bouncycastle_bcprov_jdk15on",
    artifact = "org.bouncycastle:bcprov-jdk15on:1.58",
)


maven_jar(
    name = "cglib_cglib_nodep",
    artifact = "cglib:cglib-nodep:3.2.5",
)


maven_jar(
    name = "org_asynchttpclient_async_http_client",
    artifact = "org.asynchttpclient:async-http-client:2.0.35",
)


maven_jar(
    name = "org_apache_maven_wagon_wagon_file",
    artifact = "org.apache.maven.wagon:wagon-file:1.0-beta-2",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_ecr",
    artifact = "com.amazonaws:aws-java-sdk-ecr:1.11.192",
)


maven_jar(
    name = "org_codehaus_plexus_plexus_component_annotations",
    artifact = "org.codehaus.plexus:plexus-component-annotations:1.7.1",
)


maven_jar(
    name = "org_specs2_specs2_mock_2_11",
    artifact = "org.specs2:specs2-mock_2.11:3.8.6",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_applicationautoscaling",
    artifact = "com.amazonaws:aws-java-sdk-applicationautoscaling:1.11.192",
)


maven_jar(
    name = "org_scala_lang_scala_reflect",
    artifact = "org.scala-lang:scala-reflect:2.11.11",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_cloudformation",
    artifact = "com.amazonaws:aws-java-sdk-cloudformation:1.11.192",
)


maven_jar(
    name = "org_eclipse_jetty_toolchain_jetty_schemas",
    artifact = "org.eclipse.jetty.toolchain:jetty-schemas:3.1",
)


maven_jar(
    name = "org_apache_taglibs_taglibs_standard_spec",
    artifact = "org.apache.taglibs:taglibs-standard-spec:1.2.5",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_ec2",
    artifact = "com.amazonaws:aws-java-sdk-ec2:1.11.192",
)


maven_jar(
    name = "com_google_code_findbugs_jsr305",
    artifact = "com.google.code.findbugs:jsr305:3.0.1",
)


maven_jar(
    name = "com_typesafe_slick_slick_2_11",
    artifact = "com.typesafe.slick:slick_2.11:2.1.0",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_machinelearning",
    artifact = "com.amazonaws:aws-java-sdk-machinelearning:1.11.192",
)


maven_jar(
    name = "com_fasterxml_jackson_datatype_jackson_datatype_joda",
    artifact = "com.fasterxml.jackson.datatype:jackson-datatype-joda:2.8.8",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_glacier",
    artifact = "com.amazonaws:aws-java-sdk-glacier:1.11.192",
)


maven_jar(
    name = "com_typesafe_akka_akka_protobuf_2_11",
    artifact = "com.typesafe.akka:akka-protobuf_2.11:2.5.4",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_batch",
    artifact = "com.amazonaws:aws-java-sdk-batch:1.11.192",
)


maven_jar(
    name = "com_github_tomakehurst_wiremock",
    artifact = "com.github.tomakehurst:wiremock:1.57",
)


maven_jar(
    name = "com_google_cloud_google_cloud_core",
    artifact = "com.google.cloud:google-cloud-core:0.8.0",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_elasticbeanstalk",
    artifact = "com.amazonaws:aws-java-sdk-elasticbeanstalk:1.11.192",
)


maven_jar(
    name = "org_eclipse_jetty_jetty_webapp",
    artifact = "org.eclipse.jetty:jetty-webapp:9.3.17.v20170317",
)


maven_jar(
    name = "org_apache_curator_curator_test",
    artifact = "org.apache.curator:curator-test:2.12.0",
)


maven_jar(
    name = "org_mongodb_casbah_gridfs_2_11",
    artifact = "org.mongodb:casbah-gridfs_2.11:3.1.1",
)


maven_jar(
    name = "org_apache_httpcomponents_httpmime",
    artifact = "org.apache.httpcomponents:httpmime:4.5.2",
)


maven_jar(
    name = "com_google_oauth_client_google_oauth_client_appengine",
    artifact = "com.google.oauth-client:google-oauth-client-appengine:1.21.0",
)


maven_jar(
    name = "org_apache_lucene_lucene_join",
    artifact = "org.apache.lucene:lucene-join:4.8.1",
)


maven_jar(
    name = "com_google_cloud_google_cloud_logging",
    artifact = "com.google.cloud:google-cloud-logging:0.8.0-beta",
)


maven_jar(
    name = "com_google_oauth_client_google_oauth_client_servlet",
    artifact = "com.google.oauth-client:google-oauth-client-servlet:1.21.0",
)


maven_jar(
    name = "com_fasterxml_jackson_dataformat_jackson_dataformat_yaml",
    artifact = "com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:2.8.8",
)


maven_jar(
    name = "junit_junit",
    artifact = "junit:junit:4.12",
)


maven_jar(
    name = "org_jsoup_jsoup",
    artifact = "org.jsoup:jsoup:1.10.3",
)


maven_jar(
    name = "com_google_apis_google_api_services_bigquery",
    artifact = "com.google.apis:google-api-services-bigquery:v2-rev330-1.22.0",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_cloudwatch",
    artifact = "com.amazonaws:aws-java-sdk-cloudwatch:1.11.192",
)


maven_jar(
    name = "org_parboiled_parboiled_scala_2_11",
    artifact = "org.parboiled:parboiled-scala_2.11:1.1.7",
)


maven_jar(
    name = "org_jruby_jcodings_jcodings",
    artifact = "org.jruby.jcodings:jcodings:1.0.17",
)


maven_jar(
    name = "org_codehaus_woodstox_stax2_api",
    artifact = "org.codehaus.woodstox:stax2-api:3.1.4",
)


maven_jar(
    name = "com_typesafe_play_play_iteratees_2_11",
    artifact = "com.typesafe.play:play-iteratees_2.11:2.3.5",
)


maven_jar(
    name = "org_apache_lucene_lucene_grouping",
    artifact = "org.apache.lucene:lucene-grouping:4.8.1",
)


maven_jar(
    name = "eu_bitwalker_UserAgentUtils",
    artifact = "eu.bitwalker:UserAgentUtils:1.19",
)


maven_jar(
    name = "org_slf4j_slf4j_api",
    artifact = "org.slf4j:slf4j-api:1.7.25",
)


maven_jar(
    name = "com_restfb_restfb",
    artifact = "com.restfb:restfb:1.46.0",
)


maven_jar(
    name = "org_apache_maven_wagon_wagon_ssh_common",
    artifact = "org.apache.maven.wagon:wagon-ssh-common:1.0-beta-2",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_greengrass",
    artifact = "com.amazonaws:aws-java-sdk-greengrass:1.11.192",
)


maven_jar(
    name = "org_springframework_spring_webmvc",
    artifact = "org.springframework:spring-webmvc:4.3.10.RELEASE",
)


maven_jar(
    name = "com_google_http_client_google_http_client_jackson",
    artifact = "com.google.http-client:google-http-client-jackson:1.21.0",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_cloudwatchmetrics",
    artifact = "com.amazonaws:aws-java-sdk-cloudwatchmetrics:1.11.192",
)


maven_jar(
    name = "com_spatial4j_spatial4j",
    artifact = "com.spatial4j:spatial4j:0.4.1",
)


maven_jar(
    name = "org_antlr_antlr_runtime",
    artifact = "org.antlr:antlr-runtime:3.2",
)


maven_jar(
    name = "com_google_apis_google_api_services_cloudresourcemanager",
    artifact = "com.google.apis:google-api-services-cloudresourcemanager:v1beta1-rev10-1.21.0",
)


maven_jar(
    name = "com_google_cloud_google_cloud_bigquery",
    artifact = "com.google.cloud:google-cloud-bigquery:0.8.0-beta",
)


maven_jar(
    name = "com_google_appengine_appengine_jsr107cache",
    artifact = "com.google.appengine:appengine-jsr107cache:1.9.57",
)


maven_jar(
    name = "com_google_appengine_appengine_api_1_0_sdk",
    artifact = "com.google.appengine:appengine-api-1.0-sdk:1.9.57",
)


maven_jar(
    name = "com_fasterxml_jackson_datatype_jackson_datatype_guava",
    artifact = "com.fasterxml.jackson.datatype:jackson-datatype-guava:2.8.8",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_redshift",
    artifact = "com.amazonaws:aws-java-sdk-redshift:1.11.192",
)


maven_jar(
    name = "javax_validation_validation_api",
    artifact = "javax.validation:validation-api:1.0.0.GA",
)


maven_jar(
    name = "io_spray_spray_io_2_11",
    artifact = "io.spray:spray-io_2.11:1.3.4",
)


maven_jar(
    name = "org_eclipse_jetty_jetty_util",
    artifact = "org.eclipse.jetty:jetty-util:9.3.17.v20170317",
)


maven_jar(
    name = "com_typesafe_config",
    artifact = "com.typesafe:config:1.3.1",
)


maven_jar(
    name = "org_apache_maven_maven_model_builder",
    artifact = "org.apache.maven:maven-model-builder:3.5.0",
)


maven_jar(
    name = "org_apache_maven_maven_monitor",
    artifact = "org.apache.maven:maven-monitor:2.0.11",
)


maven_jar(
    name = "io_grpc_grpc_netty",
    artifact = "io.grpc:grpc-netty:1.0.1",
)


maven_jar(
    name = "org_scalacheck_scalacheck_2_11",
    artifact = "org.scalacheck:scalacheck_2.11:1.13.5",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_elasticache",
    artifact = "com.amazonaws:aws-java-sdk-elasticache:1.11.192",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_costandusagereport",
    artifact = "com.amazonaws:aws-java-sdk-costandusagereport:1.11.192",
)


maven_jar(
    name = "net_sf_ezmorph_ezmorph",
    artifact = "net.sf.ezmorph:ezmorph:1.0.6",
)


maven_jar(
    name = "com_newrelic_agent_java_newrelic_api",
    artifact = "com.newrelic.agent.java:newrelic-api:3.42.0",
)


maven_jar(
    name = "org_slf4j_slf4j_log4j12",
    artifact = "org.slf4j:slf4j-log4j12:1.7.21",
)


maven_jar(
    name = "com_googlecode_owasp_java_html_sanitizer_owasp_java_html_sanitizer",
    artifact = "com.googlecode.owasp-java-html-sanitizer:owasp-java-html-sanitizer:20150501.1",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_route53",
    artifact = "com.amazonaws:aws-java-sdk-route53:1.11.192",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_glue",
    artifact = "com.amazonaws:aws-java-sdk-glue:1.11.192",
)


maven_jar(
    name = "net_java_dev_jna_jna",
    artifact = "net.java.dev.jna:jna:4.4.0",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_codestar",
    artifact = "com.amazonaws:aws-java-sdk-codestar:1.11.192",
)


maven_jar(
    name = "com_google_http_client_google_http_client_protobuf",
    artifact = "com.google.http-client:google-http-client-protobuf:1.20.0",
)


maven_jar(
    name = "org_apache_maven_doxia_doxia_sink_api",
    artifact = "org.apache.maven.doxia:doxia-sink-api:1.0",
)


maven_jar(
    name = "javax_jdo_jdo2_api",
    artifact = "javax.jdo:jdo2-api:2.3-eb",
)


maven_jar(
    name = "com_google_api_grpc_grpc_google_cloud_monitoring_v3",
    artifact = "com.google.api.grpc:grpc-google-cloud-monitoring-v3:0.1.3",
)


maven_jar(
    name = "org_eclipse_jetty_http2_http2_server",
    artifact = "org.eclipse.jetty.http2:http2-server:9.3.17.v20170317",
)


maven_jar(
    name = "com_google_cloud_google_cloud_monitoring",
    artifact = "com.google.cloud:google-cloud-monitoring:0.8.0",
)


maven_jar(
    name = "org_springframework_spring_context_support",
    artifact = "org.springframework:spring-context-support:4.3.10.RELEASE",
)


maven_jar(
    name = "org_jruby_jruby",
    artifact = "org.jruby:jruby:9.1.2.0",
)


maven_jar(
    name = "org_hibernate_hibernate_validator",
    artifact = "org.hibernate:hibernate-validator:4.3.0.Final",
)


maven_jar(
    name = "com_addthis_metrics_reporter_config",
    artifact = "com.addthis.metrics:reporter-config:2.1.0",
)


maven_jar(
    name = "org_apache_maven_enforcer_enforcer_api",
    artifact = "org.apache.maven.enforcer:enforcer-api:1.4.1",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_codepipeline",
    artifact = "com.amazonaws:aws-java-sdk-codepipeline:1.11.192",
)


maven_jar(
    name = "io_grpc_grpc_auth",
    artifact = "io.grpc:grpc-auth:1.0.1",
)


maven_jar(
    name = "com_fasterxml_jackson_dataformat_jackson_dataformat_cbor",
    artifact = "com.fasterxml.jackson.dataformat:jackson-dataformat-cbor:2.8.8",
)


maven_jar(
    name = "org_jruby_joni_joni",
    artifact = "org.jruby.joni:joni:2.1.10",
)


maven_jar(
    name = "jline_jline",
    artifact = "jline:jline:0.9.94",
)


maven_jar(
    name = "io_swagger_swagger_models",
    artifact = "io.swagger:swagger-models:1.5.13",
)


maven_jar(
    name = "javax_activation_activation",
    artifact = "javax.activation:activation:1.1",
)


maven_jar(
    name = "io_grpc_grpc_context",
    artifact = "io.grpc:grpc-context:1.0.1",
)


maven_jar(
    name = "io_spray_spray_client_2_11",
    artifact = "io.spray:spray-client_2.11:1.3.4",
)


maven_jar(
    name = "com_amazonaws_aws_java_sdk_marketplacecommerceanalytics",
    artifact = "com.amazonaws:aws-java-sdk-marketplacecommerceanalytics:1.11.192",
)


maven_jar(
    name = "com_google_cloud_google_cloud_pubsub",
    artifact = "com.google.cloud:google-cloud-pubsub:0.8.0",
)
