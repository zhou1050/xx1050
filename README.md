# [🟠🟡🟢🔵 机场订阅：xx1050.xyz](https://xx1050.xyz)

<td>👍👍👍👍👍</td> https://xx1050.xyz


---------

--------

<div class="theme-default-content content__default"><h3 id="1.x86-物理机"><a href="#x86-物理机" class="header-anchor">#</a> 1.x86 物理机</h3> <ul><li><p>x86物理机，范围很广，可以是各种"电脑"，或者J4125/N5105等小主机。</p></li> <li><p>这里介绍x86实机安装iStoreOS固件。</a> <h2 id="_2-准备工作"><a href="#_2-准备工作" class="header-anchor">#</a> 2.准备工作</h2> <ul><li>一个 U盘</li> <li>一个显示器</li> <li>一个键盘</li> <li>一台 windows 电脑</li></ul> <h2 id="_3-下载固件"><a href="#_3-下载固件" class="header-anchor">#</a> 3.下载固件</h2> <ul><li><a href="https://fw.koolcenter.com/iStoreOS/x86_64/" target="_blank" rel="noopener noreferrer">固件下载<span><svg xmlns="http://www.w3.org/2000/svg" aria-hidden="true" focusable="false" x="0px" y="0px" viewBox="0 0 100 100" width="15" height="15" class="icon outbound"><path fill="currentColor" d="M18.8,85.1h56l0,0c2.2,0,4-1.8,4-4v-32h-8v28h-48v-48h28v-8h-32l0,0c-2.2,0-4,1.8-4,4v56C14.8,83.3,16.6,85.1,18.8,85.1z"></path> <polygon fill="currentColor" points="45.7,48.7 51.3,54.3 77.2,28.5 77.2,37.2 85.2,37.2 85.2,14.9 62.8,14.9 62.8,22.9 71.5,22.9"></polygon></svg> <span class="sr-only">(opens new window)</span></span></a></li> <li><a href="https://fw.koolcenter.com/iStoreOS/x86_64_efi/" target="_blank" rel="noopener noreferrer">固件下载-EFI<span><svg xmlns="http://www.w3.org/2000/svg" aria-hidden="true" focusable="false" x="0px" y="0px" viewBox="0 0 100 100" width="15" height="15" class="icon outbound"><path fill="currentColor" d="M18.8,85.1h56l0,0c2.2,0,4-1.8,4-4v-32h-8v28h-48v-48h28v-8h-32l0,0c-2.2,0-4,1.8-4,4v56C14.8,83.3,16.6,85.1,18.8,85.1z"></path> <polygon fill="currentColor" points="45.7,48.7 51.3,54.3 77.2,28.5 77.2,37.2 85.2,37.2 85.2,14.9 62.8,14.9 62.8,22.9 71.5,22.9"></polygon></svg> <span class="sr-only">(opens new window)</span></span></a></li></ul> <p>越前面版本越新，请注意看中间的日期，比如 xxx20221123xx-xxx.img.gz。下载完成之后不需要解压。</p> <h2 id="_4-做启动盘"><a href="#_4-做启动盘" class="header-anchor">#</a> 4.做启动盘</h2> <ul><li>电脑上用 rufus 做 USB 启动盘</li></ul> <p><a href="https://rufus.ie/zh/" target="_blank" rel="noopener noreferrer">Rufus下载<span><svg xmlns="http://www.w3.org/2000/svg" aria-hidden="true" focusable="false" x="0px" y="0px" viewBox="0 0 100 100" width="15" height="15" class="icon outbound"><path fill="currentColor" d="M18.8,85.1h56l0,0c2.2,0,4-1.8,4-4v-32h-8v28h-48v-48h28v-8h-32l0,0c-2.2,0-4,1.8-4,4v56C14.8,83.3,16.6,85.1,18.8,85.1z"></path> <polygon fill="currentColor" points="45.7,48.7 51.3,54.3 77.2,28.5 77.2,37.2 85.2,37.2 85.2,14.9 62.8,14.9 62.8,22.9 71.5,22.9"></polygon></svg> <span class="sr-only">(opens new window)</span></span></a></p> <ul><li>电脑插入U盘，打开rufus工具，选择下载好的固件，把固件写入到U盘</li></ul> <p><p><img src="https://doc.linkease.com/assets/img/install_x86.45efb3b5.png" alt=""></p></p> <ul><li>把 U盘/键盘/显示器 接入X86机器</li></ul> <p>选择从U盘启动，一般按 F11 (x86机器太多，范围太广，可能不一定所有的机器都是F11快捷启动，具体自行查看)，选择接入的U盘，就可以启动。</p> <p>如果找不到U盘，那么可能你的U盘不兼容，需要换一个U盘。</p> <ul><li>把固件从U盘安装到系统</li></ul> <p>登录U盘系统，登录成功之后，输入：</p> <p><code>quickstart</code> (或者 qu + tab 自动补全)</p> <p>选择 Install X86，一直按确定，就行了。具体如下图所示： <p><p><img src="https://github.com/zhou1050/xx1050/assets/46239492/65a52817-6796-4aa2-8f0a-a38d29b2f155" alt=""></p></p> <ul><li>
 <ul><li>用 <code>Show Interfaces</code> 查看网线插入到了哪个网口，以及查看当前LAN口的IP</li></ul> <h2 id="_5-启动系统"><a href="#_5-启动系统" class="header-anchor">#</a> 5.启动系统</h2> <p>系统写入完成后，拔掉外接设备(U盘/键盘等)，通电启动。</p> <h3 id="进入后台管理"><a href="#进入后台管理" class="header-anchor">#</a> 进入后台管理</h3> <ul><li>默认IP http://192.168.100.1</li> <li>默认密码：password</li> <li>如果只有一个网口，默认的网口是 LAN；如果大于一个网口，默认 eth0 是 WAN 口，其它都是 LAN</li> <li>如果要修改 LAN 口 IP，首页有个内网设置，或者命令行用 quickstart 命令修改</li> <li>必读一轮我们的 <a href="/zh/guide/istoreos/question.html" class="">FAQ</a>，后续出现问题知道如何解决！</li></ul></div>



