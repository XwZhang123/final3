# final3
准备数据：使用相机参数导入代码生成并保存相机参数：配置 NeRF 训练数据
并将相机参数和图像数据转换为 NeRF 可以读取的格式，相机参数保存在 camera_params.json 中，并转换其格式
导入5张图片后

在NeRF训练中获取bash命令行
使用bash命令行
克隆 NeRF 框架并安装依赖项
将 JSON 文件和图像数据放到 nerf-pytorch 目录下，并使用命令进行训练，根据需要调整训练参数（如 batch size, learning rate, 等等）。
训练完成后，使用命令渲染视频

使用PSNR指标代码定量评价测试结果
