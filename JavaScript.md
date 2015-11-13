#<font color="000">Javascript笔记</font>

##<font color="#666">关于函数</font>

1. 函数的各种创建

	    function fn(){};
	    or
	    function (){};匿名函数
	    or
	    var fn = function (){};
2. 用对象收编函数

	    var Object = {
	    	fn : function (){
	    		return;
	    	},
	    	fu : function (){
	    		return;
	    	}
	    };
	    Object.fn();
	    Object.fu();
	    
3. 好玩的链式添加
	    
	    var Object = {
	    	fn : function (){
	    		return this;
	    	},
	    	fu : function (){
	    		return this;
	    	}
	    };
	    Object.fn().fu();
	    

