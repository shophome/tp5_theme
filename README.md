# tp5_theme

安装  `composer require samplecms/tp5_theme`


事例

		<?php
		namespace app\index\controller;
		use tp\theme\Theme;
		class Index extends Theme
		{
			public $theme = 'default';
		    public function index()
		    {
		    	

		       
		       return  $this->make('index');
		    }
		}



主题对应文件 `public/themes/default/index/index/index.html`



###如有问题请在微博中 @太极拳那点事儿 http://weibo.com/sunkangchina