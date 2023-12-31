# roop-kaggle
- 【AI换脸】roop在Kaggle上的使用样例
- 只需一张脸的图片，即可完成视频内的换脸
- 含 unlock

## 前言
- 因为roop项目的Python环境依赖等问题的处理对于部分朋友比较复杂，所以特此提供了Kaggle版本的样例，可以直接在Kaggle的Notebook中运行
- 为什么选Kaggle，不用Google Colab？
  - 因为国内可以直连Kaggle，上Colab较麻烦，让更多人能快速使用到。
- 此样例会面向较广的使用者，所以会写得比较啰嗦、傻瓜式...
- 地址信息
  - **Kaggle Notebook**样例: [https://www.kaggle.com/code/alionsss/roop-kaggle](https://www.kaggle.com/code/alionsss/roop-kaggle)
  - 本项目的GitHub地址: [https://github.com/AlionSSS/roop-kaggle](https://github.com/AlionSSS/roop-kaggle)
  - roop项目GitHub地址: [https://github.com/s0md3v/roop](https://github.com/s0md3v/roop)


## 换脸效果样例 GIF
- 样例 1

![target_merged_1.gif](resource%2Fmerged_example%2Ftarget_merged_1.gif)

- 样例 2

![target_merged_2.gif](resource%2Fmerged_example%2Ftarget_merged_2.gif)

## 项目结构描述
```shell
roop-kaggle               # 项目目录
    resource              # 资源目录
        face_picture      # 人脸样例图片
        target_video      # 样例视频
        merged_example    # 合成后的样例GIF
    README.md             # README
    roop-kaggle.ipynb     # notebook文件
```
