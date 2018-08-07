```
private val text by lazy<TextView> { findViewById(R.id.text) }
```

这里要使用`lazy`，否则会报错，因为在字段初始化的时候，`findViewById(R.id.text)`是拿不到的。
