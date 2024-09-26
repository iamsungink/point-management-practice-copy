# point-management-practice-copy

## 출처 : https://github.com/kker5/point-management-practice

실행방법

```shell
# 원래대로라면..
java -jar batch.jar --spring.batch.job.names=expirePointJob
```

```shell
## 실수방지를 위하여
java -jar batch.jar --job.name=expirePointJob
```
