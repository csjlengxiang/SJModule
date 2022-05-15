# SJModule

###### 基于DifferenceKit的页面组件component框架，主要是把CollectionViewLayout重写.
###### 采用和IGList相同的方式，加入adapter，整合成module.
###### 在layout的prepare进行attris 的创建。attris包含cell，Supplementary，DecorationView。
###### 目前只需要cell 和 DecorationView，DecorationView 用来修饰section，一个module即为一个section，若干cell和一个DecorationView。
###### 由于加入了DifferenceKit，则需要管理 diff module。
###### 另外由于各个组件加载时机不定，会出现ABC，先出现AC，再出现B的闪动情况。
###### adapter加入module下载队列，并管理module出现的顺序

###### demo里都是关于collectionlayout和diffKit的使用和交互
