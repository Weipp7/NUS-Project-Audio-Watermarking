# Audio-Watermarking
## Audio-Watermarking-using-DCT

采用图像dct的思路对音频文件进行分块，并将水印音频分块嵌入原音频文件中  
我的工作

a.Embedding Watermark

b.Extracting Watermark

c.对音频信号进行攻击，采取add noise,compress,reverbe,speedup几种攻击方式测试robustness

d.PSNR、NCC和 相关系数 指数评估技术的性能

## 食用方法：  
需要以下工具：  
 - scipy.io
 - scipy.fftpack
 - wave  
 下载源文件运行即可
 
 ## NOTE!
 在时间性能方面还有欠缺，食用过程可能有亿点点慢
 
 这是NUS暑期项目的一部分，整体项目实现了用DCT,DWT,LSB三种方法添加水印到音频中，并测试robustness。(每个分支对应着一个方法）
 
 [项目仓库地址](https://github.com/Eipi15926/Audio-Steganography-and-Watermark/tree/master)
 
 [Reference & Our Work](https://www.notion.so/5ffb5a886980429794fa265240bc0fb9?v=177c555b270246e0bdd788763e997c14)

 另：submit文件夹里是项目最终的提交结果，poster和short video都出自我手（自豪）
 
