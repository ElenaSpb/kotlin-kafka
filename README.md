# kotlin-kafka

C:\Java\jdk-11.0.2\bin\java.exe -XX:TieredStopAtLevel=1 -noverify -Dspring.output.ansi.enabled=always -Dcom.sun.management.jmxremote -Dspring.jmx.enabled=true -Dspring.liveBeansView.mbeanDomain -Dspring.application.admin.enabled=true "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA 2020.1.4\lib\idea_rt.jar=63796:C:\Program Files\JetBrains\IntelliJ IDEA 2020.1.4\bin" -Dfile.encoding=UTF-8 -classpath D:\kotlin-kafka\build\classes\kotlin\main;D:\kotlin-kafka\build\resources\main;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.springframework.boot\spring-boot-starter-webflux\2.4.0\566ff0b0b4faf1bad1a1113c22a2a5163474c7d3\spring-boot-starter-webflux-2.4.0.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\com.fasterxml.jackson.module\jackson-module-kotlin\2.11.3\ad8d29545c5ab0cdd6d49ee38f7ece8d9f772815\jackson-module-kotlin-2.11.3.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\io.projectreactor.kotlin\reactor-kotlin-extensions\1.1.0\d7490007744eb445e3db9111704bda7d8abd1f8d\reactor-kotlin-extensions-1.1.0.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.springframework.cloud\spring-cloud-stream-binder-kafka-streams\3.1.0-M4\73147e146b364775e4093a09abe1897996b49fc0\spring-cloud-stream-binder-kafka-streams-3.1.0-M4.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.apache.kafka\kafka-streams\2.6.0\44625179b6cdb3003df8eb390087d70460ee9e4e\kafka-streams-2.6.0.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-reflect\1.4.10\e2b3c6695eee6085e606d96d685396dce23a3a06\kotlin-reflect-1.4.10.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlinx\kotlinx-coroutines-reactor\1.4.1\6134f8658e441fdd859fadd638f85adc555cc86b\kotlinx-coroutines-reactor-1.4.1.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib-jdk8\1.4.10\998caa30623f73223194a8b657abd2baec4880ea\kotlin-stdlib-jdk8-1.4.10.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.springframework.cloud\spring-cloud-stream-binder-kafka\3.1.0-M4\51b8280c5876556b601347d0d027c0ef74fe29ba\spring-cloud-stream-binder-kafka-3.1.0-M4.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.springframework.cloud\spring-cloud-stream\3.1.0-M4\9cee00fb63837be27e02fd9ada4a4928d2b1f10a\spring-cloud-stream-3.1.0-M4.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.springframework.kafka\spring-kafka\2.6.3\11225d36665bd660d48f68fc58a725fed972863e\spring-kafka-2.6.3.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\com.github.javafaker\javafaker\1.0.2\be0ff271b1208416822db4438864df47f90af92f\javafaker-1.0.2.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.springframework.boot\spring-boot-starter-json\2.4.0\e688a97ab229ae5a4a0c3ccb3f4419c9457a25b6\spring-boot-starter-json-2.4.0.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.springframework.boot\spring-boot-starter\2.4.0\26162567b7644e6d245b9d8dcf6fd4efb2bf74f4\spring-boot-starter-2.4.0.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.springframework.boot\spring-boot-starter-reactor-netty\2.4.0\8810fb38f581a08865165d5b0a842303449bbeb3\spring-boot-starter-reactor-netty-2.4.0.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.springframework\spring-webflux\5.3.1\49c0194e5398a3f0b667b46529f92f77c38ad120\spring-webflux-5.3.1.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.springframework\spring-web\5.3.1\4e1e1d1c6b5a00597162db84132414c409bcf615\spring-web-5.3.1.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\com.fasterxml.jackson.core\jackson-databind\2.11.3\4f7b27416934dc929bb6c2d2c5fe521829e6a4ec\jackson-databind-2.11.3.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\com.fasterxml.jackson.core\jackson-annotations\2.11.3\25d4e9c777e7a8805c4a000a8629d3009c779c9b\jackson-annotations-2.11.3.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\io.projectreactor\reactor-core\3.4.0\683c9c676c438e5945b0f12808575f22160c5e54\reactor-core-3.4.0.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.springframework.cloud\spring-cloud-stream-binder-kafka-core\3.1.0-M4\f35b75e77d01cbb35036f648ea4ef3c0d8fb06a2\spring-cloud-stream-binder-kafka-core-3.1.0-M4.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.apache.kafka\connect-json\2.6.0\1f2a8bd0023ed8d56214b0f466ed3faefa4bac48\connect-json-2.6.0.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.apache.kafka\kafka-clients\2.6.0\a07cd8835f6d81be2820b2ec0cd63a821debe107\kafka-clients-2.6.0.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.slf4j\slf4j-api\1.7.30\b5a4b6d16ab13e34a88fae84c35cd5d68cac922c\slf4j-api-1.7.30.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.rocksdb\rocksdbjni\5.18.4\def7af83920ad2c39eb452f6ef9603777d899ea0\rocksdbjni-5.18.4.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib\1.4.10\ea29e063d2bbe695be13e9d044dcfb0c7add398e\kotlin-stdlib-1.4.10.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlinx\kotlinx-coroutines-reactive\1.4.1\20b2855788efa0c1a7d4ae6e5b9b15f43bc707d5\kotlinx-coroutines-reactive-1.4.1.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib-jdk7\1.4.10\30e46450b0bb3dbf43898d2f461be4a942784780\kotlin-stdlib-jdk7-1.4.10.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.springframework.boot\spring-boot-starter-validation\2.4.0\739a3c3d0b08be3c8dfbed08c26b6a633148e186\spring-boot-starter-validation-2.4.0.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.springframework.cloud\spring-cloud-function-context\3.1.0-M5\57fa5876446c1d3607412884c971faa8aa9456a9\spring-cloud-function-context-3.1.0-M5.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.springframework.integration\spring-integration-jmx\5.4.1\9491474e0f7404a324aad2fd32d4324417a9e513\spring-integration-jmx-5.4.1.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.springframework.integration\spring-integration-core\5.4.1\6f088271bbee83cdc239a0ea13895ad503229573\spring-integration-core-5.4.1.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.springframework\spring-messaging\5.3.1\24fcc3b962e3a4aff34f789ff307a0a10a09f49e\spring-messaging-5.3.1.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.springframework.retry\spring-retry\1.3.0\4ce2be0457023ff7afabd6a6024e6a84c7adcf9b\spring-retry-1.3.0.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.springframework\spring-context\5.3.1\736836c8098981ddabd309a0c15f967594da62bc\spring-context-5.3.1.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.springframework\spring-tx\5.3.1\191e436f0b526fbe8f3cebdfd7dc048a3e1106fc\spring-tx-5.3.1.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.apache.commons\commons-lang3\3.11\68e9a6adf7cf8eb7e9d31bbc554c7c75eeaac568\commons-lang3-3.11.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.yaml\snakeyaml\1.27\359d62567480b07a679dc643f82fc926b100eed5\snakeyaml-1.27.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.yaml\snakeyaml\1.27\1be1636a555afa20f10647ced5f44ce58053af0c\snakeyaml-1.27-android.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\com.github.mifmif\generex\1.0.2\b378f873b4e8d7616c3d920e2132cb1c87679600\generex-1.0.2.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\com.fasterxml.jackson.datatype\jackson-datatype-jdk8\2.11.3\dcdfce3e4af9da18d69b1be6f3d7c91256105831\jackson-datatype-jdk8-2.11.3.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\com.fasterxml.jackson.datatype\jackson-datatype-jsr310\2.11.3\dd53d93fd448b345eeb75bec336d9c91dc56b796\jackson-datatype-jsr310-2.11.3.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\com.fasterxml.jackson.module\jackson-module-parameter-names\2.11.3\ab66d5c5b8008161ae89be8a3d98efff9ef1b915\jackson-module-parameter-names-2.11.3.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.springframework.boot\spring-boot-starter-logging\2.4.0\4f1ba27a364170a26bbd448b14ba3907d21f2154\spring-boot-starter-logging-2.4.0.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.springframework.boot\spring-boot-autoconfigure\2.4.0\e1f7cd3b65e4706fbe3160c76f5815d4dbc79915\spring-boot-autoconfigure-2.4.0.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.springframework.boot\spring-boot\2.4.0\d8c0caa04526c8cc1dfcbb9c5badae3c99c49884\spring-boot-2.4.0.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\jakarta.annotation\jakarta.annotation-api\1.3.5\59eb84ee0d616332ff44aba065f3888cf002cd2d\jakarta.annotation-api-1.3.5.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.springframework\spring-core\5.3.1\47af5b161749cd249fc074b4f140e011a3337efd\spring-core-5.3.1.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\io.projectreactor.netty\reactor-netty-http\1.0.1\1842c244c1d34d17a2b5a96e116af3448753189e\reactor-netty-http-1.0.1.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.springframework\spring-beans\5.3.1\a4bb5ffad5564e4a0e25955e3a40b1c6158385b2\spring-beans-5.3.1.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\com.fasterxml.jackson.core\jackson-core\2.11.3\c2351800432bdbdd8284c3f5a7f0782a352aa84a\jackson-core-2.11.3.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.reactivestreams\reactive-streams\1.0.3\d9fb7a7926ffa635b3dcaa5049fb2bfa25b3e7d0\reactive-streams-1.0.3.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.springframework.integration\spring-integration-kafka\5.4.1\142f193ef0760c856fa45749d5785f36f89be09d\spring-integration-kafka-5.4.1.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.apache.kafka\connect-api\2.6.0\eb42b9b0df587c6d4a007db903403e20ec56c23a\connect-api-2.6.0.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\com.github.luben\zstd-jni\1.4.4-7\f7e9d149c0182968cc2a8706d3ffe82f5c9f01eb\zstd-jni-1.4.4-7.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.lz4\lz4-java\1.7.1\c4d931ef8ad2c9c35d65b231a33e61428472d0da\lz4-java-1.7.1.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.xerial.snappy\snappy-java\1.1.7.3\241bb74a1eb37d68a4e324a4bc3865427de0a62d\snappy-java-1.1.7.3.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib-common\1.4.10\6229be3465805c99db1142ad75e6c6ddeac0b04c\kotlin-stdlib-common-1.4.10.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.jetbrains\annotations\13.0\919f0dfe192fb4e063e7dacadee7f8bb9a2672a9\annotations-13.0.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlinx\kotlinx-coroutines-core-jvm\1.4.1\936067d1e0195f638396f60e71da745bb14a35ca\kotlinx-coroutines-core-jvm-1.4.1.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.glassfish\jakarta.el\3.0.3\dab46ee1ee23f7197c13d7c40fce14817c9017df\jakarta.el-3.0.3.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.hibernate.validator\hibernate-validator\6.1.6.Final\2fee0c38f3a8fae0aeb0f1f042b87270bd6b0cb3\hibernate-validator-6.1.6.Final.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.springframework.cloud\spring-cloud-function-core\3.1.0-M5\a523524fb6286b1bb4074d5b6e4c2ed8ebffe24d\spring-cloud-function-core-3.1.0-M5.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\net.jodah\typetools\0.6.2\d1e38fe8e668f228b0761d80a6c80c151ab6044a\typetools-0.6.2.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.springframework\spring-aop\5.3.1\25c310880484082ffba3130deb8e10c5afb29f10\spring-aop-5.3.1.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.springframework\spring-expression\5.3.1\aee660842a21fbf49f6e5921aa07974f1650c498\spring-expression-5.3.1.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\dk.brics.automaton\automaton\1.11-8\6ebfa65eb431ff4b715a23be7a750cbc4cc96d0f\automaton-1.11-8.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\ch.qos.logback\logback-classic\1.2.3\7c4f3c474fb2c041d8028740440937705ebb473a\logback-classic-1.2.3.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.apache.logging.log4j\log4j-to-slf4j\2.13.3\966f6fd1af4959d6b12bfa880121d4a2b164f857\log4j-to-slf4j-2.13.3.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.slf4j\jul-to-slf4j\1.7.30\d58bebff8cbf70ff52b59208586095f467656c30\jul-to-slf4j-1.7.30.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.springframework\spring-jcl\5.3.1\1158888aa7517f8997eb43afe47776d9d2de8a38\spring-jcl-5.3.1.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\io.projectreactor.netty\reactor-netty-core\1.0.1\d3b6861cd9cd8b1e3387f14d80eb9c6724fd052b\reactor-netty-core-1.0.1.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\io.netty\netty-codec-http2\4.1.54.Final\327a4ae62b0a41cdf02f610f06eb353f10c17ef8\netty-codec-http2-4.1.54.Final.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\io.netty\netty-codec-http\4.1.54.Final\70eb9509289d1cee549cf12bae71929d1a4a12c7\netty-codec-http-4.1.54.Final.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\io.netty\netty-resolver-dns\4.1.54.Final\7d7a3cf2a9ed327c713cf593c7ba4bf9d9bfb072\netty-resolver-dns-4.1.54.Final.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\io.netty\netty-transport-native-epoll\4.1.54.Final\e351768ffd4f5210698bbd534511fc8fc89c6b\netty-transport-native-epoll-4.1.54.Final-linux-x86_64.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\jakarta.validation\jakarta.validation-api\2.0.2\5eacc6522521f7eacb081f95cee1e231648461e7\jakarta.validation-api-2.0.2.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.jboss.logging\jboss-logging\3.4.1.Final\40fd4d696c55793e996d1ff3c475833f836c2498\jboss-logging-3.4.1.Final.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\com.fasterxml\classmate\1.5.1\3fe0bed568c62df5e89f4f174c101eab25345b6c\classmate-1.5.1.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\ch.qos.logback\logback-core\1.2.3\864344400c3d4d92dfeb0a305dc87d953677c03c\logback-core-1.2.3.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\org.apache.logging.log4j\log4j-api\2.13.3\ec1508160b93d274b1add34419b897bae84c6ca9\log4j-api-2.13.3.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\io.netty\netty-handler-proxy\4.1.54.Final\8fa9d18b09a8a79bf64e8bc1bd775cbd77277199\netty-handler-proxy-4.1.54.Final.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\io.netty\netty-handler\4.1.54.Final\e83dfe8ebe3622d2cd5cce8532a9ca49cad51e9\netty-handler-4.1.54.Final.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\io.netty\netty-codec\4.1.54.Final\295680345b12a86c21fa7af5d9a77e0e0fcff46a\netty-codec-4.1.54.Final.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\io.netty\netty-transport\4.1.54.Final\ddb9a255819b87b8812932d1d1001f4d9dc7f89e\netty-transport-4.1.54.Final.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\io.netty\netty-buffer\4.1.54.Final\15c513ef8a2e56e88d3736752ea10eae758f47d8\netty-buffer-4.1.54.Final.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\io.netty\netty-common\4.1.54.Final\8c330383cda87204ab38e7401ab0f56c0d43b799\netty-common-4.1.54.Final.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\io.netty\netty-codec-dns\4.1.54.Final\886c9875a8360f5b3495960ec8be9af3632431f9\netty-codec-dns-4.1.54.Final.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\io.netty\netty-resolver\4.1.54.Final\7eed781e7531b990f8360e1a5010b53ca73878f5\netty-resolver-4.1.54.Final.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\io.netty\netty-transport-native-unix-common\4.1.54.Final\ac7d48202cf62c8d51abe89f228d338a41cb49cd\netty-transport-native-unix-common-4.1.54.Final.jar;C:\Users\Elena_Moshnikova\.gradle\caches\modules-2\files-2.1\io.netty\netty-codec-socks\4.1.54.Final\8f8239e989e80cd470eaea90ee5746dbf24f5b8e\netty-codec-socks-4.1.54.Final.jar com.example.kotlinkafka.KotlinKafkaApplicationKt

  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/
 :: Spring Boot ::                (v2.4.0)

