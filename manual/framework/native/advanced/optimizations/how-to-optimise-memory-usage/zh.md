如何优化内存使用
===

##如何优化内存使用




    CCTextureCache::sharedTextureCache()->dumpCachedTextureInfo();


Cocos2d: cocos2d: "cc_fps_images" rc=5 id=3 256 x 32 @ 16 bpp => 16 KB








- 字体和粒子优化,在此有两条小提示：使用BMFont字体显示游戏分数时，请尽可能使用最少数量的文字。例如只想要显示单位数的数字，你可以移除所有字母。至于粒子，可以通过减少粒子数来降低内存使用。




