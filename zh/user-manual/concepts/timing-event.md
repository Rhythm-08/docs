---
title: Timing Event
---

# 定时事件

Vanus 提供事件定时的特性。此特性可以指定事件的交付时间点（例如 2022-01-01T08:00:00Z）。一旦事件到达 Eventbus，它将等待交付时间到期，然后才可以被消费。