2020-12-11 13:24:23.651  INFO 4640 --- [           main] c.e.k.KotlinKafkaApplicationKt           : Starting KotlinKafkaApplicationKt using Java 11.0.2 on EPRUPETW02EE with PID 4640 (D:\kotlin-kafka\build\classes\kotlin\main started by Elena_Moshnikova in D:\kotlin-kafka)
2020-12-11 13:24:23.655  INFO 4640 --- [           main] c.e.k.KotlinKafkaApplicationKt           : No active profile set, falling back to default profiles: default
2020-12-11 13:24:25.159  INFO 4640 --- [           main] o.s.c.a.ConfigurationClassEnhancer       : @Bean method FunctionConfiguration.po is non-static and returns an object assignable to Spring's BeanFactoryPostProcessor interface. This will result in a failure to process annotations such as @Autowired, @Resource and @PostConstruct within the method's declaring @Configuration class. Add the 'static' modifier to this method to avoid these container lifecycle issues; see @Bean javadoc for complete details.
2020-12-11 13:24:25.179  INFO 4640 --- [           main] faultConfiguringBeanFactoryPostProcessor : No bean named 'errorChannel' has been explicitly defined. Therefore, a default PublishSubscribeChannel will be created.
2020-12-11 13:24:25.189  INFO 4640 --- [           main] faultConfiguringBeanFactoryPostProcessor : No bean named 'taskScheduler' has been explicitly defined. Therefore, a default ThreadPoolTaskScheduler will be created.
2020-12-11 13:24:25.194  INFO 4640 --- [           main] faultConfiguringBeanFactoryPostProcessor : No bean named 'integrationHeaderChannelRegistry' has been explicitly defined. Therefore, a default DefaultHeaderChannelRegistry will be created.
2020-12-11 13:24:25.280  INFO 4640 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'org.springframework.integration.config.IntegrationManagementConfiguration' of type [org.springframework.integration.config.IntegrationManagementConfiguration] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-12-11 13:24:25.294  INFO 4640 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'org.springframework.boot.autoconfigure.integration.IntegrationAutoConfiguration$IntegrationJmxConfiguration' of type [org.springframework.boot.autoconfigure.integration.IntegrationAutoConfiguration$IntegrationJmxConfiguration] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-12-11 13:24:25.306  INFO 4640 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'org.springframework.boot.autoconfigure.jmx.JmxAutoConfiguration' of type [org.springframework.boot.autoconfigure.jmx.JmxAutoConfiguration] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-12-11 13:24:25.312  INFO 4640 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'mbeanServer' of type [com.sun.jmx.mbeanserver.JmxMBeanServer] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-12-11 13:24:25.335  INFO 4640 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'integrationChannelResolver' of type [org.springframework.integration.support.channel.BeanFactoryChannelResolver] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-12-11 13:24:25.337  INFO 4640 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'integrationDisposableAutoCreatedBeans' of type [org.springframework.integration.config.annotation.Disposables] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-12-11 13:24:26.409  INFO 4640 --- [           main] o.s.s.c.ThreadPoolTaskScheduler          : Initializing ExecutorService 'taskScheduler'
false
false
2020-12-11 13:24:26.498  INFO 4640 --- [           main] o.s.c.s.m.DirectWithAttributesChannel    : Channel 'application.consumeChuckNorris-in-0' has 1 subscriber(s).
2020-12-11 13:24:26.842  INFO 4640 --- [           main] o.s.i.monitor.IntegrationMBeanExporter   : Registering MessageChannel errorChannel
2020-12-11 13:24:26.919  INFO 4640 --- [           main] o.s.i.monitor.IntegrationMBeanExporter   : Registering MessageChannel consumeChuckNorris-in-0
2020-12-11 13:24:26.955  INFO 4640 --- [           main] o.s.i.monitor.IntegrationMBeanExporter   : Registering MessageChannel produceChuckNorris_integrationflow.channel#0
2020-12-11 13:24:26.959  INFO 4640 --- [           main] o.s.i.monitor.IntegrationMBeanExporter   : Registering MessageChannel produceChuckNorris-out-0
2020-12-11 13:24:26.965  INFO 4640 --- [           main] o.s.i.monitor.IntegrationMBeanExporter   : Registering MessageChannel nullChannel
2020-12-11 13:24:26.979  INFO 4640 --- [           main] o.s.i.monitor.IntegrationMBeanExporter   : Registering MessageHandler produceChuckNorris_integrationflow.org.springframework.integration.config.ConsumerEndpointFactoryBean#0
2020-12-11 13:24:27.067  INFO 4640 --- [           main] o.s.i.monitor.IntegrationMBeanExporter   : Registering MessageHandler _org.springframework.integration.errorLogger
2020-12-11 13:24:27.084  INFO 4640 --- [           main] o.s.i.monitor.IntegrationMBeanExporter   : Registering MessageSource produceChuckNorris_integrationflow.org.springframework.integration.config.SourcePollingChannelAdapterFactoryBean#0
2020-12-11 13:24:27.112  INFO 4640 --- [           main] o.s.i.monitor.IntegrationMBeanExporter   : Registering Endpoint org.springframework.integration:type=ManagedEndpoint,name="produceChuckNorris_integrationflow.org.springframework.integration.config.SourcePollingChannelAdapterFactoryBean#0.adapter",bean=endpoint
2020-12-11 13:24:27.157  INFO 4640 --- [           main] o.s.i.endpoint.EventDrivenConsumer       : Adding {logging-channel-adapter:_org.springframework.integration.errorLogger} as a subscriber to the 'errorChannel' channel
2020-12-11 13:24:27.157  INFO 4640 --- [           main] o.s.i.channel.PublishSubscribeChannel    : Channel 'application.errorChannel' has 1 subscriber(s).
2020-12-11 13:24:27.157  INFO 4640 --- [           main] o.s.i.endpoint.EventDrivenConsumer       : started bean '_org.springframework.integration.errorLogger'
2020-12-11 13:24:27.157  INFO 4640 --- [           main] o.s.i.endpoint.EventDrivenConsumer       : Adding {router} as a subscriber to the 'produceChuckNorris_integrationflow.channel#0' channel
2020-12-11 13:24:27.157  INFO 4640 --- [           main] o.s.integration.channel.DirectChannel    : Channel 'application.produceChuckNorris_integrationflow.channel#0' has 1 subscriber(s).
2020-12-11 13:24:27.158  INFO 4640 --- [           main] o.s.i.endpoint.EventDrivenConsumer       : started bean 'produceChuckNorris_integrationflow.org.springframework.integration.config.ConsumerEndpointFactoryBean#0'
2020-12-11 13:24:27.159  INFO 4640 --- [           main] o.s.c.s.binder.DefaultBinderFactory      : Creating binder: ktable
2020-12-11 13:24:27.322  INFO 4640 --- [           main] o.s.c.s.binder.DefaultBinderFactory      : Caching the binder: ktable
2020-12-11 13:24:27.322  INFO 4640 --- [           main] o.s.c.s.binder.DefaultBinderFactory      : Retrieving cached binder: ktable
2020-12-11 13:24:27.323  INFO 4640 --- [           main] o.s.c.s.binder.DefaultBinderFactory      : Creating binder: kafka
2020-12-11 13:24:27.475  INFO 4640 --- [           main] o.s.c.s.binder.DefaultBinderFactory      : Caching the binder: kafka
2020-12-11 13:24:27.475  INFO 4640 --- [           main] o.s.c.s.binder.DefaultBinderFactory      : Retrieving cached binder: kafka
2020-12-11 13:24:27.475  INFO 4640 --- [           main] o.s.c.s.binder.DefaultBinderFactory      : Creating binder: kstream
2020-12-11 13:24:27.546  INFO 4640 --- [           main] o.s.c.s.binder.DefaultBinderFactory      : Caching the binder: kstream
2020-12-11 13:24:27.546  INFO 4640 --- [           main] o.s.c.s.binder.DefaultBinderFactory      : Retrieving cached binder: kstream
2020-12-11 13:24:27.546  INFO 4640 --- [           main] o.s.c.s.binder.DefaultBinderFactory      : Creating binder: globalktable
2020-12-11 13:24:27.638  INFO 4640 --- [           main] o.s.c.s.binder.DefaultBinderFactory      : Caching the binder: globalktable
2020-12-11 13:24:27.638  INFO 4640 --- [           main] o.s.c.s.binder.DefaultBinderFactory      : Retrieving cached binder: globalktable
2020-12-11 13:24:27.638  INFO 4640 --- [           main] o.s.c.s.binder.DefaultBinderFactory      : Retrieving cached binder: kafka
2020-12-11 13:24:27.734  INFO 4640 --- [           main] o.s.c.s.b.k.p.KafkaTopicProvisioner      : Using kafka topic for outbound: produceChuckNorris-out-0
2020-12-11 13:24:27.740  INFO 4640 --- [           main] o.a.k.clients.admin.AdminClientConfig    : AdminClientConfig values: 
	bootstrap.servers = [pkc-419q3.us-east4.gcp.confluent.cloud:9092]
	client.dns.lookup = use_all_dns_ips
	client.id = 
	connections.max.idle.ms = 300000
	default.api.timeout.ms = 60000
	metadata.max.age.ms = 300000
	metric.reporters = []
	metrics.num.samples = 2
	metrics.recording.level = INFO
	metrics.sample.window.ms = 30000
	receive.buffer.bytes = 65536
	reconnect.backoff.max.ms = 1000
	reconnect.backoff.ms = 50
	request.timeout.ms = 30000
	retries = 2147483647
	retry.backoff.ms = 100
	sasl.client.callback.handler.class = null
	sasl.jaas.config = null
	sasl.kerberos.kinit.cmd = /usr/bin/kinit
	sasl.kerberos.min.time.before.relogin = 60000
	sasl.kerberos.service.name = null
	sasl.kerberos.ticket.renew.jitter = 0.05
	sasl.kerberos.ticket.renew.window.factor = 0.8
	sasl.login.callback.handler.class = null
	sasl.login.class = null
	sasl.login.refresh.buffer.seconds = 300
	sasl.login.refresh.min.period.seconds = 60
	sasl.login.refresh.window.factor = 0.8
	sasl.login.refresh.window.jitter = 0.05
	sasl.mechanism = PLAIN
	security.protocol = SASL_SSL
	security.providers = null
	send.buffer.bytes = 131072
	ssl.cipher.suites = null
	ssl.enabled.protocols = [TLSv1.2, TLSv1.3]
	ssl.endpoint.identification.algorithm = https
	ssl.engine.factory.class = null
	ssl.key.password = null
	ssl.keymanager.algorithm = SunX509
	ssl.keystore.location = null
	ssl.keystore.password = null
	ssl.keystore.type = JKS
	ssl.protocol = TLSv1.3
	ssl.provider = null
	ssl.secure.random.implementation = null
	ssl.trustmanager.algorithm = PKIX
	ssl.truststore.location = null
	ssl.truststore.password = null
	ssl.truststore.type = JKS

