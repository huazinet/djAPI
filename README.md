# 短剧api永久免费接口稳定性高，欢迎对接。
## 全网短剧API接口


概述：
> 本文档提供短剧搜索服务API的对接指南，包括API功能、请求参数、返回数据格式及示例。 本接口主要是用来存储夸克网盘资源然后对接短剧机器人，来实现盈利。

功能描述：
> 短剧搜索服务API提供短剧名称的搜索功能，用户可通过API提交短剧名称关键字，获取相应的短剧信息列表。

搜索接口地址：<br/>
> `https://pan.sharehub.club/api/search?page_no=1&page_size=20&title=桃花马上请长缨`

返回数据:
```
{
	'code': 200,
	'message': '获取成功',
	'data': {
		'total_result': 1,
		'items': [{
			'id': 10597,
			'source_category_id': 1,
			'title': '桃花马上请长缨（91集）马秋元',
			'url': 'https://pan.quark.cn/s/90106264c043',
			'is_time': 0,
			'times': '2024-08-22',
			'category': {
				'source_category_id': 1,
				'name': '短剧'
			}
		}]
	}
}
```
API接口可用于微信搜索机器人，对接各大程序，网站，网页。
如有未搜到剧集，将在反馈后24小时更新！！！！
