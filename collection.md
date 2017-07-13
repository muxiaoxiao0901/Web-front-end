#### 1.cookie web存储机制 localStorage      
navigator.onLine() 判断是否是离线状态       
web存储机制 web Storage 两个主要目标：     
* 提供一种cookie以外的存储会话数据的途径    
* 提供一种存储大量可以跨会话存在的数据的机制。    
默认情况下，浏览器会在当前会话(session)缓存页面，当用户点击“前进”或“后退”按钮时，浏览器就会从缓存中加载页面
浏览器有一个特性叫“往返缓存”(back-forward cache或bfcache)，可以在用户使用浏览器的“后退”和“前进”按钮时加快页面的转换速度。这个缓存中不仅保存着页面数据，还保存了DOM和javascript的状态；实际上是将整个页面都保存在了内存里。如果页面位于bfcache中，那么再次打开该页面时就不会触发load事件   

