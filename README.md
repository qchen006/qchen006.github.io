# How to use Hexo to write blog and publish to the master branch?

### Execute the following commands
 - ```git clone your own repo```<br>
Clone your own repository and checkout to hexo branch.

 - ```npm install hexo```<br>
 - ```npm install```<br>
These two commands install hexo and hexo git deployer and other depdencies

 - ```hexo clean```<br>
 - ```git clone https://github.com/iissnan/hexo-theme-next themes/next```<br>
Please remember to clone the Next repository before using ```hexo g``` as ```hexo g``` needs to use the next repository to generate<br><br>
 - ```hexo n``` New a post<br>
 - ```hexo g``` Generate the files using the .md files<br>
 - ```hexo s```  Serve the <br>
 - ```hexo d``` Deploy the latest blog website to this repo master branch<br>
 
 Use ```https://qchen006.github.io/``` to see the new blog


### MD file writing skills
#####图片 
```![](https://oss.navercorp.com/GWorks-Service/webtalk_docs/blob/master/webtalk-nginx/nginx-worksmobile.png) ```

#####锚点 
```Take me to [pookie](#pookie) ```
<br>
```### <a name="pookie"></a>Some heading ```

#####普通链接 
```Take me to [pookie](https://sdfdsadsfsadf) ```
