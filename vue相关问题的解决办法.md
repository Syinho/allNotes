[Toc]

## 1. v-html的图片大小处理

- 使用正则表达式将所有的图片的`<img `都替换成带样式的html片段

  - ```vue
    <p v-html="content"></p>
    <script setup>
    	content.value=data.replace(/<img/g,"<img style='max-width:100%;height:auto;'")
    </script>
    ```





