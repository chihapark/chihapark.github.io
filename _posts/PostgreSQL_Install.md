---
layout: post
title: Welcome to Chiha
author: Chiha Park
date: '2019-07-19 14:35:23 +0530'
category: personal
summary: First Post
thumbnail: posts/hello.jpg
---

# PostgreSQL 설치

- PostgreSQL 9.6 버전을 기준으로 Centos 7.4에 설치합니다.
- DB Engine 디렉토리 : /PG/PGDATABASE
- DB DATA 디렉토리: /data



## 1. PostgreSQL 파일 다운로드

- https://www.enterprisedb.com/download-postgresql-binaries 사이트에서 binary 파일 다운로드



## 2. 디렉토리 생성

```
mkdir -p /PG/PGDATABASE				# PostgreSQL Engine 영역
mkdir -p /data/PGDATABASE/data/pg  	# PostgreSQL Data 영역
mkdir -p /data/PGDATABASE/pg_xlog   # PostgreSQL xlog 영역 (10버전 이후는 wal 영역)
mkdir -p /data/PGDATABASE/arch      # PostgesSQL Archiving 영역
mkdir -p /data/PGDATABASE/TS01      # PostgreSQL Table Space 영역
```



## 3. Kernel Parameter 설정

```

```





