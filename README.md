# BDSocket

BDScoket 标准是从原BDX平台的BDXWebsocketAPI插件接口修改而来的通用应用接口标准。

开发者可以在各类机器人平台实现 BDSocket 标准，从而使用户可以将基于 BDSocket 标准的机器人项目无缝迁移到这些平台。

当需要添加新的功能（例如新的事件、API、消息段类型等）时，可以通过 pull request 扩充本标准，此后其它 BDSocket 实现在添加同一功能时应参考扩充后的标准。