2020-12-11 13:24:27.837 ERROR 4640 --- [           main] o.s.cloud.stream.binding.BindingService  : Failed to create producer binding; retrying in 30 seconds

org.springframework.cloud.stream.binder.BinderException: Exception thrown while building outbound endpoint
	at org.springframework.cloud.stream.binder.AbstractMessageChannelBinder.doBindProducer(AbstractMessageChannelBinder.java:241) ~[spring-cloud-stream-3.1.0-M4.jar:3.1.0-M4]
	at org.springframework.cloud.stream.binder.AbstractMessageChannelBinder.doBindProducer(AbstractMessageChannelBinder.java:91) ~[spring-cloud-stream-3.1.0-M4.jar:3.1.0-M4]
	at org.springframework.cloud.stream.binder.AbstractBinder.bindProducer(AbstractBinder.java:152) ~[spring-cloud-stream-3.1.0-M4.jar:3.1.0-M4]
	at org.springframework.cloud.stream.binding.BindingService.doBindProducer(BindingService.java:313) ~[spring-cloud-stream-3.1.0-M4.jar:3.1.0-M4]
	at org.springframework.cloud.stream.binding.BindingService.bindProducer(BindingService.java:282) ~[spring-cloud-stream-3.1.0-M4.jar:3.1.0-M4]
	at org.springframework.cloud.stream.binding.BindingService.bindProducer(BindingService.java:291) ~[spring-cloud-stream-3.1.0-M4.jar:3.1.0-M4]
	at org.springframework.cloud.stream.binding.AbstractBindableProxyFactory.createAndBindOutputs(AbstractBindableProxyFactory.java:136) ~[spring-cloud-stream-3.1.0-M4.jar:3.1.0-M4]
	at org.springframework.cloud.stream.binding.OutputBindingLifecycle.doStartWithBindable(OutputBindingLifecycle.java:58) ~[spring-cloud-stream-3.1.0-M4.jar:3.1.0-M4]
	at java.base/java.util.LinkedHashMap$LinkedValues.forEach(LinkedHashMap.java:608) ~[na:na]
	at org.springframework.cloud.stream.binding.AbstractBindingLifecycle.start(AbstractBindingLifecycle.java:57) ~[spring-cloud-stream-3.1.0-M4.jar:3.1.0-M4]
	at org.springframework.cloud.stream.binding.OutputBindingLifecycle.start(OutputBindingLifecycle.java:34) ~[spring-cloud-stream-3.1.0-M4.jar:3.1.0-M4]
	at org.springframework.context.support.DefaultLifecycleProcessor.doStart(DefaultLifecycleProcessor.java:178) ~[spring-context-5.3.1.jar:5.3.1]
	at org.springframework.context.support.DefaultLifecycleProcessor.access$200(DefaultLifecycleProcessor.java:54) ~[spring-context-5.3.1.jar:5.3.1]
	at org.springframework.context.support.DefaultLifecycleProcessor$LifecycleGroup.start(DefaultLifecycleProcessor.java:356) ~[spring-context-5.3.1.jar:5.3.1]
	at java.base/java.lang.Iterable.forEach(Iterable.java:75) ~[na:na]
	at org.springframework.context.support.DefaultLifecycleProcessor.startBeans(DefaultLifecycleProcessor.java:155) ~[spring-context-5.3.1.jar:5.3.1]
	at org.springframework.context.support.DefaultLifecycleProcessor.onRefresh(DefaultLifecycleProcessor.java:123) ~[spring-context-5.3.1.jar:5.3.1]
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:942) ~[spring-context-5.3.1.jar:5.3.1]
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:591) ~[spring-context-5.3.1.jar:5.3.1]
	at org.springframework.boot.web.reactive.context.ReactiveWebServerApplicationContext.refresh(ReactiveWebServerApplicationContext.java:63) ~[spring-boot-2.4.0.jar:2.4.0]
	at org.springframework.boot.SpringApplication.refresh(SpringApplication.java:767) ~[spring-boot-2.4.0.jar:2.4.0]
	at org.springframework.boot.SpringApplication.refresh(SpringApplication.java:759) ~[spring-boot-2.4.0.jar:2.4.0]
	at org.springframework.boot.SpringApplication.refreshContext(SpringApplication.java:426) ~[spring-boot-2.4.0.jar:2.4.0]
	at org.springframework.boot.SpringApplication.run(SpringApplication.java:326) ~[spring-boot-2.4.0.jar:2.4.0]
	at org.springframework.boot.SpringApplication.run(SpringApplication.java:1309) ~[spring-boot-2.4.0.jar:2.4.0]
	at org.springframework.boot.SpringApplication.run(SpringApplication.java:1298) ~[spring-boot-2.4.0.jar:2.4.0]
	at com.example.kotlinkafka.KotlinKafkaApplicationKt.main(KotlinKafkaApplication.kt:35) ~[main/:na]
