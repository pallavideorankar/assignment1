pipeline{
    agent{
	  label '172.31.10.184'
	 }
      stages{
	 
 		stage ('slave3') {
		
			steps {
				sh "yum install httpd -y"
				sh " service httpd start"
				sh "cp -r index.html /var/www/html/"
				sh "chmod -R 777 /var/www/html/index.html"
			       }
			}
		}
        }


