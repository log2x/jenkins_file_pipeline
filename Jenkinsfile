pipeline {

	agent any
	stages {
		stage("re_build") {
			steps {

				echo "starting Re_building。。。。。"
				sh "./echo.sh"
			}
			post {
				always {
				 echo "预处理执行完成！！！"
				}
			}

		}




	}














}
