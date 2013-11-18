JRuby実装のビルドとインストール
----------

    // ビルド
    $ jgem update --system
    $ jgem install yard
    $ jgem install rake-compiler
    $ jgem build eventmachine.gemspec

    // jruby用のgemを作成
    $ jruby -S rake java gem

    // インストール
    $ jgem install pkg/sonixlabs-eventmachine-java-1.0.x-java
