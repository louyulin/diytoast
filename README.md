# 自定义Toast
### 将系统Toast三秒后再显示第二个吐司进行时间消费,能够立即覆盖
#### 引入依赖:
    	allprojects {
    		repositories {
    			...
    			maven { url 'https://jitpack.io' }
    		}
    	}


        dependencies {
        	        compile 'com.github.louyulin:diytoast:v1.0'
        	}

#### 使用:

          LToast.showToast(context,index + "");