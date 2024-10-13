# Rules

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
    path: ./ruleset/xxxx.list 
    url: "https://raw.githubusercontent.com/../xxxx.list"
    interval: 86400
```

**rules:**

```
  - RULE-SET,xxxx,policy
```

## sing-box

**rule_set**

```
{
  "type": "remote",
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
