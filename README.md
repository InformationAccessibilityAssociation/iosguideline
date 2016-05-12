﻿# Accessibility Programming Guide for iOS 中文翻译（草稿）

<ul id="toc" rule="tree">
		<li class=" " data-aref="//apple_ref/doc/uid/TP40008785-CH1-SW1"><span class="nodisclosure"></span><span class="sectionName"><a href="declaration.htm">翻译声明</a></span></li>
		
       <li class=" " data-aref="//apple_ref/doc/uid/TP40008785-CH1-SW1"><span class="nodisclosure"></span><span class="sectionName"><a href="Introduction.htm#//apple_ref/doc/uid/TP40008785-CH1-SW1">介绍</a></span></li>
		
		<li data-aref="//apple_ref/doc/uid/TP40008785-CH100-SW1" rule="treeitem"><span class="disclosure"></span><span class="sectionName"><a href="Understanding_Accessibility_on_iOS.htm">理解iOS上的无障碍特性</a></span>
			<ul>
			<li class=" " data-aref="//apple_ref/doc/uid/TP40008785-CH100-SW3"><span class="nodisclosure"></span><span class="sectionName"><a onclick='s_objectID="https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/iPhoneAccessibili_3";return this.s_oc?this.s_oc(e):true' href="Understanding_Accessibility_on_iOS.htm#//apple_ref/doc/uid/TP40008785-CH100-SW3">无障碍特性和VoiceOver</a></span></li>
			
			<li class=" " data-aref="//apple_ref/doc/uid/TP40008785-CH100-SW4"><span class="nodisclosure"></span><span class="sectionName"><a onclick='s_objectID="https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/iPhoneAccessibili_4";return this.s_oc?this.s_oc(e):true' href="Understanding_Accessibility_on_iOS.htm#//apple_ref/doc/uid/TP40008785-CH100-SW4">为什么您应该构建应用的无障碍特性</a></span></li>
			
			<li  data-aref="//apple_ref/doc/uid/TP40008785-CH100-SW2" rule="treeitem"><span class="disclosure"></span><span class="sectionName"><a onclick='s_objectID="https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/iPhoneAccessibili_5";return this.s_oc?this.s_oc(e):true' href="Understanding_Accessibility_on_iOS.htm#//apple_ref/doc/uid/TP40008785-CH100-SW2">iOS的无障碍API及工具</a></span>
			
				<ul>
					<li class=" " data-aref="//apple_ref/doc/uid/TP40008785-CH100-SW6"><span class="nodisclosure"></span><span class="sectionName"><a onclick='s_objectID="https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/iPhoneAccessibili_6";return this.s_oc?this.s_oc(e):true' href="Understanding_Accessibility_on_iOS.htm#//apple_ref/doc/uid/TP40008785-CH100-SW6">UI无障碍编程接口</a></span></li>
					<li class=" " data-aref="//apple_ref/doc/uid/TP40008785-CH100-SW7"><span class="nodisclosure"></span><span class="sectionName"><a onclick='s_objectID="https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/iPhoneAccessibili_7";return this.s_oc?this.s_oc(e):true' href="Understanding_Accessibility_on_iOS.htm#//apple_ref/doc/uid/TP40008785-CH100-SW7">无障碍属性</a></span></li></ul></li>
				</ul>
		</li>
		<li data-aref="//apple_ref/doc/uid/TP40008785-CH102-SW5" rule="treeitem"><span class="disclosure"></span><span class="sectionName"><a onclick='s_objectID="https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/iPhoneAccessibili_8";return this.s_oc?this.s_oc(e):true' href="Making_Your_iOS_App_Accessible.htm#//apple_ref/doc/uid/TP40008785-CH102-SW5">构建您iOS应用程序的无障碍特性</a></span>
		<ul>
			<li  data-aref="//apple_ref/doc/uid/TP40008785-CH102-SW17" rule="treeitem"><span class="disclosure"></span><span class="sectionName"><a onclick='s_objectID="https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/iPhoneAccessibili_9";return this.s_oc?this.s_oc(e):true' href="Making_Your_iOS App_Accessible.htm#//apple_ref/doc/uid/TP40008785-CH102-SW17">让用户界面元素具有可访问性</a></span>
			<ul>
				<li class=" " data-aref="//apple_ref/doc/uid/TP40008785-CH102-SW9"><span class="nodisclosure"></span><span class="sectionName"><a onclick='s_objectID="https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/iPhoneAccessibili_10";return this.s_oc?this.s_oc(e):true' href="Making_Your_iOS_App_Accessible.htm#//apple_ref/doc/uid/TP40008785-CH102-SW9">让自定义的独立视图具有无障碍特性</a></span></li>
				<li class=" " data-aref="//apple_ref/doc/uid/TP40008785-CH102-SW10"><span class="nodisclosure"></span><span class="sectionName"><a onclick='s_objectID="https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/iPhoneAccessibili_11";return this.s_oc?this.s_oc(e):true' href="Making_Your_iOS_App_Accessible.htm#//apple_ref/doc/uid/TP40008785-CH102-SW10">让自定义容器视图的内容具有无障碍特性</a></span></li>
			</ul>
			</li>
			<li  data-aref="//apple_ref/doc/uid/TP40008785-CH102-SW4" rule="treeitem"><span class="disclosure"></span><span class="sectionName"><a onclick='s_objectID="https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/iPhoneAccessibili_12";return this.s_oc?this.s_oc(e):true' href="Making_Your_iOS_App_Accessible.htm#//apple_ref/doc/uid/TP40008785-CH102-SW4">提供准确和有用的属性信息</a></span>
				<ul>
					<li class=" " data-aref="//apple_ref/doc/uid/TP40008785-CH102-SW8"><span class="nodisclosure"></span><span class="sectionName"><a onclick='s_objectID="https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/iPhoneAccessibili_13";return this.s_oc?this.s_oc(e):true' href="Making_Your_iOS_App_Accessible.htm#//apple_ref/doc/uid/TP40008785-CH102-SW8">优化默认属性信息</a></span></li>
					<li data-aref="//apple_ref/doc/uid/TP40008785-CH102-SW6" rule="treeitem"><span class="disclosure"></span><span class="sectionName"><a onclick='s_objectID="https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/iPhoneAccessibili_14";return this.s_oc?this.s_oc(e):true' href="Making_Your_iOS_App_Accessible.htm#//apple_ref/doc/uid/TP40008785-CH102-SW6">制作有用的标签和提示</a></span>
						<ul>
							<li class=" " data-aref="//apple_ref/doc/uid/TP40008785-CH102-SW20"><span class="nodisclosure"></span><span class="sectionName"><a onclick='s_objectID="https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/iPhoneAccessibili_15";return this.s_oc?this.s_oc(e):true' href="Making_Your_iOS_App_Accessible.htm#//apple_ref/doc/uid/TP40008785-CH102-SW20">创建标签指南</a></span></li>
							<li class=" " data-aref="//apple_ref/doc/uid/TP40008785-CH102-SW11"><span class="nodisclosure"></span><span class="sectionName"><a onclick='s_objectID="https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/iPhoneAccessibili_16";return this.s_oc?this.s_oc(e):true' href="Making_Your_iOS_App_Accessible.htm#//apple_ref/doc/uid/TP40008785-CH102-SW11">创建提示指南</a></span></li>
						</ul>
					</li>
					<li class=" " data-aref="//apple_ref/doc/uid/TP40008785-CH102-SW7"><span class="nodisclosure"></span><span class="sectionName"><a onclick='s_objectID="https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/iPhoneAccessibili_17";return this.s_oc?this.s_oc(e):true' href="Making_Your_iOS_App_Accessible.htm#//apple_ref/doc/uid/TP40008785-CH102-SW7">定义恰当的特质</a></span></li>
					<li class=" " data-aref="//apple_ref/doc/uid/TP40008785-CH102-SW1"><span class="nodisclosure"></span><span class="sectionName"><a onclick='s_objectID="https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/iPhoneAccessibili_18";return this.s_oc?this.s_oc(e):true' href="Making_Your_iOS_App_Accessible.htm#//apple_ref/doc/uid/TP40008785-CH102-SW1">在Interface Builder中自定义属性信息</a></span></li>
					<li class=" " data-aref="//apple_ref/doc/uid/TP40008785-CH102-SW2"><span class="nodisclosure"></span><span class="sectionName"><a onclick='s_objectID="https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/iPhoneAccessibili_19";return this.s_oc?this.s_oc(e):true' href="Making_Your_iOS_App_Accessible.htm#//apple_ref/doc/uid/TP40008785-CH102-SW2">编程化处理自定义属性信息</a></span></li>
				</ul>
			</li>
			<li class=" " data-aref="//apple_ref/doc/uid/TP40008785-CH102-SW3"><span class="nodisclosure"></span><span class="sectionName"><a onclick='s_objectID="https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/iPhoneAccessibili_20";return this.s_oc?this.s_oc(e):true' href="Making_Your_iOS_App_Accessible.htm#//apple_ref/doc/uid/TP40008785-CH102-SW3">优化表格视图无障碍特性</a></span></li>
			<li class=" " data-aref="//apple_ref/doc/uid/TP40008785-CH102-SW25"><span class="nodisclosure"></span><span class="sectionName"><a onclick='s_objectID="https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/iPhoneAccessibili_21";return this.s_oc?this.s_oc(e):true' href="Making_Your_iOS_App_Accessible.htm#//apple_ref/doc/uid/TP40008785-CH102-SW25">让动态元素具有无障碍特性</a></span></li>
			<li class=" " data-aref="//apple_ref/doc/uid/TP40008785-CH102-SW26"><span class="nodisclosure"></span><span class="sectionName"><a onclick='s_objectID="https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/iPhoneAccessibili_22";return this.s_oc?this.s_oc(e):true' href="Making_Your_iOS_App_Accessible.htm#//apple_ref/doc/uid/TP40008785-CH102-SW26">让非文本数据具有无障碍特性</a></span></li>
			</ul>
		</li>
			<li class=" " data-aref="//apple_ref/doc/uid/TP40008785-CH99-SW1"><span class="nodisclosure"></span><span class="sectionName"><a onclick='s_objectID="https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/iPhoneAccessibili_23";return this.s_oc?this.s_oc(e):true' href="Document_Revision_History.htm">修订记录</a></span></li>
		</ul>