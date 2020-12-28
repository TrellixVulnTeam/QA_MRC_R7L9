

####  中文机器阅读理解Andoid客户端Demo

#### Tensorflow Lite Transformers Andorid  Chinese Machine Reading Comprehension Demo

- 在CMRC中微调的ALBERT[Albert_tiny_google](#)
- 转换ALBERT to TFLite
- 离线进行答案预测

#### 示例数据

CMRC2018 Dev





#### 基于Android的开发流程

##### 前提

- 安装 Android Studio （最新） [官网](https://developer.android.com/studio/index.html)

- 你应该有一台Android设备，或者 虚拟器

#####  Android Studio步骤

1. 打开 Android Studio  ，依次**File**  >>  **Open an existing Android Studio project**
2. 等待
3. 选择运行设备，并点击运行
4. gradle 下载预训练TFlite模型，并自动构建APP，并在目标设备上运行

##### 命令行步骤

1. 切换到当前工作目录，通过以下命令构建

   ```shell
   ./gradlew build
   ```

1. 通过**adb**安装应用

   ```shell
   adb install app/build/outputs/apk/debug/app-debug.apk
   ```

   

#### 模型转换过程

[here](#)

---

#### 参考

Demo参考TFlite官方例子: [tensorflow/examples](https://github.com/tensorflow/examples)

中文预训练ALBERT: [Albert_tiny_google](https://github.com/zhongbin1/bert_tokenization_for_java)

[BERT Tokenization For JAVA](https://github.com/zhongbin1/bert_tokenization_for_java)