Caused by: org.apache.kafka.common.KafkaException: Failed to create new KafkaAdminClient
	at org.apache.kafka.clients.admin.KafkaAdminClient.createInternal(KafkaAdminClient.java:499) ~[kafka-clients-2.6.0.jar:na]
	at org.apache.kafka.clients.admin.Admin.create(Admin.java:73) ~[kafka-clients-2.6.0.jar:na]
	at org.apache.kafka.clients.admin.AdminClient.create(AdminClient.java:49) ~[kafka-clients-2.6.0.jar:na]
	at org.springframework.cloud.stream.binder.kafka.provisioning.KafkaTopicProvisioner.provisionProducerDestination(KafkaTopicProvisioner.java:154) ~[spring-cloud-stream-binder-kafka-core-3.1.0-M4.jar:3.1.0-M4]
	at org.springframework.cloud.stream.binder.kafka.provisioning.KafkaTopicProvisioner.provisionProducerDestination(KafkaTopicProvisioner.java:86) ~[spring-cloud-stream-binder-kafka-core-3.1.0-M4.jar:3.1.0-M4]
	at org.springframework.cloud.stream.binder.AbstractMessageChannelBinder.doBindProducer(AbstractMessageChannelBinder.java:223) ~[spring-cloud-stream-3.1.0-M4.jar:3.1.0-M4]
	... 26 common frames omitted
