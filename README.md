# tp5_theme
thinkphp5 theme composer方式安装 


		<?php
		namespace app\index\controller;
		use tp\Theme;
		class Index extends Theme
		{
			public $theme = 'default';
		    public function index()
		    {
		    	

		       
		       return  $this->make('index');
		    }
		}



主题对应文件 `public/themes/default/index/index/index.html`