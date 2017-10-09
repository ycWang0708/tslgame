使用：
<pre><code>pip install pynput         
python tslgame.py
</code></pre>    

f7 = 开/关脚本    
开启脚本后按鼠标左键就会自动向下偏移，按pageUp/pageDown可以切换不同的武器预设。    
武器预设为m16时按住鼠标左键会自动连点。    

f8 = 开/关调试模式    
调试模式开启后不再使用武器预设数据，而是以15px为基础，通过pageUp/pageDown自由控制偏移量。    
你可以通过这个模式寻找适合不同武器的偏移量，然后写回到武器预设里。    

**注意：这个脚本已经可以运行，但是武器预设的偏移量并没有经过实际测试。**    
如果你有兴趣的话欢迎使用f8调试模式测试各个武器的偏移量，然后提交pull request给我
