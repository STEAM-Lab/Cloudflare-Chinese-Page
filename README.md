# Cloudflare-Chinese-Page

自定义Cloudflare为中文页面，依据Cloudflare官方的界面源码进行翻译。

HTML语言编写，使用者可以轻松编辑源码中的文字。

如果网站是面向国内用户的，自定义页面可以很好的避免了部分访问者因不了解英文说明而直接关闭网页。 

网站 <https://DevHjz.com/> 

统一演示地址：
https://Chinese.Pages.Dev/

⚠注意：
1.🛑部署到自己的网站使用前务必先使文件在你自己处托管更换网站（域）名及邮箱！❗❗❗ 

请直接编辑并部署V3文件夹中的文件，这个才是最新的！OSS中的文件仅为备份使用，OSS文件夹下的所有文件均请求自Cloudflare，无需托管。

✅欢迎使用新版5秒盾界面，文件名：5s.html

2.重大版本更新：2022-2-19更新了V3版本，删除了1000的自定义界面（难以操作），增加了没有缓存的提示。

3.修复了5秒盾的BUG和5XX错误的排版问题以及若干BUGs。

4.下方“由Cloudflare提供防护”的字样可以直接在自定义界面中删除或更改。

请正在使用V2的用户及时更新到V3以解决问题。

如果JS/CSS访问慢，可以手动将代码中的https://cloudflare.com/cdn-cgi/ 更换为你自己的域名/cdn-cgi/或只保留/cdn-cgi/，但要注意如只保留/cdn-cgi/，删除设置的域名在自定义界面设置时需先托管于你自己经过Cloudflare缓存的对应域名的服务器上，然后从自己的链接添加。

感谢@186526大佬提供的优化思路！ https://github.com/186526/CloudflareCustomErrorPage
