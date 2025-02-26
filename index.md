# 沟通是一场无限游戏 - 《沟通的方法》速查笔记

> 我们学习沟通的方法，不是为了取悦别人，而是为了赢得尊重，影响他人，最终解决问题
>
 #目录

#前言

connectDevice 接口内部变更
swipe 滑动接口变更
scroll_to_element_by_xpath 接口变更
添加 clear_element_text_by_resourceId，之前的 by_xpath 不再支持
get_element_all_info_by_resourceid 接口变更
show_toast 接口不再支持
添加 get_checked_info_by_resource_id 接口，替换之前中科的 AT 接口
watcher：由于内部轮询机制，无法立即停止 watcher，需要上层在 callback 方法中使用标志位来保证 callback 只执行一次
