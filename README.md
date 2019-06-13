# cifar10-CNN
卷积神经网络CNN在cifar10上的应用

进行了分别是在单个GPU和多个GPU下进行了测试，所以代码就被分成了两部分
<table>
    <thead>
        <tr>
            <th>文件</th>
            <th>作用</th>
        </tr>
    </thead>
    <tbody>
        <tr> <th>cifar10_model.py</th> <th> 建立卷积神经模型，定义损失函数，训练器和正确率计算等函数</th> </tr>
        <tr> <th>cifar10_input.py</th> <th> </th>读取本地CIFAR-10的二进制文件格式的内容 </tr>
        <tr> <th>cifar10_train_eval.py </th> <th>训练CIFAR-10和评估CIFAR-10模型</th> </tr>
    </tbody>
</table>


<table>
    <thead>
        <tr>
            <th>文件</th>
            <th>作用</th>
        </tr>
    </thead>
    <tbody>
       <tr> <th>input.py</th>  <th>读取本地CIFAR-10的二进制文件格式的内容。</th> </tr>
       <tr> <th>cifar10.py </th>  <th> 建立CIFAR-10的模型。</th> </tr>
       <tr> <th>train.py </th>  <th> 在CPU或GPU上训练CIFAR-10的模型。</th> </tr>
       <tr> <th>eval.py </th>  <th>评估CIFAR-10模型的预测性能。</th> </tr>
       <tr> <th>multi_gpu_train.py </th>  <th> 在多GPU上训练CIFAR-10的模型。</th> </tr>
    </tbody>
</table>
