
```objc

 CAGradientLayer *layer = [CAGradientLayer layer];
    layer.startPoint = CGPointMake(0, 0);//（0，0）表示从左上角开始变化。默认值是(0.5,0.0)表示从x轴为中间，y为顶端的开始变化
    layer.endPoint = CGPointMake(1, 1);//（1，1）表示到右下角变化结束。默认值是(0.5,1.0)  表示从x轴为中间，y为低端的结束变化
    layer.colors = [NSArray arrayWithObjects:(id)[UIColor blueColor].CGColor,(id)[UIColor redColor].CGColor,(id)[UIColor greenColor].CGColor, nil];
    layer.locations = @[@0.0f,@0.6f,@1.0f];//渐变颜色的区间分布，locations的数组长度和color一致，这个值一般不用管它，默认是nil，会平均分布
    layer.frame = self.view.layer.bounds;
    [self.view.layer insertSublayer:layer atIndex:0];
    
```    
 