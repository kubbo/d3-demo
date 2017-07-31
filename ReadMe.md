

     d3.select('body').data(data).enter().append('p').text(function (d) {
            return '序号:'+d
        }).style('color',function (d) {
            return d >3 ? 'red':'blue'
        })

 * select 选择器
 * data 遍历数值
 * enter 遍历每个数值进入的处理流程
 * append 添加元素
 * text 设置元素的 text
 * style 设置元素的 style