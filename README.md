実行手順
====

dockerのインストールとdocker machine 操作
-----
* 参照
 * https://docs.docker.com/toolbox/toolbox_install_mac/
* docker machine 停止
 * docker-machine stop default
* docker machine 起動
 * docker-machine start default
 * eval $(docker-machine env default)

sugarcrmのビルドと起動
----
* docker-compose build
* docker-compose up


sugarcrmへアクセス
----
* ゲストmachineのIPを確認
 * docker-machine ls
* http://machine_ip/sugarcrm


sugarcrmインストール
----

* database hostname
 * db
* username
 * root
* password
 * root

