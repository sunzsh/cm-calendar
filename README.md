# element-ui组件Calendar仅渲染当月版本

> cm-calendar 中的 cm 取名自 “current-month” 两个单词首字母

### 使用方法

1. 复制 `cm-calendar` 文件夹及内容到自己项目中
2. 在要使用的页面上引入组件（路径根据自己情况修改）：
    ```
    import CMCalendar from '@/components/cm-calendar'
    ```
3. 在 页面的 `components` 中注册组件：
    ```
    ... 
    components: {
        ...
        CMCalendar
    },
    ... 
    ```
4. 与 `el-calendar` 的使用方法完全相同，只是把组件名换成 `CMCalendar`
    ```
    <CMCalendar v-model="value"></CMCalendar>
    ```
