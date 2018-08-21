# google_translate_api_python
A python wrapped free and unlimited API for Google Translate.

### Install

```
pip insatll https://github.com/Ljqiii/google_translate_api_python/archive/master.zip
```



### Basic Usage

```python
import google_translate_api_python
a=google_translate_api_python.GoogleTranslate(domainnames="cn",sl="en",tl="zh-CN")
print(a.trans("Hello World."))
print(a.trans("I am a robot."))
```

**sl** 

  from Language

**tl**

  to Language

**domainnames**

  google domain names. for example, if domainnames="com" ,the url is "translate.google.com". In China google.com is blocked by GFW,you can use "cn". 

------

| value | Language |
| ----- | -------- |
| sq    | 阿尔巴尼亚语     |
| ar    | 阿拉伯语     |
| am    | 阿姆哈拉语     |
| az    | 阿塞拜疆语     |
| ga    | 爱尔兰语     |
| et    | 爱沙尼亚语     |
| eu    | 巴斯克语     |
| be    | 白俄罗斯语     |
| bg    | 保加利亚语     |
| is    | 冰岛语     |
| pl    | 波兰语     |
| bs    | 波斯尼亚语     |
| fa    | 波斯语     |
| af    | 布尔语(南非荷兰语)     |
| da    | 丹麦语     |
| de    | 德语     |
| ru    | 俄语     |
| fr    | 法语     |
| tl    | 菲律宾语     |
| fi    | 芬兰语     |
| fy    | 弗里西语     |
| km    | 高棉语     |
| ka    | 格鲁吉亚语     |
| gu    | 古吉拉特语     |
| kk    | 哈萨克语     |
| ht    | 海地克里奥尔语     |
| ko    | 韩语     |
| ha    | 豪萨语     |
| nl    | 荷兰语     |
| ky    | 吉尔吉斯语     |
| gl    | 加利西亚语     |
| ca    | 加泰罗尼亚语     |
| cs    | 捷克语     |
| kn    | 卡纳达语     |
| co    | 科西嘉语     |
| hr    | 克罗地亚语     |
| ku    | 库尔德语     |
| la    | 拉丁语     |
| lv    | 拉脱维亚语     |
| lo    | 老挝语     |
| lt    | 立陶宛语     |
| lb    | 卢森堡语     |
| ro    | 罗马尼亚语     |
| mg    | 马尔加什语     |
| mt    | 马耳他语     |
| mr    | 马拉地语     |
| ml    | 马拉雅拉姆语     |
| ms    | 马来语     |
| mk    | 马其顿语     |
| mi    | 毛利语     |
| mn    | 蒙古语     |
| bn    | 孟加拉语     |
| my    | 缅甸语     |
| hmn   | 苗语     |
| xh    | 南非科萨语     |
| zu    | 南非祖鲁语     |
| ne    | 尼泊尔语     |
| no    | 挪威语     |
| pa    | 旁遮普语     |
| pt    | 葡萄牙语     |
| ps    | 普什图语     |
| ny    | 齐切瓦语     |
| ja    | 日语     |
| sv    | 瑞典语     |
| sm    | 萨摩亚语     |
| sr    | 塞尔维亚语     |
| st    | 塞索托语     |
| si    | 僧伽罗语     |
| eo    | 世界语     |
| sk    | 斯洛伐克语     |
| sl    | 斯洛文尼亚语     |
| sw    | 斯瓦希里语     |
| gd    | 苏格兰盖尔语     |
| ceb   | 宿务语     |
| so    | 索马里语     |
| tg    | 塔吉克语     |
| te    | 泰卢固语     |
| ta    | 泰米尔语     |
| th    | 泰语     |
| tr    | 土耳其语     |
| cy    | 威尔士语     |
| ur    | 乌尔都语     |
| uk    | 乌克兰语     |
| uz    | 乌兹别克语     |
| es    | 西班牙语     |
| iw    | 希伯来语     |
| el    | 希腊语     |
| haw   | 夏威夷语     |
| sd    | 信德语     |
| hu    | 匈牙利语     |
| sn    | 修纳语     |
| hy    | 亚美尼亚语     |
| ig    | 伊博语     |
| it    | 意大利语     |
| yi    | 意第绪语     |
| hi    | 印地语     |
| su    | 印尼巽他语     |
| id    | 印尼语     |
| jw    | 印尼爪哇语     |
| en    | 英语     |
| yo    | 约鲁巴语     |
| vi    | 越南语     |
| zh - CN   | 中文     |


