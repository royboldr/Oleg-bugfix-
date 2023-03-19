# Oleg-bugfix-
description = 'RSocket IPC Protobuf Support'

dependencies {
    api project (':rsocket-ipc-core')
    
    implementation 'com.google.protobuf:protobuf-java'
    implementation 'org.slf4j:slf4j-api'

    testImplementation 'io.opentracing.brave:brave-opentracing'
    testImplementation 'junit:junit'
    testImplementation 'org.junit.jupiter:junit-jupiter-engine'
    testImplementation 'org.junit.vintage:junit-vintage-engine'

    testImplementation 'javax.inject:javax.inject'
    testImplementation 'io.projectreactor:reactor-test'
    testImplementation 'com.google.protobuf:protobuf-java'
    testImplementation 'org.hdrhistogram:HdrHistogram'
    testImplementation 'org.apache.logging.log4j:log4j-api'
    testImplementation 'org.apache.logging.log4j:log4j-core'
    testImplementation 'org.apache.logging.log4j:log4j-slf4j-impl'
    testImplementation 'io.rsocket:rsocket-transport-netty'
    testImplementation 'io.rsocket:rsocket-transport-local'
    testImplementation 'org.mockito:mockito-core'
    testImplementation 'io.zipkin.reporter2:zipkin-sender-okhttp3'
