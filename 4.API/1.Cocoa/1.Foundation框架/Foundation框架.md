## Foundation框架

Cocoa 本身由 Objective-C 语言写成，因此 Objective-C 是开发 Cocoa 应用的首选语言。虽然也提供 Java 到 Cocoa 的绑定，但是在开发者中并未得到广泛采用。而且，由于使用桥接机制，Java 的绑定并不能全面利用 Cocoa 的所有功能。2005年，苹果公司宣布 Java 的 Cocoa 绑定在 Mac OS X 10.4 和之后版本中属被废弃的技术。换句话说，Cocoa API 中可能会逐渐出现不支援 Java 的功能。
>iOS开发是基于cocoa框架的。
cocoa框架类图
![](/assets/20151205105717540.jpg)

其实所有的Mac OS X和IOS程序都是由大量的对象构成，而这些对象的根对象都是NSObject，NSObject就处在Foundation框架之中。