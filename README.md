# AndroidImageSlider

        修改自AndroidImageSlider
        https://github.com/daimajia/AndroidImageSlider

        使用glide加载的AndroidImageSlider
        具体使用方法参照上方网址



        远程依赖方法在项目根目录下的build.gradle添加如下
        allprojects {
        		repositories {
        			...
        			<!--添加的话，就这一句-->
        			maven { url "https://jitpack.io" }
        		}
        	}


        在引用项目处添加
        dependencies {
        	        compile 'com.github.yaozs:AndroidImageSlider-glide:1.0.0'
        	}

