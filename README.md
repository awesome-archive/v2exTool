# v2exTool
It's a tool to help you using v2ex better, you can check in, get the content of each node and more.   
The v2ex website is: `www.v2ex.com`
## How To Use It
`pip install v2extool`    
if you are in china, blocked by GFW     
you can try:     
`pip install v2extool -i https://pypi.douban.com/simple`
### login
`import v2extool`    
`v2extool.login(username="", password="")`
### check in
`v2extool.check_in`
### get the node's content 
`v2extool.node_content(page="", node_name="")`
### get personal info
`v2extool.self_info`
### get user info
`v2extool.user_info(username="")`   
or 
`v2extool.user_info(user_id="")`   
and you can type username and id both:    
`v2extool.user_info(username="", user_id="")`   
if you type both but discompare of them, system must recognise id fisrt
