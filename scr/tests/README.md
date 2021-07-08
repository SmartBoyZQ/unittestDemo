##固件 pytest.fixture()
将夹具函数名称作为参数传递到测试用例函数当中
@pytest.mark.usefixtures("夹具函数名称")
@pytest.fixture(autouse=True)，设置了 autouse，就可以不用上述两种手动方式，默认就会使用夹具
pytest 文件命 --setup-show 回溯fixture的执行过程
##捕获异常 pytest.raises()
##函数进行标记 pytest.mark()
执行标记函数 pytest -m "**"
##参数化pytest.mark.parametrize(argnames,argvalues)
执行测试 pytest -v 
pytest.param(argvalues,id/ids)