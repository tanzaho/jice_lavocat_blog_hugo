[ ![Codeship Status for tanzaho/jice_lavocat_blog_hugo](https://codeship.com/projects/88507000-fb0f-0132-88a3-56a30f6b7674/status?branch=master)](https://codeship.com/projects/87058)


## Find and replace images : 
\{\{<img (.*) src="(.*)" (.*)>\}\}
replace with ->
<img $1 src="/$2" $3>