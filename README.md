# SMS-bomber

SMS-Bomber-test 是一个使用 Python 编写的短信轰炸机，利用多个短信接口向指定手机号码发送大量短信，仅供学习和娱乐使用，请勿用于非法用途。

## 功能

- 支持多个电话号码
- 支持多个短信接口
- 并发异步请求
- 自动过滤非 URL 字段
- 日志记录错误信息

## 安装

### 环境要求

- Python 3.7+
- aiohttp
- requests

### 安装步骤

1. 克隆或下载项目：

```python
git clone https://github.com/U1timater/SMS-Bomber-test.git
```

2. 安装依赖：

```python
pip install requests logging aiohttp urllib
```

## 使用方法

1. 编辑 `smstest.py` 文件，修改电话号码列表 `phone_numbers`，添加或删除要轰炸的电话号码。

```python
phone_numbers = ["1xxxxxxxxxx", "1xxxxxxxxxx"]  # 可以修改这个列表以添加或删除电话号码
```

2. 运行 main.py：

```python
python main.py
```

程序将开始向指定的电话号码发送大量短信。如有错误信息，会记录在 error_log.log 文件中。

##注意事项

请勿将本工具用于非法用途，否则后果自负。
如有问题，请查看 error_log.log 文件以获取详细错误信息。

##许可证

本项目基于 MIT 许可证发布。
