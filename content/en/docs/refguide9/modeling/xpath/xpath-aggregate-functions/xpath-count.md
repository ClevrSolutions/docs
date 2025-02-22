---
title: "XPath count"
url: /refguide9/xpath-count/
---

## Overview

The `count()` function counts all objects retrieved by the enclosed query and returns the value as an integer.

## Examples

This query returns a count of all the placed orders:

```java
count(//Sales.Order)
```

This query returns a count of all the orders placed by a customer named "Jansen":

```java
count(//Sales.Order[Sales.Customer_Order/Sales.Customer/Name = 'Jansen'])
```