Caused by: org.apache.kafka.common.KafkaException: javax.security.auth.login.LoginException: Could not login: the client is being asked for a password, but the Kafka client code does not currently support obtaining a password from the user. not available to garner  authentication information from the user
	at org.apache.kafka.common.network.SaslChannelBuilder.configure(SaslChannelBuilder.java:172) ~[kafka-clients-2.6.0.jar:na]
	at org.apache.kafka.common.network.ChannelBuilders.create(ChannelBuilders.java:157) ~[kafka-clients-2.6.0.jar:na]
	at org.apache.kafka.common.network.ChannelBuilders.clientChannelBuilder(ChannelBuilders.java:73) ~[kafka-clients-2.6.0.jar:na]
	at org.apache.kafka.clients.ClientUtils.createChannelBuilder(ClientUtils.java:105) ~[kafka-clients-2.6.0.jar:na]
	at org.apache.kafka.clients.admin.KafkaAdminClient.createInternal(KafkaAdminClient.java:474) ~[kafka-clients-2.6.0.jar:na]
	... 31 common frames omitted
Caused by: javax.security.auth.login.LoginException: Could not login: the client is being asked for a password, but the Kafka client code does not currently support obtaining a password from the user. not available to garner  authentication information from the user
	at jdk.security.auth/com.sun.security.auth.module.Krb5LoginModule.promptForPass(Krb5LoginModule.java:917) ~[jdk.security.auth:na]
	at jdk.security.auth/com.sun.security.auth.module.Krb5LoginModule.attemptAuthentication(Krb5LoginModule.java:737) ~[jdk.security.auth:na]
	at jdk.security.auth/com.sun.security.auth.module.Krb5LoginModule.login(Krb5LoginModule.java:592) ~[jdk.security.auth:na]
	at java.base/javax.security.auth.login.LoginContext.invoke(LoginContext.java:726) ~[na:na]
	at java.base/javax.security.auth.login.LoginContext$4.run(LoginContext.java:665) ~[na:na]
	at java.base/javax.security.auth.login.LoginContext$4.run(LoginContext.java:663) ~[na:na]
	at java.base/java.security.AccessController.doPrivileged(Native Method) ~[na:na]
	at java.base/javax.security.auth.login.LoginContext.invokePriv(LoginContext.java:663) ~[na:na]
	at java.base/javax.security.auth.login.LoginContext.login(LoginContext.java:574) ~[na:na]
	at org.apache.kafka.common.security.authenticator.AbstractLogin.login(AbstractLogin.java:60) ~[kafka-clients-2.6.0.jar:na]
	at org.apache.kafka.common.security.authenticator.LoginManager.<init>(LoginManager.java:62) ~[kafka-clients-2.6.0.jar:na]
	at org.apache.kafka.common.security.authenticator.LoginManager.acquireLoginManager(LoginManager.java:112) ~[kafka-clients-2.6.0.jar:na]
	at org.apache.kafka.common.network.SaslChannelBuilder.configure(SaslChannelBuilder.java:158) ~[kafka-clients-2.6.0.jar:na]
	... 35 common frames omitted

2020-12-11 13:24:27.844  INFO 4640 --- [           main] o.s.i.e.SourcePollingChannelAdapter      : started bean 'produceChuckNorris_integrationflow.org.springframework.integration.config.SourcePollingChannelAdapterFactoryBean#0'
2020-12-11 13:24:27.844  INFO 4640 --- [           main] o.s.c.s.binder.DefaultBinderFactory      : Retrieving cached binder: kafka
2020-12-11 13:24:27.889  INFO 4640 --- [           main] o.a.k.clients.admin.AdminClientConfig    : AdminClientConfig values: 
	bootstrap.servers = [pkc-419q3.us-east4.gcp.confluent.cloud:9092]
	client.dns.lookup = use_all_dns_ips
	client.id = 
	connections.max.idle.ms = 300000
	default.api.timeout.ms = 60000
	metadata.max.age.ms = 300000
	metric.reporters = []
	metrics.num.samples = 2
	metrics.recording.level = INFO
	metrics.sample.window.ms = 30000
	receive.buffer.bytes = 65536
	reconnect.backoff.max.ms = 1000
	reconnect.backoff.ms = 50
	request.timeout.ms = 30000
	retries = 2147483647
	retry.backoff.ms = 100
	sasl.client.callback.handler.class = null
	sasl.jaas.config = null
	sasl.kerberos.kinit.cmd = /usr/bin/kinit
	sasl.kerberos.min.time.before.relogin = 60000
	sasl.kerberos.service.name = null
	sasl.kerberos.ticket.renew.jitter = 0.05
	sasl.kerberos.ticket.renew.window.factor = 0.8
	sasl.login.callback.handler.class = null
	sasl.login.class = null
	sasl.login.refresh.buffer.seconds = 300
	sasl.login.refresh.min.period.seconds = 60
	sasl.login.refresh.window.factor = 0.8
	sasl.login.refresh.window.jitter = 0.05
	sasl.mechanism = PLAIN
	security.protocol = SASL_SSL
	security.providers = null
	send.buffer.bytes = 131072
	ssl.cipher.suites = null
	ssl.enabled.protocols = [TLSv1.2, TLSv1.3]
	ssl.endpoint.identification.algorithm = https
	ssl.engine.factory.class = null
	ssl.key.password = null
	ssl.keymanager.algorithm = SunX509
	ssl.keystore.location = null
	ssl.keystore.password = null
	ssl.keystore.type = JKS
	ssl.protocol = TLSv1.3
	ssl.provider = null
	ssl.secure.random.implementation = null
	ssl.trustmanager.algorithm = PKIX
	ssl.truststore.location = null
	ssl.truststore.password = null
	ssl.truststore.type = JKS

2020-12-11 13:24:27.893 ERROR 4640 --- [           main] o.s.cloud.stream.binding.BindingService  : Failed to create consumer binding; retrying in 30 seconds

