JRuby実装のビルドとインストール
----------

    $ jgem update --system
    $ jgem install yard
    $ jgem install rake-compiler
    $ jgem build eventmachine.gemspec
    $ jruby -S rake java gem
    $ jgem install pkg/sonixlabs-eventmachine-java-1.0.x-java
