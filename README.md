- `java_cli` は、 `java -jar openapi-generator-cli.jar generate -i petstore.yaml -o java_cli -g java` で作った。
- `java_cli_app` は、 `gradle init` で Java Application用に作ったプロジェクト。
  - App.javaは自前実装
  - build.gradleに、追加implementationが必要。