org.springframework.cloud.stream.binder.BinderException: Exception thrown while starting consumer: 
	at org.springframework.cloud.stream.binder.AbstractMessageChannelBinder.doBindConsumer(AbstractMessageChannelBinder.java:462) ~[spring-cloud-stream-3.1.0-M4.jar:3.1.0-M4]
	at org.springframework.cloud.stream.binder.AbstractMessageChannelBinder.doBindConsumer(AbstractMessageChannelBinder.java:91) ~[spring-cloud-stream-3.1.0-M4.jar:3.1.0-M4]
	at org.springframework.cloud.stream.binder.AbstractBinder.bindConsumer(AbstractBinder.java:143) ~[spring-cloud-stream-3.1.0-M4.jar:3.1.0-M4]
	at org.springframework.cloud.stream.binding.BindingService.doBindConsumer(BindingService.java:176) ~[spring-cloud-stream-3.1.0-M4.jar:3.1.0-M4]
	at org.springframework.cloud.stream.binding.BindingService.bindConsumer(BindingService.java:133) ~[spring-cloud-stream-3.1.0-M4.jar:3.1.0-M4]
	at org.springframework.cloud.stream.binding.AbstractBindableProxyFactory.createAndBindInputs(AbstractBindableProxyFactory.java:112) ~[spring-cloud-stream-3.1.0-M4.jar:3.1.0-M4]
	at org.springframework.cloud.stream.binding.InputBindingLifecycle.doStartWithBindable(InputBindingLifecycle.java:58) ~[spring-cloud-stream-3.1.0-M4.jar:3.1.0-M4]
	at java.base/java.util.LinkedHashMap$LinkedValues.forEach(LinkedHashMap.java:608) ~[na:na]
	at org.springframework.cloud.stream.binding.AbstractBindingLifecycle.start(AbstractBindingLifecycle.java:57) ~[spring-cloud-stream-3.1.0-M4.jar:3.1.0-M4]
	at org.springframework.cloud.stream.binding.InputBindingLifecycle.start(InputBindingLifecycle.java:34) ~[spring-cloud-stream-3.1.0-M4.jar:3.1.0-M4]
	at org.springframework.context.support.DefaultLifecycleProcessor.doStart(DefaultLifecycleProcessor.java:178) ~[spring-context-5.3.1.jar:5.3.1]
	at org.springframework.context.support.DefaultLifecycleProcessor.access$200(DefaultLifecycleProcessor.java:54) ~[spring-context-5.3.1.jar:5.3.1]
	at org.springframework.context.support.DefaultLifecycleProcessor$LifecycleGroup.start(DefaultLifecycleProcessor.java:356) ~[spring-context-5.3.1.jar:5.3.1]
	at java.base/java.lang.Iterable.forEach(Iterable.java:75) ~[na:na]
	at org.springframework.context.support.DefaultLifecycleProcessor.startBeans(DefaultLifecycleProcessor.java:155) ~[spring-context-5.3.1.jar:5.3.1]
	at org.springframework.context.support.DefaultLifecycleProcessor.onRefresh(DefaultLifecycleProcessor.java:123) ~[spring-context-5.3.1.jar:5.3.1]
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:942) ~[spring-context-5.3.1.jar:5.3.1]
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:591) ~[spring-context-5.3.1.jar:5.3.1]
	at org.springframework.boot.web.reactive.context.ReactiveWebServerApplicationContext.refresh(ReactiveWebServerApplicationContext.java:63) ~[spring-boot-2.4.0.jar:2.4.0]
	at org.springframework.boot.SpringApplication.refresh(SpringApplication.java:767) ~[spring-boot-2.4.0.jar:2.4.0]
	at org.springframework.boot.SpringApplication.refresh(SpringApplication.java:759) ~[spring-boot-2.4.0.jar:2.4.0]
	at org.springframework.boot.SpringApplication.refreshContext(SpringApplication.java:426) ~[spring-boot-2.4.0.jar:2.4.0]
	at org.springframework.boot.SpringApplication.run(SpringApplication.java:326) ~[spring-boot-2.4.0.jar:2.4.0]
	at org.springframework.boot.SpringApplication.run(SpringApplication.java:1309) ~[spring-boot-2.4.0.jar:2.4.0]
	at org.springframework.boot.SpringApplication.run(SpringApplication.java:1298) ~[spring-boot-2.4.0.jar:2.4.0]
	at com.example.kotlinkafka.KotlinKafkaApplicationKt.main(KotlinKafkaApplication.kt:35) ~[main/:na]
Caused by: org.apache.kafka.common.KafkaException: Failed to create new KafkaAdminClient
	at org.apache.kafka.clients.admin.KafkaAdminClient.createInternal(KafkaAdminClient.java:499) ~[kafka-clients-2.6.0.jar:na]
	at org.apache.kafka.clients.admin.Admin.create(Admin.java:73) ~[kafka-clients-2.6.0.jar:na]
	at org.apache.kafka.clients.admin.AdminClient.create(AdminClient.java:49) ~[kafka-clients-2.6.0.jar:na]
	at org.springframework.cloud.stream.binder.kafka.provisioning.KafkaTopicProvisioner.createAdminClient(KafkaTopicProvisioner.java:253) ~[spring-cloud-stream-binder-kafka-core-3.1.0-M4.jar:3.1.0-M4]
	at org.springframework.cloud.stream.binder.kafka.provisioning.KafkaTopicProvisioner.doProvisionConsumerDestination(KafkaTopicProvisioner.java:223) ~[spring-cloud-stream-binder-kafka-core-3.1.0-M4.jar:3.1.0-M4]
	at org.springframework.cloud.stream.binder.kafka.provisioning.KafkaTopicProvisioner.provisionConsumerDestination(KafkaTopicProvisioner.java:190) ~[spring-cloud-stream-binder-kafka-core-3.1.0-M4.jar:3.1.0-M4]
	at org.springframework.cloud.stream.binder.kafka.provisioning.KafkaTopicProvisioner.provisionConsumerDestination(KafkaTopicProvisioner.java:86) ~[spring-cloud-stream-binder-kafka-core-3.1.0-M4.jar:3.1.0-M4]
	at org.springframework.cloud.stream.binder.AbstractMessageChannelBinder.doBindConsumer(AbstractMessageChannelBinder.java:403) ~[spring-cloud-stream-3.1.0-M4.jar:3.1.0-M4]
	... 25 common frames omitted
Caused by: org.apache.kafka.common.KafkaException: javax.security.auth.login.LoginException: Could not login: the client is being asked for a password, but the Kafka client code does not currently support obtaining a password from the user. not available to garner  authentication information from the user
	at org.apache.kafka.common.network.SaslChannelBuilder.configure(SaslChannelBuilder.java:172) ~[kafka-clients-2.6.0.jar:na]
	at org.apache.kafka.common.network.ChannelBuilders.create(ChannelBuilders.java:157) ~[kafka-clients-2.6.0.jar:na]
	at org.apache.kafka.common.network.ChannelBuilders.clientChannelBuilder(ChannelBuilders.java:73) ~[kafka-clients-2.6.0.jar:na]
	at org.apache.kafka.clients.ClientUtils.createChannelBuilder(ClientUtils.java:105) ~[kafka-clients-2.6.0.jar:na]
	at org.apache.kafka.clients.admin.KafkaAdminClient.createInternal(KafkaAdminClient.java:474) ~[kafka-clients-2.6.0.jar:na]
	... 32 common frames omitted
Caused by: javax.security.auth.login.LoginException: Could not login: the client is being asked for a password, but the Kafka client code does not currently support obtaining a password from the user. not available to garner  authentication information from the user
	at jdk.security.auth/com.sun.security.auth.module.Krb5LoginModule.promptForPass(Krb5LoginModule.java:917) ~[jdk.security.auth:na]
	at jdk.security.auth/com.sun.security.auth.module.Krb5LoginModule.attemptAuthentication(Krb5LoginModule.java:737) ~[jdk.security.auth:na]
	at jdk.security.auth/com.sun.security.auth.module.Krb5LoginModule.login(Krb5LoginModule.java:592) ~[jdk.security.auth:na]
	at java.base/javax.security.auth.login.LoginContext.invoke(LoginContext.java:726) ~[na:na]
	at java.base/javax.security.auth.login.LoginContext$4.run(LoginContext.java:665) ~[na:na]
	at java.base/javax.security.auth.login.LoginContext$4.run(LoginContext.java:663) ~[na:na]
	at java.base/java.security.AccessController.doPrivileged(Native Method) ~[na:na]
	at java.base/javax.security.auth.login.LoginContext.invokePriv(LoginContext.java:663) ~[na:na]
	at java.base/javax.security.auth.login.LoginContext.login(LoginContext.java:574) ~[na:na]
	at org.apache.kafka.common.security.authenticator.AbstractLogin.login(AbstractLogin.java:60) ~[kafka-clients-2.6.0.jar:na]
	at org.apache.kafka.common.security.authenticator.LoginManager.<init>(LoginManager.java:62) ~[kafka-clients-2.6.0.jar:na]
	at org.apache.kafka.common.security.authenticator.LoginManager.acquireLoginManager(LoginManager.java:112) ~[kafka-clients-2.6.0.jar:na]
	at org.apache.kafka.common.network.SaslChannelBuilder.configure(SaslChannelBuilder.java:158) ~[kafka-clients-2.6.0.jar:na]
	... 36 common frames omitted

