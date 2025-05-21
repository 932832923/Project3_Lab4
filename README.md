# Project3_Lab4
软件项目研发实践（3）Lab4

右键“start”模块，或者选择File，然后New>Other>TensorFlow Lite Model

![image](https://github.com/user-attachments/assets/7f4eb672-5bab-403f-95d7-145f07ea41fb)

选择已经下载的自定义的训练模型。本教程模型训练任务以后完成，这里选择finish模块中ml文件下的FlowerModel.tflite。

![image](https://github.com/user-attachments/assets/395e4cb9-beaf-4709-999c-c239f606a9da)

最终TensorFlow Lite模型被成功导入，并生成摘要信息

![image](https://github.com/user-attachments/assets/eef93734-b2c4-4767-8683-07ec917d1037)

检查代码中的TODO项

本项目初始代码中包括了若干的TODO项，以导航项目中未完成之处。为了方便起见，首先查看TODO列表视图，View>Tool

![image](https://github.com/user-attachments/assets/1e5cd76f-edfa-486e-9a7c-83a9532fa451)

默认情况下了列出项目所有的TODO项，进一步按照模块分组（Group By）

![image](https://github.com/user-attachments/assets/273c44ea-2a22-4fcf-b4d7-c7b7f0842115)

添加代码重新运行APP
定位“start”模块MainActivity.kt文件的TODO 1，添加初始化训练模型的代码

![image](https://github.com/user-attachments/assets/fb0691fa-d897-49f3-8d08-04b83d6e42ea)

在 CameraX 的 analyze 方法内部，需要将摄像头输入的 ImageProxy 转换为 Bitmap 对象，并进一步转化为 TensorImage，然后对图像进行处理并生成识别结果：包括根据 score 属性将结果按概率从高到低排序，选出前 k 个最可能的结果（k 由常量 MAX_RESULT_DISPLAY 定义），并将每个识别结果（含 label 和 score）封装到 Recognition 数据对象中，供后续 RecyclerView 显示使用，同时注释或删除原有用于虚拟显示识别结果的相关代码。

![image](https://github.com/user-attachments/assets/99fd526d-260b-4667-be57-ea50eff2cfb6)
![1](https://github.com/user-attachments/assets/396ffe51-7442-42d9-b761-f0249ec82a43)



