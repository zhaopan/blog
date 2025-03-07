---
date: "2009-04-25 14:01:01"
toc: true
id: 4
slug: /posts/docker_mysql
aliases:
    - /archives/2009/04/4/
tags:
    - 随笔
title: docker_mysql
---

# config

```yml
# 128MB
innodb_buffer_pool_chunk_size=134217728
# 4 instances
innodb_buffer_pool_instances=4
# 4GB
innodb_buffer_pool_size=4294967296
```

eg

```bash
set global innodb_buffer_pool_size=4294967296;

# cat:
show VARIABLES like '%innodb_buffer_pool%';
```