2020-12-11 13:24:27.923 ERROR 4640 --- [ask-scheduler-1] o.s.integration.handler.LoggingHandler   : org.springframework.messaging.MessageDeliveryException: Dispatcher has no subscribers for channel 'application.produceChuckNorris-out-0'.; nested exception is org.springframework.integration.MessageDispatchingException: Dispatcher has no subscribers, failedMessage=GenericMessage [payload=byte[98], headers={contentType=application/json, id=c78ab9ad-4eca-d346-2e72-66b1a6290b0b, timestamp=1607682267916}], failedMessage=GenericMessage [payload=byte[98], headers={contentType=application/json, id=c78ab9ad-4eca-d346-2e72-66b1a6290b0b, timestamp=1607682267916}]
	at org.springframework.integration.channel.AbstractSubscribableChannel.doSend(AbstractSubscribableChannel.java:76)
	at org.springframework.integration.channel.AbstractMessageChannel.send(AbstractMessageChannel.java:317)
	at org.springframework.integration.channel.AbstractMessageChannel.send(AbstractMessageChannel.java:272)
	at org.springframework.messaging.core.GenericMessagingTemplate.doSend(GenericMessagingTemplate.java:187)
	at org.springframework.messaging.core.GenericMessagingTemplate.doSend(GenericMessagingTemplate.java:166)
	at org.springframework.messaging.core.GenericMessagingTemplate.doSend(GenericMessagingTemplate.java:47)
	at org.springframework.messaging.core.AbstractMessageSendingTemplate.send(AbstractMessageSendingTemplate.java:109)
	at org.springframework.integration.router.AbstractMessageRouter.doSend(AbstractMessageRouter.java:213)
	at org.springframework.integration.router.AbstractMessageRouter.handleMessageInternal(AbstractMessageRouter.java:195)
	at org.springframework.integration.handler.AbstractMessageHandler.handleMessage(AbstractMessageHandler.java:56)
	at org.springframework.integration.dispatcher.AbstractDispatcher.tryOptimizedDispatch(AbstractDispatcher.java:115)
	at org.springframework.integration.dispatcher.UnicastingDispatcher.doDispatch(UnicastingDispatcher.java:133)
	at org.springframework.integration.dispatcher.UnicastingDispatcher.dispatch(UnicastingDispatcher.java:106)
	at org.springframework.integration.channel.AbstractSubscribableChannel.doSend(AbstractSubscribableChannel.java:72)
	at org.springframework.integration.channel.AbstractMessageChannel.send(AbstractMessageChannel.java:317)
	at org.springframework.integration.channel.AbstractMessageChannel.send(AbstractMessageChannel.java:272)
	at org.springframework.messaging.core.GenericMessagingTemplate.doSend(GenericMessagingTemplate.java:187)
	at org.springframework.messaging.core.GenericMessagingTemplate.doSend(GenericMessagingTemplate.java:166)
	at org.springframework.messaging.core.GenericMessagingTemplate.doSend(GenericMessagingTemplate.java:47)
	at org.springframework.messaging.core.AbstractMessageSendingTemplate.send(AbstractMessageSendingTemplate.java:109)
	at org.springframework.integration.endpoint.SourcePollingChannelAdapter.handleMessage(SourcePollingChannelAdapter.java:196)
	at org.springframework.integration.endpoint.AbstractPollingEndpoint.messageReceived(AbstractPollingEndpoint.java:445)
	at org.springframework.integration.endpoint.AbstractPollingEndpoint.doPoll(AbstractPollingEndpoint.java:429)
	at org.springframework.integration.endpoint.AbstractPollingEndpoint.pollForMessage(AbstractPollingEndpoint.java:377)
	at org.springframework.integration.endpoint.AbstractPollingEndpoint.lambda$null$3(AbstractPollingEndpoint.java:324)
	at org.springframework.integration.util.ErrorHandlingTaskExecutor.lambda$execute$0(ErrorHandlingTaskExecutor.java:57)
	at org.springframework.core.task.SyncTaskExecutor.execute(SyncTaskExecutor.java:50)
	at org.springframework.integration.util.ErrorHandlingTaskExecutor.execute(ErrorHandlingTaskExecutor.java:55)
	at org.springframework.integration.endpoint.AbstractPollingEndpoint.lambda$createPoller$4(AbstractPollingEndpoint.java:321)
	at org.springframework.scheduling.support.DelegatingErrorHandlingRunnable.run(DelegatingErrorHandlingRunnable.java:54)
	at org.springframework.scheduling.concurrent.ReschedulingRunnable.run(ReschedulingRunnable.java:95)
	at java.base/java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:515)
	at java.base/java.util.concurrent.FutureTask.run(FutureTask.java:264)
	at java.base/java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:304)
	at java.base/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1128)
	at java.base/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:628)
	at java.base/java.lang.Thread.run(Thread.java:834)
Caused by: org.springframework.integration.MessageDispatchingException: Dispatcher has no subscribers, failedMessage=GenericMessage [payload=byte[98], headers={contentType=application/json, id=c78ab9ad-4eca-d346-2e72-66b1a6290b0b, timestamp=1607682267916}]
	at org.springframework.integration.dispatcher.UnicastingDispatcher.doDispatch(UnicastingDispatcher.java:139)
	at org.springframework.integration.dispatcher.UnicastingDispatcher.dispatch(UnicastingDispatcher.java:106)
	at org.springframework.integration.channel.AbstractSubscribableChannel.doSend(AbstractSubscribableChannel.java:72)
	... 36 more

2020-12-11 13:24:28.934 ERROR 4640 --- [ask-scheduler-2] o.s.integration.handler.LoggingHandler   : org.springframework.messaging.MessageDeliveryException: Dispatcher has no subscribers for channel 'application.produceChuckNorris-out-0'.; nested exception is org.springframework.integration.MessageDispatchingException: Dispatcher has no subscribers, failedMessage=GenericMessage [payload=byte[108], headers={contentType=application/json, id=dd53db7e-8cd6-515e-da94-fa5cd458bd51, timestamp=1607682268933}], failedMessage=GenericMessage [payload=byte[108], headers={contentType=application/json, id=dd53db7e-8cd6-515e-da94-fa5cd458bd51, timestamp=1607682268933}]
	at org.springframework.integration.channel.AbstractSubscribableChannel.doSend(AbstractSubscribableChannel.java:76)
	at org.springframework.integration.channel.AbstractMessageChannel.send(AbstractMessageChannel.java:317)
	at org.springframework.integration.channel.AbstractMessageChannel.send(AbstractMessageChannel.java:272)
	at org.springframework.messaging.core.GenericMessagingTemplate.doSend(GenericMessagingTemplate.java:187)
	at org.springframework.messaging.core.GenericMessagingTemplate.doSend(GenericMessagingTemplate.java:166)
	at org.springframework.messaging.core.GenericMessagingTemplate.doSend(GenericMessagingTemplate.java:47)
	at org.springframework.messaging.core.AbstractMessageSendingTemplate.send(AbstractMessageSendingTemplate.java:109)
	at org.springframework.integration.router.AbstractMessageRouter.doSend(AbstractMessageRouter.java:213)
	at org.springframework.integration.router.AbstractMessageRouter.handleMessageInternal(AbstractMessageRouter.java:195)
	at org.springframework.integration.handler.AbstractMessageHandler.handleMessage(AbstractMessageHandler.java:56)
	at org.springframework.integration.dispatcher.AbstractDispatcher.tryOptimizedDispatch(AbstractDispatcher.java:115)
	at org.springframework.integration.dispatcher.UnicastingDispatcher.doDispatch(UnicastingDispatcher.java:133)
	at org.springframework.integration.dispatcher.UnicastingDispatcher.dispatch(UnicastingDispatcher.java:106)
	at org.springframework.integration.channel.AbstractSubscribableChannel.doSend(AbstractSubscribableChannel.java:72)
	at org.springframework.integration.channel.AbstractMessageChannel.send(AbstractMessageChannel.java:317)
	at org.springframework.integration.channel.AbstractMessageChannel.send(AbstractMessageChannel.java:272)
	at org.springframework.messaging.core.GenericMessagingTemplate.doSend(GenericMessagingTemplate.java:187)
	at org.springframework.messaging.core.GenericMessagingTemplate.doSend(GenericMessagingTemplate.java:166)
	at org.springframework.messaging.core.GenericMessagingTemplate.doSend(GenericMessagingTemplate.java:47)
	at org.springframework.messaging.core.AbstractMessageSendingTemplate.send(AbstractMessageSendingTemplate.java:109)
	at org.springframework.integration.endpoint.SourcePollingChannelAdapter.handleMessage(SourcePollingChannelAdapter.java:196)
	at org.springframework.integration.endpoint.AbstractPollingEndpoint.messageReceived(AbstractPollingEndpoint.java:445)
	at org.springframework.integration.endpoint.AbstractPollingEndpoint.doPoll(AbstractPollingEndpoint.java:429)
	at org.springframework.integration.endpoint.AbstractPollingEndpoint.pollForMessage(AbstractPollingEndpoint.java:377)
	at org.springframework.integration.endpoint.AbstractPollingEndpoint.lambda$null$3(AbstractPollingEndpoint.java:324)
	at org.springframework.integration.util.ErrorHandlingTaskExecutor.lambda$execute$0(ErrorHandlingTaskExecutor.java:57)
	at org.springframework.core.task.SyncTaskExecutor.execute(SyncTaskExecutor.java:50)
	at org.springframework.integration.util.ErrorHandlingTaskExecutor.execute(ErrorHandlingTaskExecutor.java:55)
	at org.springframework.integration.endpoint.AbstractPollingEndpoint.lambda$createPoller$4(AbstractPollingEndpoint.java:321)
	at org.springframework.scheduling.support.DelegatingErrorHandlingRunnable.run(DelegatingErrorHandlingRunnable.java:54)
	at org.springframework.scheduling.concurrent.ReschedulingRunnable.run(ReschedulingRunnable.java:95)
	at java.base/java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:515)
	at java.base/java.util.concurrent.FutureTask.run(FutureTask.java:264)
	at java.base/java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:304)
	at java.base/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1128)
	at java.base/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:628)
	at java.base/java.lang.Thread.run(Thread.java:834)
