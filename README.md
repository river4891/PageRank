# email PageRank

## setup-env

```bash
cconda env create -f ./environment.yml
```


## data describe

|   文件名   |   字段   |  含义  |
| :---------: | :------: | :----: |
| Aliases.csv |    Id    | 别名Id |
|            |  Alias  |  别名  |
|            | PersonId | 人名Id |

| 文件名      | 字段 |  含义  |
| ----------- | :--: | :----: |
| Persons.csv |  Id  | 人名Id |
|             | Name |  姓名  |

| 文件名             |   字段   |    含义    |
| ------------------ | :-------: | :--------: |
| EmailReceivers.cvs |    Id    | 邮箱接收Id |
|                    |  EmailId  |   邮件Id   |
|                    | PersonsId |  接收人Id  |

|  文件名  |             字段             |      含义      |
| :-------: | :--------------------------: | :------------: |
| Email.csv |              Id              |     邮箱Id     |
|          |          DocNumber          |     文档号     |
|          |       MetadataSubject       |   元数据主题   |
|          |          MetadataTo          |  元数据发送到  |
|          |         MetadataFrom         |   元数据来源   |
|          |        SenderPersonId        |    发送人Id    |
|          |       MetadataDateSent       | 元数据发送日期 |
|          |     MetadataDateReleased     | 元数据发行时间 |
|          |       MetadataPdfLink       | 元数据PDF链接 |
|          |      MetadataCaseNumber      |  元数据状况码  |
|          |    MetadataDocumentClass    |  元数据文档类  |
|          |       ExtractedSubject       |                |
|          |         ExtractedTo         |                |
|          |        ExtractedFrom        |                |
|          |         ExtractedCc         |                |
|          |      ExtractedDateSent      |                |
|          |     ExtractedCaseNumber     |                |
|          |      ExtractedDocNumber      |                |
|          |    ExtractedDateReleased    |                |
|          | ExtractedReleaseInPartOrFull |                |
|          |      ExtractedBodyText      |                |
|          |           RawText           |                |
