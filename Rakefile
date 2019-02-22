task :publish do
	puts '开始生成'
	`jekyll build`
	puts '拷贝网站到baozi2.github.io'
	`cp -r _site/* ../baozi2.github.io`
	puts '发布更新'
	`cd ../baozi2.github.io && git push`
end