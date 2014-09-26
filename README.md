## つかいかた

事前にコマンドプロンプトから以下を実行し、chocolatey をインストールしておく。

     @powershell -NoProfile -ExecutionPolicy unrestricted -Command "iex ((new-object net.webclient).DownloadString('https://chocolatey.org/install.ps1'))" && SET PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin

chocolateyのインストールが完了したら以下のコマンドでパッケージをどかどかーっとインストール

    cinst packages.config

