pipeline{
    agent{
	  label '172.31.10.184'
	 }
      stages{
	 
 		stage ('slave3') {
		
			steps {
				sh "sudo yum install httpd -y"
				sh " sudo service httpd start"
				sh "cp -r index.html /var/www/html/"
				sh " sudo chmod -R 777 /var/www/html/index.html"
			       }
			}
		}
        }


