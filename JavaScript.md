#<font color="000">Javascript笔记</font>

##<font color="#666">关于函数</font>

1. 用对象收编函数

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
	    
2. 好玩的链式添加
	    
	    var Object = {
	    	fn : function (){
	    		return this;
	    	},
	    	fu : function (){
	    		return this;
	    	}
	    };
	    Object.fn().fu();
	    
	    
	    



<font size="4px"></font>

