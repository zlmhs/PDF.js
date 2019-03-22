### 使用场景
- type=file上传pdf文件、预览
- 后台返回base64格式的pdf，前台进行展示

### 使用方法
```
  /**
   * base64 to Blob for upload
   * @param {*} b64Data 64code
   * @param {*} element 放置canvas画布的元素
   * @param {*} element 参照图片尺寸的元素
  */

  showPdfFile(b64Data, ele, eleWidth)

```