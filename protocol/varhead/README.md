说明
====

这个包实现了变长头部的分包协议。

每个消息包由包头和包体构成，包头的内容是以Uvarint格式编码的包体长度信息。