# Introduction

牛逼

```java
glVertexAttribPointer(0,3,GL_FLOAT,false,3 * 4,0);
        glEnableVertexAttribArray(0);

        glBindBuffer(GL_ARRAY_BUFFER,0);
        glBindVertexArray(0);
        //EBO解绑会被VAO保存,故需在VAO解绑后解绑
        glBindBuffer(GL_ELEMENT_ARRAY_BUFFER,0);
```

