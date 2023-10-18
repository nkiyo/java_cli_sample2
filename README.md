# openapi-generator-cli で作ったJavaクライアントをビルド実行するサンプル

- `java_cli` ディレクトリは、 `java -jar openapi-generator-cli.jar generate -i petstore.yaml -o java_cli -g java` で作った。
- `java_cli_app` ディレクトリは、 `gradle init` で Java Application用に作ったプロジェクト。
  - App.javaは自前実装
  - build.gradleに、追加implementationが必要。（ないと実行時にNoClassDefFoundError）

