# LayoutConstraints
İOS Simple Autolayout Class

```Swift
        redView = UIView()
        redView.backgroundColor = UIColor.red
        view.addSubview(redView)
        
        greenView = UIView()
        greenView.backgroundColor = UIColor.green
        view.addSubview(greenView)
        
        blueView = UIView()
        blueView.backgroundColor = UIColor.blue
        view.addSubview(blueView)
```
- Use Simple and Easy Programmatically Autolayout Class with Swift 
```Swift
        const.width(item: greenView, value: 200)
        const.height(item: greenView, value: 100)
        const.centerX(item: greenView, toItem: self.view)
    
        const.size(item: redView, size: CGSize(width: 100, height: 100))
        const.centerX(item: redView, toItem: greenView)
        const.equalBottom(item: redView, toItem: self.view)
        const.bottom(item: redView, toItem: self.view, value: -40)
        
        const.fillWidth(item: blueView, toItem: self.view)
        const.height(item: blueView, value: 50)
        const.centerY(item: blueView, toItem: self.view)
        
        const.final()
```
