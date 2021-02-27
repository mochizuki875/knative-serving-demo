# Knative Serving Demo
## 概要
Knative ServingをセットアップしたKubernetesクラスタ上にサンプルアプリをデプロイするための  
Knativeマニフェストファイルが含まれています。

### サンプルアプリ
mochizuki875/spring-boot-web  
https://github.com/mochizuki875/spring-boot-web

## 動作環境
Kubernetes: v1.20.2  
Knative Serving: v0.20.0

## Quick Start
以下コマンドによりサンプルアプリをKnative上にデプロイできます。

~~~
kubectl apply -f service/service-spring.yml
~~~

## 備考
2021/03/09 Kubernetes Novice Tokyo #9で実施したKnative Servingのデモ資材です。  
発表資料と合わせてご参照ください。  
https://speakerdeck.com/mochizuki875/knativedekubernetesworakunisuru