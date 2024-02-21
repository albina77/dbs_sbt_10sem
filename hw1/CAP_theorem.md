# CAP теорема

## DragonFly

Согласно слогану на их [главной странице](https://www.dragonflydb.io)  
> Redis® with wings.  

эта база данных явно является производной от Redis.  
  
Redis занимает место [CP](https://sprksh.github.io/distributed-systems/2020/04/17/nosql-cap-theorem-distributed-systems-summary.html):  
> Redis: It is put under CP because redis cluster becomes unavailable in case of partition. Redis Sentinel & Redis cluster are two types of distributed redis setup.  

При этом кажется интуитивно понятным, что увеличение количества потоков не может положительно влиять на доступность системы, оно лишь увеличивает рассинхронизацию

![Примеры БД отностельно CAP теоремы](https://qph.cf2.quoracdn.net/main-qimg-08457045b0d56b6dd938f3b5d5a3b197-pjlq)

## ScyllaDB

Scylla [отвечает](https://www.scylladb.com/glossary/cap-theorem/#:~:text=In%20computer%20science%2C%20the%20CAP,and%20partition%20tolerance%20(CAP).) на этот вопрос сама:  
>ScyllaDB is a PA/EL highly available, partition tolerant, low latency database system. 

## ArenadataDB


![ArenadataDB](https://arenadata.tech/wp-content/uploads/2020/05/opengraph-adb.png)

> [Massively Parallel PostgreSQL for Analytics](https://greenplum.org)

![Postgres](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTMNk1JKd7JjvefMp_Ucjj-cOrAsiETS57QIjZLPsoXlA&s)

Вывод: **СА!**

*Да, мои рассуждения довольно топорны, но киньте в меня камень те, кто без греха...*


```python

```