Caused by: org.springframework.integration.MessageDispatchingException: Dispatcher has no subscribers, failedMessage=GenericMessage [payload=byte[108], headers={contentType=application/json, id=dd53db7e-8cd6-515e-da94-fa5cd458bd51, timestamp=1607682268933}]
	at org.springframework.integration.dispatcher.UnicastingDispatcher.doDispatch(UnicastingDispatcher.java:139)
	at org.springframework.integration.dispatcher.UnicastingDispatcher.dispatch(UnicastingDispatcher.java:106)
	at org.springframework.integration.channel.AbstractSubscribableChannel.doSend(AbstractSubscribableChannel.java:72)
	... 36 more

2020-12-11 13:24:29.089  INFO 4640 --- [           main] o.s.b.web.embedded.netty.NettyWebServer  : Netty started on port(s): 8080
2020-12-11 13:24:29.099  INFO 4640 --- [           main] c.e.k.KotlinKafkaApplicationKt           : Started KotlinKafkaApplicationKt in 6.035 seconds (JVM running for 7.781)
2020-12-11 13:24:29.946 ERROR 4640 --- [ask-scheduler-1] o.s.integration.handler.LoggingHandler   : org.springframework.messaging.MessageDeliveryException: Dispatcher has no subscribers for channel 'application.produceChuckNorris-out-0'.; nested exception is org.springframework.integration.MessageDispatchingException: Dispatcher has no subscribers, failedMessage=GenericMessage [payload=byte[98], headers={contentType=application/json, id=68841897-38c9-6f1e-ee3b-e60f46ca9e63, timestamp=1607682269944}], failedMessage=GenericMessage [payload=byte[98], headers={contentType=application/json, id=68841897-38c9-6f1e-ee3b-e60f46ca9e63, timestamp=1607682269944}]
	at org.springframework.integration.channel.AbstractSubscribableChannel.doSend(AbstractSubscribableChannel.java:76)
	at org.springframework.integration.channel.AbstractMessageChannel.send(AbstractMessageChannel.java:317)
	at org.springframework.integration.channel.AbstractMessageChannel.send(AbstractMessageChannel.java:272)
	at org.springframework.messaging.core.GenericMessagingTemplate.doSend(GenericMessagingTemplate.java:187)
	at org.springframework.messaging.core.GenericMessagingTemplate.doSend(GenericMessagingTemplate.java:166)
	at org.springframework.messaging.core.GenericMessagingTemplate.doSend(GenericMessagingTemplate.java:47)
	at org.springframework.messaging.core.AbstractMessageSendingTemplate.send(AbstractMessageSendingTemplate.java:109)
	at org.springframework.integration.router.AbstractMessageRouter.doSend(AbstractMessageRouter.java:213)
	at org.springframework.integration.router.AbstractMessageRouter.handleMessageInternal(AbstractMessageRouter.java:195)
	at org.springframework.integration.handler.AbstractMessageHandler.handleMessage(AbstractMessageHandler.java:56)
	at org.springframework.integration.dispatcher.AbstractDispatcher.tryOptimizedDispatch(AbstractDispatcher.java:115)
	at org.springframework.integration.dispatcher.UnicastingDispatcher.doDispatch(UnicastingDispatcher.java:133)
	at org.springframework.integration.dispatcher.UnicastingDispatcher.dispatch(UnicastingDispatcher.java:106)
	at org.springframework.integration.channel.AbstractSubscribableChannel.doSend(AbstractSubscribableChannel.java:72)
	at org.springframework.integration.channel.AbstractMessageChannel.send(AbstractMessageChannel.java:317)
	at org.springframework.integration.channel.AbstractMessageChannel.send(AbstractMessageChannel.java:272)
	at org.springframework.messaging.core.GenericMessagingTemplate.doSend(GenericMessagingTemplate.java:187)
	at org.springframework.messaging.core.GenericMessagingTemplate.doSend(GenericMessagingTemplate.java:166)
	at org.springframework.messaging.core.GenericMessagingTemplate.doSend(GenericMessagingTemplate.java:47)
	at org.springframework.messaging.core.AbstractMessageSendingTemplate.send(AbstractMessageSendingTemplate.java:109)
	at org.springframework.integration.endpoint.SourcePollingChannelAdapter.handleMessage(SourcePollingChannelAdapter.java:196)
	at org.springframework.integration.endpoint.AbstractPollingEndpoint.messageReceived(AbstractPollingEndpoint.java:445)
	at org.springframework.integration.endpoint.AbstractPollingEndpoint.doPoll(AbstractPollingEndpoint.java:429)
	at org.springframework.integration.endpoint.AbstractPollingEndpoint.pollForMessage(AbstractPollingEndpoint.java:377)
	at org.springframework.integration.endpoint.AbstractPollingEndpoint.lambda$null$3(AbstractPollingEndpoint.java:324)
	at org.springframework.integration.util.ErrorHandlingTaskExecutor.lambda$execute$0(ErrorHandlingTaskExecutor.java:57)
	at org.springframework.core.task.SyncTaskExecutor.execute(SyncTaskExecutor.java:50)
	at org.springframework.integration.util.ErrorHandlingTaskExecutor.execute(ErrorHandlingTaskExecutor.java:55)
	at org.springframework.integration.endpoint.AbstractPollingEndpoint.lambda$createPoller$4(AbstractPollingEndpoint.java:321)
	at org.springframework.scheduling.support.DelegatingErrorHandlingRunnable.run(DelegatingErrorHandlingRunnable.java:54)
	at org.springframework.scheduling.concurrent.ReschedulingRunnable.run(ReschedulingRunnable.java:95)
	at java.base/java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:515)
	at java.base/java.util.concurrent.FutureTask.run(FutureTask.java:264)
	at java.base/java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:304)
	at java.base/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1128)
	at java.base/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:628)
	at java.base/java.lang.Thread.run(Thread.java:834)
Caused by: org.springframework.integration.MessageDispatchingException: Dispatcher has no subscribers, failedMessage=GenericMessage [payload=byte[98], headers={contentType=application/json, id=68841897-38c9-6f1e-ee3b-e60f46ca9e63, timestamp=1607682269944}]
	at org.springframework.integration.dispatcher.UnicastingDispatcher.doDispatch(UnicastingDispatcher.java:139)
	at org.springframework.integration.dispatcher.UnicastingDispatcher.dispatch(UnicastingDispatcher.java:106)
	at org.springframework.integration.channel.AbstractSubscribableChannel.doSend(AbstractSubscribableChannel.java:72)
	... 36 more


Process finished with exit code -1
