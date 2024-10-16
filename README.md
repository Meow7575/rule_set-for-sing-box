# Rules
**singbox的规则集几乎全部基于zhiqiang的surge规则集并用zhiqiang的脚本转换**

## surge

**[Rule]**

```
RULE-SET,https://raw.githubusercontent.com/../xxxx.list,policy
```

## clash

**rule-providers:**

```
  xxxx:
    type: http
    behavior: classical
    format: text
    url: 
```

**rules:**

```
  - RULE-SET,xxxx,#策略组
```

## sing-box

**rule_set**

```
{
  "type": "source",
  "tag": "",
  "format": "",
  "url": ""
}
```
  
**rules**
  
```
{
  "rule_set": "",
  "outbound": ""
}
```
