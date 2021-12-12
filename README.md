# 把包发布到pypi的测试

流程总结：

1.  设置一些配置文件

    -   pyproject.toml   # build依赖

    -   setup.cfg            # pypi主页一些信息

2.  build打包

3.  创建pypi账号，把打包的内容upload到pypi

    

 完成后就可以使用了

[上传成功的链接](https://test.pypi.org/project/wzc-mypackage/)

```
pip install -i https://test.pypi.org/simple/ wzc-mypackage
```



## [官方教程链接](https://packaging.python.org/en/latest/tutorials/packaging-projects/)

