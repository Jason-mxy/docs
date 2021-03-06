# IDatabaseApi.ExecuteCurrentId method (1 of 3)

获取当前数据库类型INSERT SQL语句执行后表生成的自增长Id

```csharp
public int ExecuteCurrentId(IDbConnection connection, string tableName, string idColumnName)
```

| parameter | description |
| --- | --- |
| connection | 有效的IDbConnection。 |
| tableName | 数据库表名称。 |
| idColumnName | 自增长字段名称。 |

## Return Value

INSERT SQL语句执行后表生成的自增长Id值。

## See Also

* interface [IDatabaseApi](../IDatabaseApi.md)
* namespace [SiteServer.Plugin](../../SiteServer.Plugin.md)

---

# IDatabaseApi.ExecuteCurrentId method (2 of 3)

获取当前数据库类型INSERT SQL语句执行后表生成的自增长Id

```csharp
public int ExecuteCurrentId(IDbTransaction transaction, string tableName, string idColumnName)
```

| parameter | description |
| --- | --- |
| transaction | 有效的IDbTransaction。 |
| tableName | 数据库表名称。 |
| idColumnName | 自增长字段名称。 |

## Return Value

INSERT SQL语句执行后表生成的自增长Id值。

## See Also

* interface [IDatabaseApi](../IDatabaseApi.md)
* namespace [SiteServer.Plugin](../../SiteServer.Plugin.md)

---

# IDatabaseApi.ExecuteCurrentId method (3 of 3)

获取当前数据库类型INSERT SQL语句执行后表生成的自增长Id。

```csharp
public int ExecuteCurrentId(string connectionString, string tableName, string idColumnName)
```

| parameter | description |
| --- | --- |
| connectionString | 数据库连接字符串。 |
| tableName | 数据库表名称。 |
| idColumnName | 自增长字段名称。 |

## Return Value

INSERT SQL语句执行后表生成的自增长Id值。

## See Also

* interface [IDatabaseApi](../IDatabaseApi.md)
* namespace [SiteServer.Plugin](../../SiteServer.Plugin.md)

<!-- DO NOT EDIT: generated by xmldocmd for SiteServer.Plugin.dll -->
