# IContentApi.GetContentIdList method

获取指定栏目的所有内容Id的列表。

```csharp
public List<int> GetContentIdList(int siteId, int channelId)
```

| parameter | description |
| --- | --- |
| siteId | 站点Id。 |
| channelId | 栏目Id。 |

## Return Value

如果站点与栏目存在，则返回此栏目下的所有内容的Id列表；否则返回 null。

## See Also

* interface [IContentApi](../IContentApi.md)
* namespace [SiteServer.Plugin](../../SiteServer.Plugin.md)

<!-- DO NOT EDIT: generated by xmldocmd for SiteServer.Plugin.dll -->