<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">iStore软件包 iStore .run Packages</h2><a id="user-content-istore软件包-istore-run-packages" class="anchor" aria-label="Permalink: iStore软件包 iStore .run Packages" href="#istore软件包-istore-run-packages"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>
<p dir="auto">本页面所下载的软件包插件仅适用于x86_64平台的机器。</p>
</li>
<li>
<p dir="auto">适用于KoolCenter iStoreOS 22.03.X的软件包</p>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto">常用代理软件包 Commonly Used Proxy Packages</h4><a id="user-content-常用代理软件包-commonly-used-proxy-packages" class="anchor" aria-label="Permalink: 常用代理软件包 Commonly Used Proxy Packages" href="#常用代理软件包-commonly-used-proxy-packages"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<table>
<thead>
<tr>
<th align="center">插件名</th>
<th align="center">功能</th>
<th align="center">下载</th>
<th align="center">编译日期</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">PassWall</td>
<td align="center">科学工具</td>
<td align="center"><a href="https://github.com/AUK9527/Are-u-ok/raw/main/x86/all/PassWall_4.76-1_x86_64_all_sdk_22.03.6.run">PassWall_4.76-1</a></td>
<td align="center">2024-03-21</td>
</tr>
<tr>
<td align="center">PassWall2</td>
<td align="center">科学工具</td>
<td align="center"><a href="https://github.com/AUK9527/Are-u-ok/raw/main/x86/all/PassWall2_1.28-4_x86_64_all_sdk_22.03.6.run">PassWall2_1.28-4</a></td>
<td align="center">2024-03-21</td>
</tr>
<tr>
<td align="center">SSR-Plus</td>
<td align="center">科学工具</td>
<td align="center"><a href="https://github.com/AUK9527/Are-u-ok/raw/main/x86/all/SSR-Plus_188-3_x86_64_all_sdk_22.03.6.run">SSR-Plus_188-3</a></td>
<td align="center">2024-03-12</td>
</tr>
<tr>
<td align="center">OpenClash</td>
<td align="center">科学工具</td>
<td align="center"><a href="https://github.com/AUK9527/Are-u-ok/raw/main/x86/all/OpenClash_0.46.003+x86_64_core.run">OpenClash_0.46.003</a></td>
<td align="center">2024-03-09</td>
</tr>
</tbody>
</table>
<ul dir="auto">
<li>passwall、passwall2、ssr-plus均使用 22.03.X sdk编译，依旧使用libopenssl1.1，无需libopenssl3依赖，安装后在服务里。</li>
<li>安装后passwall日志里提示一些依赖未安装属于正常现象，不影响使用，这些依赖固件里应该都自带的。可以到【系统】-【软件包】-【已安装】里确认。</li>
<li>如果你在安装此包前通过第三方软件源安装，可能导致意外的错误，例如本不需要libopenssl3，变得需要，此情况可能需要重置你的路由器。</li>
<li>自带clash核心的openclash，版本为0.46.001。如果安装完出现路由器断网，重启一次路由器。</li>
<li><strong>注意，上述软件包安装，部分依赖依然要通过opkg软件源在线安装。如果安装失败，检查路由器自身的网络情况，特别是旁路由模式下最容易出现网络问题。</strong></li>
<li><strong>再三注意需要路由器自身联网正常</strong></li>
</ul>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto">其它软件包 Other Packages</h4><a id="user-content-其它软件包-other-packages" class="anchor" aria-label="Permalink: 其它软件包 Other Packages" href="#其它软件包-other-packages"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<table>
<thead>
<tr>
<th align="center">插件名</th>
<th align="center">功能</th>
<th align="center">下载</th>
<th align="center">编译日期</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">AdGuardHome</td>
<td align="center">DNS/拦截</td>
<td align="center"><a href="https://github.com/AUK9527/Are-u-ok/raw/main/x86/all/adguardhome.run">下载</a></td>
<td align="center">2024-03-17</td>
</tr>
<tr>
<td align="center">MosDNS</td>
<td align="center">DNS 转发/分流器</td>
<td align="center"><a href="https://github.com/AUK9527/Are-u-ok/raw/main/x86/all/mosdns_5.3.1-1_x86_64_all.run">mosdns_5.3.1-1</a></td>
<td align="center">2024-02-26</td>
</tr>
<tr>
<td align="center">UnblockNeteaseMusic</td>
<td align="center">解锁网易云灰色歌曲</td>
<td align="center"><a href="https://github.com/AUK9527/Are-u-ok/raw/main/x86/all/unblockneteasemusic.run">下载</a></td>
<td align="center">2024-01-05</td>
</tr>
<tr>
<td align="center">VSSR</td>
<td align="center">HelloWorld 科学工具</td>
<td align="center"><a href="https://github.com/AUK9527/Are-u-ok/raw/main/x86/all/VSSR_x86.run">下载</a></td>
<td align="center">N/A</td>
</tr>
<tr>
<td align="center">ByPass</td>
<td align="center">ByPass 科学工具</td>
<td align="center"><a href="https://github.com/AUK9527/Are-u-ok/raw/main/x86/all/ByPass_x86.run">下载</a></td>
<td align="center">N/A</td>
</tr>
<tr>
<td align="center">ikoolproxy</td>
<td align="center">koolproxy去广告(不适合高于5.4内核的固件)</td>
<td align="center"><a href="https://github.com/AUK9527/Are-u-ok/raw/main/x86/all/ikoolproxy_x86.run">下载</a></td>
<td align="center">N/A</td>
</tr>
<tr>
<td align="center">adblock</td>
<td align="center">adblock去广告</td>
<td align="center"><a href="https://github.com/AUK9527/Are-u-ok/raw/main/x86/all/adblock_x86.run">下载</a></td>
<td align="center">N/A</td>
</tr>
<tr>
<td align="center">adbyby</td>
<td align="center">adbyby去广告</td>
<td align="center"><a href="https://github.com/AUK9527/Are-u-ok/raw/main/x86/all/adbyby_x86.run">下载</a></td>
<td align="center">N/A</td>
</tr>
<tr>
<td align="center">KMS</td>
<td align="center">KMS服务器</td>
<td align="center"><a href="https://github.com/AUK9527/Are-u-ok/raw/main/x86/all/KMS_x86.run">下载</a></td>
<td align="center">N/A</td>
</tr>
<tr>
<td align="center">OpenVPN</td>
<td align="center">OpenVPN客户端</td>
<td align="center"><a href="https://github.com/AUK9527/Are-u-ok/raw/main/x86/all/OpenVPN_x86.run">下载</a></td>
<td align="center">N/A</td>
</tr>
<tr>
<td align="center">OpenVPN-Server</td>
<td align="center">OpenVPN服务端</td>
<td align="center"><a href="https://github.com/AUK9527/Are-u-ok/raw/main/x86/all/OpenVPN-Server_x86.run">下载</a></td>
<td align="center">N/A</td>
</tr>
<tr>
<td align="center">NPS</td>
<td align="center">Nps内网穿透</td>
<td align="center"><a href="https://github.com/AUK9527/Are-u-ok/raw/main/x86/all/NPS_x86.run">下载</a></td>
<td align="center">N/A</td>
</tr>
</tbody>
</table>
<ul dir="auto">
<li><strong>AdGuardHome如果想自己配置，而不是使用默认配置，请删除 <code>/etc/AdGuardHome.yaml</code> 配置文件后，自己进行用户名，密码，web以及dns相关配置</strong></li>
</ul>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto">如何安装</h4><a id="user-content-如何安装" class="anchor" aria-label="Permalink: 如何安装" href="#如何安装"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>
<p dir="auto">下载后，来到iStore应用商店页面，点击手动安装，点击选择上传或者直接拖放文件
<a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/7bb6bb7288f22482f4b7474270ab00d092692bb111b2130ea210c37dfc51f6c8/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f41554b393532372f4172652d752d6f6b406d61737465722f617070732f696e7374616c6c2e706e67"><img src="https://camo.githubusercontent.com/7bb6bb7288f22482f4b7474270ab00d092692bb111b2130ea210c37dfc51f6c8/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f41554b393532372f4172652d752d6f6b406d61737465722f617070732f696e7374616c6c2e706e67" alt="png" data-canonical-src="https://cdn.jsdelivr.net/gh/AUK9527/Are-u-ok@master/apps/install.png" style="max-width: 100%;"></a></p>
</li>
<li>
<p dir="auto">对于没有iStore应用商店的OpenWrt也可以使用以下方法。</p>
</li>
</ul>
<p dir="auto">将 .run 文件上传到路由器上，然后在终端环境执行</p>
<div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">sh 包名.run</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="sh 包名.run" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto">例</p>
<div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">sh PassWall_4.75-8_x86_64_all_sdk_22.03.6.run</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="sh PassWall_4.75-8_x86_64_all_sdk_22.03.6.run" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto">如果文件不在当前路径记得填写路径，下例</p>
<div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">sh /tmp/upload/PassWall_4.75-8_x86_64_all_sdk_22.03.6.run</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="sh /tmp/upload/PassWall_4.75-8_x86_64_all_sdk_22.03.6.run" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</article></div>
