# Card
NJUCS 2014 创新实验——安卓开发，图像识别

目前已经完成的功能：
	从相册获取照片（URI）
	使用系统相机拍摄得到照片（URI）
	基本框架搭建
								——by 152
	联系人界面
	将获取信息传递到上述界面并在检测后显示
								——by 147
						
中期考核前尽量完成至：
	配置OpenCV Android环境并进行简单测试
	Web 查询对返回结果的分析（已经存在测试模块）
	联系人界面完善
	
BUG未修复：
	得到图片的URI之后，在转换至Bitmap时，如果图片尺寸过大（4096*4096）会使得位图存不下这么多数据，以至于大图片无法显示。
	联系人界面在拍照得到大尺寸图片后无法显示联系人信息
	
注意：
	任务范围外的代码文件，布局文件尽量不要修改，避免Merge时的冲突
	不要私自删除文件
	
	