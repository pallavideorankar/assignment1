pipeline{
    agent{
	  label '172.31.9.100'
	 }
      stages{
	 
 		stage ('slave2') {
		
			steps {
				sh "sudo yum install httpd -y"
				sh " sudo service httpd start"
				sh "cp -r index.html /var/www/html/"
				sh "chmod -R 777 /var/www/html/index.html"
			       }
			}
		}
        }


