# Bmap_case

    var map = new _BMAP('Bmap')
    // 添加控件
    map.addControl(['tl_control', 'tl_navigation'])
    // 移除标记
    map.clearOverlays()
    // 添加标记
    map.markerAdd({
        lat: 116.404,
        lng: 39.915,
        title: '天安门',
        imgUrl: 'http://lbsyun.baidu.com/jsdemo/img/tianAnMen.jpg',
        content: '这是中华人民共和国天安门……'
    })

![Image text](https://github.com/zjiangming/Bmap_case/blob/master/dist/page.png)
