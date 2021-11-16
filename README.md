# fluentd-for-docker-containers

fluentd-for-docker-containers は、Docker コンテナ（Kubernetesの対象Pod）のログを収集するためのリソースです。  
fluentd を動かすためには、 fluentd-for-docker-containers の他に、下記のようなレポジトリを参照して、設定を行う必要があります。  

* fluentd-for-mongodb  
* fluentd-core-kube   
* fluentd-for-containers-mongodb-kube  
* fluentd-for-avis

## 動作環境
fluentd-for-docker-containers は、以下の動作環境を前提としています。  

* OS: Linux OS  
* CPU: ARM/AMD/Intel  
* Kubernetes  

## サンプル定義ファイル

本リポジトリには、 fluentd-for-docker-containers としてのサンプル定義ファイル fluentd-configmap.yaml が格納されています。

## AION での fluentd の動作  
AION で fluentd を動かすためには、主にエッジコンピューティング環境の特性とシステム要求に留意して、aion-core-manifests に適切な追加設定を行う必要があります。

